# Hadoop MapReduce example in Python using Hadoop Streamimg
A simple Hadoop MapReduce example to demonstrate *mapper* and *reducer* functions written in python. The course can be found at [Udacity: Intro to Hadoop and MapReduce](https://www.udacity.com/course/intro-to-hadoop-and-mapreduce--ud617)

## Download Data
Use following script to download the test data.

```./download_data.sh```


## Input Data

Each mapper will process the input data and process the lines given to it. First ten lines of the input file using command `head data/purchases.txt` Each line have 6 values separated with `\t`:

```
2012-01-01	09:00	San Jose	Men's Clothing	214.05	Amex
2012-01-01	09:00	Fort Worth	Women's Clothing	153.57	Visa
2012-01-01	09:00	San Diego	Music	66.08	Cash
2012-01-01	09:00	Pittsburgh	Pet Supplies	493.51	Discover
2012-01-01	09:00	Omaha	Children's Clothing	235.63	MasterCard
2012-01-01	09:00	Stockton	Men's Clothing	247.18	MasterCard
2012-01-01	09:00	Austin	Cameras	379.6	Visa
2012-01-01	09:00	New York	Consumer Electronics	296.8	Cash
2012-01-01	09:00	Corpus Christi	Toys	25.38	Discover
2012-01-01	09:00	Fort Worth	Toys	213.88	Visa

```
 
