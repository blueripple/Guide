## [Blue Ripple Politics](https://blueripplepolitics.org/) 

### Introduction
We are progressive citizens who are despondent and 
angry---but determined to help make America bluer,
support voting rights, and end gerrymandering.

How? By helping you make informed choices about how to 
support important candidates and ballot initiatives with your time and money.

Our plan is to produce and disseminate independent writing and analysis 
(1-2 emails per month; maybe a few more right before an election — we promise we won’t spam you!). 
We aim to:

- Help progressives identify key local, state, and national races 
where our donations of effort or money could have an outsized impact;
- Identify races and ballot initiatives to support that will enable 
voter turnout and enfranchisement, and counter voter suppression and gerrymandering; and,
- Collect and broadly disseminate data, tools,
and resources to support “open source” election data analysis and modeling by progressives.

Please [visit](https://blueripplepolitics.org/) us on the web,
like our [FB page](https://www.facebook.com/blueripplepolitics),
follow [@blueripplepol](https://twitter.com/BlueRipplePol) on twitter,
and [join](http://eepurl.com/gzmeQ5) our mailing list!

### Open Code and Data
We plan to make all of our code, and, to the extent possible, 
whatever [data](https://github.com/blueripple/Guide/blob/master/dataIndex.md) 
we use, available here
so that other people can re-use any and all of it.  We hope some of our consolidations
of existing data, etc. will be helpful.  The code will also be here--or open-sourced
elsewhere with links from here--so that our methods and approach are clear and open
to criticism and refinement.

Some publicly available data that we wish to analyze may be too big to host here. In 
those cases we will note that fact in any post using that data and make sure to provide links,
both in the post itself and in our 
[data index](https://github.com/blueripple/Guide/blob/master/dataIndex.md).

### Code of Conduct
Our code-of-conduct, based on the 
[Contributor Covenant](https://www.contributor-covenant.org/), is 
[here](https://github.com/blueripple/Guide/blob/master/CODE_OF_CONDUCT.md)
and applies to all communications and contributions to Blue Ripple Politics.

### Data-Science and Ethics
We are mindful that data-science brings with it ethical concerns and pitfalls.  As 
a general rule, we will follow the principles laid out in 
[this post](https://datascience.columbia.edu/ethical-principles-okrs-and-kpis-what-youtube-and-facebook-could-learn-tukey)
by Columbia professor Chris Wiggins. Those are targeted at corporate data use and not
perfectly applicable. Of particular importance to our work which will use
entirely data already made public, is the principle of "transparency in methods and results." 

### Join The Effort!
- We're happy if you make use of our data, code or ideas! Please let us
know (via an [issue](https://github.com/blueripple/Guide/issues) 
in this repo) 
if you do so we can help and so we know what is useful to others.
- Keep us accountable!  Feel free to raise 
[issues](https://github.com/blueripple/Guide/issues) here,
or in specific repos, to discuss the details
of the data or the algorithms used to analyze them.
- We're also always interested in comments on posts or analyses we've done
and ideas for new ones.  Feel free to raise those as 
[issues](https://github.com/blueripple/Guide/issues) here, contact 
us via email 
(adam@blueripplepolitics.org or frank@blueripplepolitics.org) or 
[@BlueRipplePol](https://twitter.com/BlueRipplePol) on twitter.

### Repo Guide
- [Guide](https://github.com/blueripple/Guide): 
This Repo, just a readme with introduction and summaries of the other repos
- [data-sets](https://github.com/blueripple/data-sets)
Contains any data-set we use which can be hosted on github.  Also a small Haskell
wrapper for using Frames as a data-set container for these data-sets.
- [blueripple.github.io](https://github.com/blueripple/blueripple.github.io): 
repo purely for hosting html. Research posts and technical addenda are here.
- [blueripple-research](https://github.com/blueripple/blueripple-research):
Code for doing demographic voter-preference inference from 
congressional district demographics, turnout data and election results.
Also contains bits of other research projects, soon to be split into 
their own repos.
- [FEC](https://github.com/blueripple/FEC): 
A set of (Haskell) tools for querying the OpenFEC api for Federal
Election Commission data.  This has been used mainly to query spending data
in 2018 house races.  The resulting data is in the 
BlueRipple [data](https://github.com/blueripple/BlueRipple/tree/master/data)
directory in files beginning with "allSpending".
- [census-tools](https://github.com/blueripple/census-tools): A set of (Haskell)
tools for querying the census American Community Survey (ACS) api.  Used for
pulling ACS data into CSV files for use by the Blue Ripple Politics national
voter preference model. 

