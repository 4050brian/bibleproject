# bibleproject
About
Some years ago, I started working on getting all Bible versions (and ultimately all languages) in a SQL database, simply to assist developers of Bible study software. Since then, technology have rapidly developed, and it became quite easy to use this in Excel and other spreadsheet software.
What started as a personal Bible software solution (mainly in php with mySQL and asp.net with MS SQL) proofed quite a challenge especially when adding search, reporting etc. functionality. The Bible project have grown to such an extent that I decided to use the full Business Intelligence methodologies and tools to add such a huge volume of data from so many different sources, place it into a Data Lake and Data Warehouse with analytical tools.
Using Power BI as a BI specialist I only recently I started to see the unbelievable advantages of using Power BI to gain insight into this volume of data. These reports are mainly as a starting point for further development. As a starting point I separated the Bible (King James Version) into Old and New testament.  Using this I am currently working on adding extended mapping for visually presenting a historical picture and utilizing the Q&A capabilities for study and research.
Source data is available on https://github.com/4050brian and supporting videos on how I developed these reports will be on https://www.youtube.com/channel/UC02DbzMnvJ8GtcduPmBBJVw

The Process
The process I followed to get to the stage where we can start building insightful reports. 
Step1.	Source the original electronic text. This where mainly created by the original publishers of the various Bible version publishers. we then had to ensure that the necessary permissions where in place to use these text files. At this stage we have around 12 Bible versions in around 20 languages. 

Step 2.	For software development it were of little use to have the hole Bible in one huge text file so we created meaningful tables in in SQL database structure. The original text files were transformed to mainly csv format which made it easier to import Bible books into separate tables and using SQL normalization etc. to either combine or use separately.

Both steps are ongoing project as one of our goals is to have all Bible versions and ultimately all languages in a central database. However, each Bible version in each language should be available separately. Bible software developers will normally only be interested in one or the other version.
