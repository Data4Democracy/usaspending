# D4D - USA Spending

This repository is for collaborating on exploring data from [USASpending.gov](https://www.usaspending.gov/#/). The instructions in this README should provide you with some help in getting started working on this project. This is a living document. Feel free to clone the repo locally, make edits, and commit your changes as you learn to help others when they get started. 

## Overview
Currently we won't have any goals for this project. If anyone has idea for things they would like to look into please suggest them in the slack channel. If you're just diving into the data for the first time I would think the main goal is to learn and explore the data for yourself. Look into things that you find interesting, come up with your own questions, and try to answer them. Feel free to store your code in this repo for others to reproduce. 

## Repository Structure
For a first attempt at structuring our workflow I have creating two main directories depending on your programming language of choice. If neither of these are your primary languages, feel free to add a directory for those. 

1. python - any python code should be placed in this directory
2. R - any R code should be placed in this directory

Each of the main directories (python and R) have the same set of subdirectories each with their own purpose. 

* data - place any (small) data sets that you use in here; this should contain only data that you use and not any data that comes out of some code or is otherwise processed
* doc - contains any documentation
* figs - contains any figures generated
* output - contains data output from code, processed data sets, logs, or other processed things
* python/R - contains various functions either written in python or R

This is a structure I use at work that I learned from [here](https://nicercode.github.io/blog/2013-04-05-projects/) and it has benefitted me. It might not be ideal for collaboration so if anyone has any better ideas feel free to suggest them in the slack channel. 

## Getting the Data

If you want to get started and just dive into the data the easiest way is doing a bulk download [here](https://www.usaspending.gov/#/download_center/award_data_archive). You can also do a custom award download to answer more targeted questions [here](https://www.usaspending.gov/#/download_center/custom_award_data). There is a [USASpending API](https://api.usaspending.gov/) which could be useful to explore. Finally, Amazon AWS hosts entire database snapshots [here](https://registry.opendata.aws/usaspending/). You can read a tutorial about connecting to the AWS snapshot [here](https://aws.amazon.com/blogs/aws/new-usaspending-gov-on-an-amazon-rds-snapshot/). 

## Questions

I'd encourage you all to just explore the data yourself, but it can be challenging if you're not familiar with the data. [USASpending](https://www.usaspending.gov/#/) provides a glossary of terms on their website for you to learn more. They also have a [Data Lab](https://datalab.usaspending.gov/) which can help you get started in your analysis and start coming up with some questions. They also have a [community page](https://usaspending-help.zendesk.com/hc/en-us/community/topics) which you can join and ask questions about the data, provide feedback on their site, or just discuss general things. 

All of this data comes from the [Federal Procurement Data System](https://www.fpds.gov/fpdsng_cms/index.php/en/) (FPDS). [Here](https://www.fpds.gov/downloads/Version_1.4_specs/FPDSNG_DataDictionary_V1.4.pdf) is a link to FPDS's data dictionary, but beware that it can be dense and hard to follow. 


## Contributing

If you'd like to contribute you can clone this repo locally, make changes as desired, and commit back to the repo. 