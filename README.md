# What Drives DIY Video Views?
Throughout this project, we focused on creating a machine learning model to determine what qualities a video 'must have' for it to be considered a “successful” YouTube video. Our group focused specifically on DIY videos published in 2024. We pulled our data using the YouTube API, cleaned the data, and then created multiple visualizations based on what we found from the datasets.

# Machine Learning & Text Processing Notebooks

## Overview
This repository contains Jupyter notebooks for machine learning model evaluation, text data preprocessing, and API-based data retrieval.

## Team Members
- Yannis Papadopoulos
- Amy Dos Santos
- Saloum Bouchaaya
- Crystal Gonzales
- Zoey Quach

## Repository Contents
This repository includes essential Jupyter notebooks and supporting files for our project.

### Files
- `API_Calls_Data_Cleaning.ipynb`: Handles API requests for retrieving YouTube channel and video data for analysis, also includes data cleaning.
- `Data_Cleaning_Language.ipynb`: Preprocessing script to clean text data and remove non-English channels.
- `ML_Models_Part1.ipynb`: Best Results, Uses Random Forest, XGBoost, and Decision Trees for Machine Learning.
- `ML_Models_Part2.ipynb`: Uses Random Forest, XGBoost, and Decision Trees for Machine Learning.
- `ML_Models_Less_Accuracy.ipynb`: Uses Random Forest, XGBoost, and Decision Trees for Machine Learning with lower accuracy, uses mostly text data.

### Subfolders
- `/data`: Contains datasets used in the project (CSV, JSON).
- `/models`: Includes saved machine learning models.

## Interactive Visualization
The project includes visualizations for model performance and data processing:
- Confusion matrices for classification models.
- Word clouds and frequency distributions for text analysis.
- [Our Tableau Visualization](https://public.tableau.com/app/profile/saloum.bochaaya/viz/final__book/Story1?publish=yes)

## How to Run
To execute the notebooks, follow these steps:
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open and run any `.ipynb` file.

## Data Points Used
- **c_channel_id**: YouTube channel ID's.
- **c_channel_title**: YouTube channel titles.
- **c_channel_upload_playlist**: YouTube channels upload playlist ID.
- **c_channel_subCount**: Total number of subscriber's for a channel.
- **c_channel_videoCount**: Total number of video's for a channel.
- **c_channel_viewCount**: Total number of view's for a channel.
- **v_video_id**: YouTube video ID.
- **v_title**: YouTube video title.
- **v_date_publishedAt**: Date video was published at.
- **v_time_publishedAt**: Time video was published at.
- **v_duration**: YouTube video duration.
- **v_category_id**: YouTube video category ID.
- **v_tags**: YouTube video tag's.
- **v_description**: YouTube video description.
- **v_comment_count**: YouTube video comment count.
- **v_likes**: YouTube video number of likes.
- **v_views**: YouTube video number of views (our Target or y).
- **v_definition**: YouTube video definition.
- **v_caption**: Weather or not a video has captions.
- **v_age_restricted**: YouTube video age restriction if present.
- **v_made_for_kids**: Weather or not a video was made for children.

## Technologies and Tools
- **Jupyter Notebook**: Interactive computing environment.
- **Scikit-learn & XGBoost**: Machine learning model development.
- **Pandas & NumPy & Scipy**: Data manipulation and numerical computing.
- **re(Regex)**: Text preprocessing and NLP.
- **LangDetect**: Language detection.
- **API Integration**: Fetching YouTube data for analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **Tableau**: Data Visualization.

## Data Sources
- Custom datasets (CSV, JSON).
- Publicly available NLP and ML datasets.
- YouTube API for channel and video data.

## YouTube API License
This project uses the YouTube API. By using the YouTube API, you agree to comply with the YouTube API Terms of Service.
For full terms and conditions, visit the [YouTube API Terms of Service](https://developers.google.com/YouTube/terms).

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Ethical Considerations
This project does not involve personally identifiable or sensitive data. Ethical aspects such as bias and fairness are considered in data preprocessing and model evaluation.

## References:
- ChatGPT
- PowerPoint template taken from 24Slides PowerPoint Templates: (https://24slides.com/templates/all)
