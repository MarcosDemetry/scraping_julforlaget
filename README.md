# Exploring Julförlagets Catalogue


## What's this about?

Every year, kids in Sweden could sell a Christmas magazine and based on their sales earn points. With these points, they could either claim rewards or convert the points to cash. This is a small exploration of the products, points and cash rewards through [Svenska Julförlaget](https://julforlaget.se/jultidningar/premier/).

This project was inspired by two things. First, there was a blog post on a Swedish economics blog about this yesterday by Robert Östling ([check out the blog post here](https://ekonomistas.se/2021/11/16/kop-julklappar-till-hela-slakten-utan-att-betala-en-krona/)). Second, I should be studying and this is was a great outlet for my burdening procrastination.

Seeing that this is an opportunity to completely waste my time, I couldn't pass on it. I wanted to explore how the sales, points earned, products and cash rewards relate to each other.
I've gone to their websites, scraped data, did some manual input of data, merged everything together in a big soup of a dataset and explored the data using heatmaps (*yes, everyone loves heatmaps!*), histograms and box plots.

## Where did you get the data and where do I find it?

In this notebook, I've scraped information on the reward products ([through Svenska Julförlagets website](https://julforlaget.se/jultidningar/premier/)). In this repository, you'll find a dataset with the scraped data in "/data/raw_data.xlsx. Let's not unnecessarily bombard their server. Just use this data.

Here's the link with information on [converting sales to points and points to cash rewards](https://julforlaget.se/userfiles/attachments/2021/Folder_tabellen_2021_web_SE.pdf). I've manually entered this information in the Excel-files *raw_sales_to_points.xlsx* and *raw_points_to_cash.xlsx*

Finally, I saved the combined data in "/data/clean_data.xlsx".

## The Notebook
1. The one with Ryan Gosling and Rachel McAdams is amazing.
2. The JupyterLab notebook is where all the juicy stuff is, check it out [here](https://github.com/MarcosDemetry/scraping_julforlaget/blob/master/EDA_julforlag.ipynb).
3. Works best if you clone the repository and play around with the notebook yourself!

## Example output
Here are two examples of products and how many points are required to claim them in contrast to the distribution of points for all products:
<img src="https://github.com/MarcosDemetry/scraping_julforlaget/blob/master/output/figs_inspecting_row_nr/fig_points_in_hist_for_row_50.png" width="600" height="450" />

<img src="https://github.com/MarcosDemetry/scraping_julforlaget/blob/master/output/figs_inspecting_row_nr/fig_points_in_hist_for_row_100.png" width="600" height="450" />

<img src="https://github.com/MarcosDemetry/scraping_julforlaget/blob/master/output/1_heatmap.png" width="600" height="600" />

<img src="https://github.com/MarcosDemetry/scraping_julforlaget/blob/master/output/5_cash_reward_boxplot.png" width="600" height="600" />

