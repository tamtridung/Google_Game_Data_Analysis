# Google_Game_Data_Analysis

## Description:

This project is to help game developers, start-ups, ... answer the BIG question **"How should I invest in games in Google Play Store to easily bring success?"**
<p align="center">
  <img src="https://user-images.githubusercontent.com/87942072/135633454-8238855e-fbab-4c60-844f-d16dd8e804e0.png" />
</p>

## Dataset:
- We use 2 dataset for this project
  - [Google Play Store Apps](https://www.kaggle.com/gauthamp10/google-playstore-apps):      645.13 MB   - 24 columns  - 2,312,944 rows
  - [Google Play Store User Review](https://www.kaggle.com/lava18/google-play-store-apps):  7.31 MB     - 5 columns   -  64,296 rows

## File structure:
- [**Google_Game_Report.pdf**](https://github.com/tamtridung/Google_Game_Data_Analysis/blob/main/Google_Game_Report.pdf): This is the Google Data Studio Report
- [**Google_Game_Report.pdf**](https://github.com/tamtridung/Google_Game_Data_Analysis/blob/main/data_preprocessing_EDA.ipynb): This notebook contains all steps of Clean Data, EDA, Save Data

## Technologies - Techniques:
- Pandas, 
- Matplotlib, Seaborn
- Python 3.8

## EDA and Report by Google Data Studio
I will highlight some key points in this project, you can find more detail in [**Google_Game_Report.pdf**](https://github.com/tamtridung/Google_Game_Data_Analysis/blob/main/Google_Game_Report.pdf) 

### Market overal:
<p align="center">
  <img src="https://user-images.githubusercontent.com/87942072/135635152-421603e3-2336-44d6-bd49-6485018cadad.png" />
</p>

- The number of new games released has always increased over the years.
- **Install Rate Per Game** was high in 2010, 2012, 2013 because in these years were the birth of some legendary games, such as: Talking Tom, Angry Bird (2010); Subway Surfers (2012); May Talking Tom (2013).
- The game market is still on the trend of development however high competition

### The Best Potential Categories 
<p align="center">
  <img src="https://user-images.githubusercontent.com/87942072/135637851-79fe70d2-4bbf-4c27-91f5-6b03beb8e8dd.png" />
</p>

- In the chart **INSTALL RATE ACROSS CATEGORIES**, we can see, those categories: Action, Simualtion, Racing, Role Playing, Strategy, Music have Install rate bigger than Avg. Install Rate. That mean, those Categories have the most potential to grow.
- Look at chart **RATING RATE ACROSS CATEGORIES**, Music category got the least rating 4*-5*. So it is not a good place for us to invest.
- **ACTION - SIMULATION - RACING - ROLE PLAYING - STRATEGY** is the most potential categories

### Best time to release Game:
<p align="center">
  <img src="https://user-images.githubusercontent.com/87942072/135639671-7cf13ec4-e741-459e-bce0-1665aec38723.png" />
</p>

### Price and Size?

<p align="center">
  <img src="https://user-images.githubusercontent.com/87942072/135639892-ce14c5b6-0d3a-4df1-a428-490bd2b41ea7.png" />
</p>

## Conclution
**These are our advices if you want to successfull in the game market! (Sep-2021)**

![image](https://user-images.githubusercontent.com/87942072/135640103-6c094200-45a9-4463-bcd7-8ba4f3eec257.png)

## Next Steps
- Deep dive analysis into 5 categories: **ACTION - SIMULATION - RACING - ROLE PLAYING - STRATEGY**
- Analysis more in some hug installation game like: PugG, LienMinhHuyenThoai,...
