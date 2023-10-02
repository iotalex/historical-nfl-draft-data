# historical-nfl-draft-data

A place to store data about historical NFL draft classes

The lion's share of the credit for this data goes to [Pro Football Reference Draft History](https://www.pro-football-reference.com/draft/), though I've made some formatting changes as well as included some information from [nflverse](https://github.com/nflverse/nfldata)


The current method of compiling this data uses a [Microsoft polyglot notebook](https://devblogs.microsoft.com/dotnet/announcing-polyglot-notebooks-harness-the-power-of-multilanguage-notebooks-in-visual-studio-code/). Most of the work is being done with [Microsoft.Data.Analysis](https://www.nuget.org/packages/Microsoft.Data.Analysis/) using the Microsoft version of a [DataFrame](https://devblogs.microsoft.com/dotnet/an-introduction-to-dataframe/).


There is some old information in an old-data folder. In there, the SchoolNameCleaning.json file contains instructions for cleaning and converting the PFR CSV files using OpenRefine. There is also a text file with a csvkit command that can be used to join data.