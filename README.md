# Wines of the World

Here, we will be analyzing the review data from over 150,000 wine reviews. Originating from ([WineEnthisiast][WineEnthisiast] ↗), and found on ([Kaggle.com][kaggle] ↗). All reviews originate from each of the 6 populated continents, at least those where wine could be produced! Each wine was rated on a scale of 1-100 by 19 different reviewers, only those with a rating greater than 80 are included here.

The data is categorized by wine variety, location, winery, price, and description. We will be primarily interested in the wine **variety** and its **location**.

I highly reccomend partitioning this analysis within a Jupyter notebook, processing all the data as one combined python file would be more cumbersome than needed. 

This analysis only requires the additional `winemag-data_first150k.csv` or `winemag-data-130k-v2.csv` files to be stored in the same directory as your `winereviews.ipynb` (Jupyter) file, unless you want to reference the aforementioned files another way. 

[WineEnthisiast]: http://www.winemag.com/?s=&drink_type=wine
[kaggle]: https://www.kaggle.com/datasets/zynicide/wine-reviews
