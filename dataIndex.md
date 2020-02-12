# Blue Ripple Data Index

## Description
The table below contains links to all the data we use in our research pieces at [Blue Ripple Politics](https://www.blueripplepolitics.org).
As we publish new pieces, we'll add relevant data here.

- Some data we use exactly as is from a provider.  In that case we link our local copy in column 1 of the table and the provider page in column 2.
- Other data we pull using an API.  In that case we link our local version in column 1 and to an API reference or data source description in column 2.
- Some data we combine or simplify for analysis.  In those cases we will link the data-set we use in column 1 and the source in column 2.
- Finally, some data is too large to store a local copy on github.  In that case, we don't link to the outside data-set in column 1 and do link to the provider in column 2.

In all cases, the link in column 1 should be to a file or page containing 
a file which is *exactly* the one we are using in our analyis. 
When possible we keep the data in github so that there is a versioned history if the file changes.

| Data Set                                          | Source                 | Comment/Description                        |
| ------------------------------------------------- | ---------------------- | -----------------------------------------  |
| [House Election Results (1976-2018), version 5.0](https://github.com/blueripple/data-sets/blob/master/data/election/1976-2018-house_v5.csv)   | [MIT Election Lab](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/IG0UN2&version=5.0) | U.S. House election results from 1976 through 2018 (NB: The local version is edited to remove unparseable characters and change some "NA" to "FALSE" in the "runoff" field.)                           |
| [Presidential Election Results (1976-2016)](https://github.com/blueripple/data-sets/blob/master/data/election/1976-2016-president.csv)  |[MIT Election Lab](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/42MVDX) | US Presidential Election results by State. Edited to remove spurious quotes                              |
| [Voter Turnout By State](https://github.com/blueripple/data-sets/blob/master/data/election/StateTurnout.csv) | [United States Election Project](http://www.electproject.org/home/voter-turnout/voter-turnout-data) | Counts of total votes cast, votes for highest office, voting-eligible-population, voting-age-population, etc. Local version is combined USEP data from 2010 to 2018.| 
| [Voter Turnout by Age, Sex and Education](https://github.com/blueripple/data-sets/blob/master/data/election/DetailedTurnoutByAgeSexEducation2010-2018.csv) | [US Census Voter Turnout Data](https://www.census.gov/topics/public-sector/voting/data/tables.2018.html)| Combined census voter turnout broken down by Age, Sex and Education for 2010-2018.  Local version is hand copy/pasted from various spreadsheets published by the Census Bureau. |
| [Voter Turnout by Age, Sex and Race](https://github.com/blueripple/data-sets/blob/master/data/election/DetailedTurnoutByAgeSexRace2010-2018.csv) | [US Census Voter Turnout Data](https://www.census.gov/topics/public-sector/voting/data/tables.2018.html)| Combined census voter turnout broken down by Age, Sex and Race for 2010-2018. Local version is hand copy/pasted from various spreadsheets published by the Census Bureau. |
| [Congressional District Demographics by Age, Sex and Education](https://github.com/blueripple/data-sets/blob/master/data/demographic/ageSexEducationDemographics2010-2017.csv) | [US Census ACS Data](https://www.census.gov/programs-surveys/acs)| Demographic Data from the Census American Communnity Survey (ACS). Local version is pulled and aggregated using the [census ACS API](https://www.census.gov/data/developers/data-sets/acs-1year.html) via code in the [census-tools](https://github.com/blueripple/census-tools) repo. |
| [Congressional District Demographics by Age, Sex and Race](https://github.com/blueripple/data-sets/blob/master/data/demographic/ageSexRaceDemographics2010-2017.csv) | [US Census ACS Data](https://www.census.gov/programs-surveys/acs)| Demographic Data from the Census American Communnity Survey (ACS).  Local version is pulled and aggregated using the [census ACS API](https://www.census.gov/data/developers/data-sets/acs-1year.html) via code in the [census-tools](https://github.com/blueripple/census-tools) repo. |
| [2018 Edison Exit Poll Breakdown](https://github.com/blueripple/data-sets/blob/master/data/election/EdisonExitPoll2018.csv) | [Fox News Analysis](https://www.foxnews.com/midterms-2018/voter-analysis) | Exit Poll breakdowns by various demographic categories.  Local version is aggregated from various tables on the Fox News page. |

