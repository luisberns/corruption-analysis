# Corruption analysis
Today is possible for us to readily and constantly check information online, over the years more and more people got access to mobile devices and this medium became the main for information exchange and gathering. We can imagine how this can influency society, but we're not going to study how people are interacting or being influenced, we're going to analyze the relations between CPI score of the country, the Number of Internet Users, and the Number of Journalists Killed.

## About the data

We used three datasets*:
- Corruption Perception Index (CPI)
- Number Of Internet Users (# people with internet access)
- Number Of Journalists Killed

**All the datasets were downloaded from [Gap Minder](https://www.gapminder.org)*

We're considering the years from **2012** to **2016** and only countries that had journalists killed during that period.

### Corruption Perception Index (CPI)
[Transparency International, CPI 2018](https://www.transparency.org/cpi2018)

More about the index (YouTube Video):

[![CPI 2018](https://i.ytimg.com/vi/OXApeTYRYNQ/hqdefault.jpg?sqp=-oaymwEZCPYBEIoBSFXyq4qpAwsIARUAAIhCGAFwAQ==&rs=AOn4CLCNIW09Vs8woiyo5Y824JeMQarslQ)](https://www.youtube.com/watch?v=OXApeTYRYNQ)

## Running the scripts
The analysis was made in a Jupyter Notebook, so the best way to run the scripts is clonning the repository and running a [Jupyter Notebook](https://jupyter.org/).

Clone the repo.
```Shell
$ git clone [git-repository]
```

Start Jupyter.
```Shell
$ jupyter-notebook
#  or
$ jupyter lab # I personally preffer this one
```

Also, I'm using and recomend [Conda](https://www.anaconda.com/distribution/) to manage any packages and modules needed. With Conda its easy to create different environments and manage Python modules for your project.
