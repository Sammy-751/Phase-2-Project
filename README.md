{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "9a66e474-d047-4159-ab3a-c364b6500293",
   "metadata": {},
   "source": [
    "# VIEWERS PRODUCTION STUDIO - Movie Data Analysis\n",
    "\n",
    "## Overview\n",
    "\n",
    "This project analyzes historical movie data to identify trends in genres, budgets, and release timings that contribute to box office success. The goal is to provide actionable insights for a new movie studio, \"Viewers Production Studio,\" to make data-driven decisions about film production.\n",
    "\n",
    "## Business Understanding\n",
    "\n",
    "Viewers Production Studio is entering the movie industry and needs to make informed decisions about film production to maximize profitability. This analysis aims to identify key factors that contribute to box office success, such as genres, budgets, and release timings, by examining historical movie data.\n",
    "\n",
    "## Data Understanding\n",
    "\n",
    "The analysis utilizes several datasets:\n",
    "\n",
    "- **bom.movie_gross.csv**: Contains box office gross data, including domestic and foreign receipts.\n",
    "- **tmdb.movies.csv**: Provides movie metadata from The Movie Database (TMDb), including genres, popularity, and release dates.\n",
    "- **tn.movie_budgets.csv**: Includes production budgets and worldwide gross figures.\n",
    "- **im.db**: An SQLite database with additional movie information.\n",
    "\n",
    "These datasets were cleaned and preprocessed to handle missing values, convert data types, and remove duplicates.\n",
    "\n",
    "## Data Understanding and Analysis\n",
    "\n",
    "The analysis involved:\n",
    "\n",
    "- Exploring the relationship between movie genres and profitability.\n",
    "- Investigating how release timing affects box office revenue.\n",
    "- Examining the correlation between production budgets and return on investment (ROI).\n",
    "- Conducting statistical tests, such as ANOVA, to assess the significance of findings related to genre profitability.\n",
    "\n",
    "Key findings include:\n",
    "\n",
    "- **Popularity vs. Profit**: A moderate positive correlation (r = 0.40) exists between movie popularity and profit, but it is not a strong predictor of financial success.\n",
    "- **Ratings Impact**: Movie ratings (vote averages) show a very weak correlation (r = 0.10) with profit, indicating that high ratings do not necessarily lead to high profits.\n",
    "- **Genre Profitability**: ANOVA testing (F-statistic: 1.96, p-value: 0.14) shows no significant difference in profitability among the top three movie genres, suggesting genre alone is not a determinant of success.\n",
    "\n",
    "## Conclusion\n",
    "\n",
    "Based on the analysis, the following recommendations are provided:\n",
    "\n",
    "- **Prioritize High-ROI Genres**: Focus on genres with historically high returns on investment rather than just popular ones (e.g., Fantasy-Romance or Adventure-Drama-Sport).\n",
    "- **Optimize Beyond Popularity**: Consider factors like budget efficiency, release timing, and market trends in addition to popularity and ratings when planning film production.\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "6f5e52c4-0e00-4f36-822a-c315a3c98f99",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
