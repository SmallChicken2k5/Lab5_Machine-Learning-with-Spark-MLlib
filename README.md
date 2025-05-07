# SparkML - Sentiment Analysis with Movie Reviews

## Overview

This project demonstrates the use of PySpark and Spark MLlib for sentiment analysis on the **Large Movie Review Dataset**. The dataset contains 50,000 movie reviews labeled as positive or negative, making it an excellent benchmark for classification tasks.

## Project Structure

```
.
├── Activity.ipynb                # Main notebook for the lab activities
├── Assignment.ipynb              # Additional assignment notebook
├── adult.csv                     # Example dataset for auxiliary tasks
├── Bài Lab 05_ PySpark - Spark MLlib.pdf  # Lab instructions
├── README.md                     # Project documentation
├── .devcontainer/                # Development container configuration
│   └── devcontainer.json
├── data/                         # Dataset directory
│   └── aclImdb/                  # Large Movie Review Dataset
│       ├── imdb.vocab            # Vocabulary file
│       ├── imdbEr.txt            # Expected ratings for tokens
│       ├── README                # Dataset documentation
│       ├── train/                # Training data
│       └── test/                 # Test data
```

## Dataset Details

The **Large Movie Review Dataset** is organized as follows:
- **Train/Test Split**: 25,000 reviews each for training and testing.
- **Labels**: Reviews are labeled as `pos` (positive) or `neg` (negative).
- **File Naming Convention**: `[id]_[rating].txt` where `[rating]` is the IMDb score (e.g., `200_8.txt`).

For more details, refer to the dataset's [README](data/aclImdb/README).

## Requirements

- Python 3
- PySpark
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/SmallChicken2k5/Lab5_Machine-Learning-with-Spark-MLlib.git
    cd Lab5_Machine-Learning-with-Spark-MLlib
    ```

2. Install dependencies:

3. Open the development container (if using VS Code):
    - Ensure Docker is running.
    - Open the project in VS Code and reopen in the dev container.

4. Launch Jupyter Notebook:

## Usage

- Open `Activity.ipynb` to follow the lab instructions.
- Use the `Assignment.ipynb` notebook for additional exercises.
- Modify and experiment with the PySpark code to explore the dataset and train models.

## Goals

- Learn how to preprocess text data using PySpark.
- Train and evaluate machine learning models with Spark MLlib.
- Perform sentiment analysis on movie reviews.

## About the Author

This project was created and maintained by [SmallChicken2k5](https://github.com/SmallChicken2k5), a passionate developer and data enthusiast. Feel free to reach out or contribute to the repository!

For inquiries, contact me via email: [thp.gia@gmail.com](mailto:thp.gia@gmail.com).

## References

- [Large Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)
- [PySpark Documentation](https://spark.apache.org/docs/latest/api/python/)
- [Spark MLlib Guide](https://spark.apache.org/mllib/)

## License

This project is for educational purposes only. Please refer to the dataset's license for usage restrictions.