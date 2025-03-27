# Project 1: Sales Data CSV Cleanup and Upload to S3

## Goal
Learn basic data handling and AWS S3 usage by cleaning a sales dataset and uploading it to S3.

## Steps
1. Downloaded a sales CSV dataset (e.g., Superstore Sales from Kaggle).
2. Used Python and pandas to remove duplicates and handle missing values.
3. Uploaded the cleaned CSV to an AWS S3 bucket using boto3.

## Tools
- Python, pandas, boto3
- AWS S3

## Results
- Cleaned dataset: Reduced rows from 7800 to 7989 after removing duplicates.
- Uploaded to: `s3://practice-buck-011111/cleansed_file.csv`
