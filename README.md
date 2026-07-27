# TikTok Claims Analysis

## Project Overview

This educational project examines synthetic TikTok video data using Python and pandas. The analysis was completed as part of the Google Advanced Data Analytics Professional Certificate.

The broader project goal is to prepare data for a future machine learning model that can classify videos as either claims or opinions.

## Business Problem

TikTok receives reports about videos containing claims and opinions. A classification model could help moderators prioritize reported content and reduce the review backlog.

This stage of the project focuses on inspecting, organizing, and understanding the data before exploratory data analysis and model development.

## Dataset

The dataset contains 19,382 TikTok video records and 12 original columns.

The variables include:

- Claim status
- Video duration
- Video transcription text
- Verification status
- Author ban status
- Video views
- Video likes
- Video shares
- Video downloads
- Video comments

The dataset is synthetic and was created for educational purposes. It does not represent TikTok's actual internal data.

## Tools and Skills

- Python
- pandas
- NumPy
- Jupyter Notebook
- Data inspection
- Descriptive statistics
- Boolean filtering
- Grouping and aggregation
- Feature engineering
- Exploratory data analysis preparation

## Tasks Completed

- Imported the dataset into a pandas DataFrame
- Reviewed the first rows of the data
- Inspected column data types and non-null values
- Calculated descriptive statistics
- Compared claim and opinion videos
- Examined engagement by author ban status
- Created engagement-rate variables
- Prepared recommendations for future modeling

## New Variables Created

- `likes_per_view`
- `comments_per_view`
- `shares_per_view`

These variables help compare engagement across videos with different total view counts.

## Key Findings

- The dataset is nearly balanced between claim and opinion videos.
- There are 9,608 claim videos and 9,476 opinion videos.
- Claim videos receive substantially more views than opinion videos.
- Claim videos also have higher like, comment, and share engagement rates.
- Videos from banned and under-review authors generally receive more engagement than videos from active authors.
- Claim status, author ban status, and engagement measurements may be useful variables for future classification modeling.

## Recommended Next Steps

- Perform more detailed exploratory data analysis
- Investigate and handle missing values
- Examine correlations among engagement variables
- Evaluate whether additional features should be created
- Select useful predictors
- Build and evaluate a classification model

## Project File

- `tiktok_claims_analysis.ipynb` — completed Python notebook

## Note

This is an educational project based on synthetic data and course materials from the Google Advanced Data Analytics Professional Certificate.
