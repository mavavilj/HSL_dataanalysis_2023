# HSL data-analysis 2023
My entry for HSL "Data Engineer" position.

Jupyter, Python, and data inferring with limited knowledge.

Used libraries:

- jupyter (1.0.0)
- matplotlib (3.3.4)
- numpy (1.19.2)
- pandas_ods_reader (0.1.2)
- pandas (1.1.5)
- utm (0.7.0)

Usage would be to place the .ipynb in a folder and open it in a Jupyter notebook instance.
However, due to not including the data file, the .ipynb cannot be ran.

However, you can open the .html in a browser.

# Problem explanation

## Schedule:

4 days

## Data:

About 3500 rows and 11 columns.

Date/time, location (coordinate system not given), and technical data about two vessels.

There are data patterns that have not been given empirical explanation by the data gatherer.

## Execution:

Inferring is done in a "missing data" style context due to missing knowledge about phenomena 
that may cause the patterns that are observed and how observing the patterns should be used to
inform how to optimize the usage of vessels. One must therefore make assumptions
by using knowledge from literature.

It's possible to also see patterns that could be improved with machine learning, but due to 
missing empirical explanation there is no real meaning to doing modeling, because one
cannot know how to infer the data, since one lacks access 
to the actual empirical knowledge.

Best practice (w.r.t. to literature) and carefulness of not saying things
that are not known about are still used to infer "possible phenomena"
in the vessel trips. I discover for example that:

- vessels might have been unoptimally loaded on some trips
- speed has not been constant, even when it should be a "best practice" according to literature
- messy data might have been gathered without paying too much attention to DOE (https://en.wikipedia.org/wiki/Design_of_experiments)
