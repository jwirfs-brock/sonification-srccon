# sonification-srccon
Materials and Resources for the "Data Audioization/Sonification" session at SRCCON 2015.

## Dataset 1
This dataset, from Popup Archive, contains the weekly number of mentions of people in podcasts starting at beginning of 2015.

The datafile is called popupArchiveData.csv.

The file has the following structure:

Variable | Definition
---|---------
`name` | The person's first and last name
`mentions` | The number of mentions in a given week
`week` | The week, in format YYYY-MM-DD (i.e. 2015-03-29)

The data was compiled by Shindo Strzelczyk of [Popup Archive](https://www.popuparchive.com/).

## Dataset 2
This data is from FiveThirtyEight, and was originally published in [their GitHub repo](https://github.com/fivethirtyeight/data/tree/master/comic-characters) and used for Walt Hickey's article, ["Comic Books Are Still Made By Men, For Men And About Men."](http://fivethirtyeight.com/features/women-in-comic-books/) 

The original data set was published under a [Creative Commons Attribution 4.0 License](http://creativecommons.org/licenses/by/4.0/).

Here are the data notes from FiveThirtyEight:

The raw data behind the story [Comic Books Are Still Made By Men, For Men And About Men](http://fivethirtyeight.com/features/women-in-comic-books/). 

The data comes from [Marvel Wikia](http://marvel.wikia.com/Main_Page) and [DC Wikia](http://dc.wikia.com/wiki/Main_Page). Characters were scraped on August 24. Appearance counts were scraped on September 2. The month and year of the first issue each character appeared in was pulled on October 6.

The data is split into two files, for DC and Marvel, respectively: `dc-wikia-data.csv` and `marvel-wikia-data.csv`. Each file has the following variables:

Variable | Definition
---|---------
`page_id` | The unique identifier for that characters page within the wikia
`name` | The name of the character
`urlslug` | The unique url within the wikia that takes you to the character
`ID` | The identity status of the character (Secret Identity, Public identity, [on marvel only: No Dual Identity])
`ALIGN` | If the character is Good, Bad or Neutral
`EYE` | Eye color of the character
`HAIR` | Hair color of the character
`SEX` | Sex of the character (e.g. Male, Female, etc.)
`GSM` | If the character is a gender or sexual minority (e.g. Homosexual characters, bisexual characters)
`ALIVE` | If the character is alive or deceased
`APPEARANCES` | The number of appareances of the character in comic books (as of Sep. 2, 2014. Number will become increasingly out of date as time goes on.)
`FIRST APPEARANCE` | The month and year of the character's first appearance in a comic book, if available
`YEAR` | The year of the character's first appearance in a comic book, if available
