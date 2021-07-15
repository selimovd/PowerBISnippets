# Commonly used Power BI / DAX and Power Query / M snippets
As the amount of code snippets got a little bit messy, I decided to put all of the commonly used and referred code snippets together in a repository on GitHub.
I differentiate between the Power BI or DAX measures and the Power Query or M snippets. For that reason I created two separate folders.
The following table will give an overview over the provided examples

## Power BI / DAX measures
| DAX-Snippet | Description |
|--|--|
| [Correct column YYYY/MM for ISO format](https://github.com/selimovd/PowerBISnippets/blob/main/PowerBI_DAX/Correct%20column%20YYYY%20MM%20for%20change%20of%20year%20and%20ISO%20format.txt)  | When you use the ISO format the combination of YYYY/MM is wrong at the end of the year. For example for the first week of 2021 the result would be "2021/53" instead of "2020/53". This snippet is correcting this error |
| [DateTable with date column in fact table](https://github.com/selimovd/PowerBISnippets/blob/main/PowerBI_DAX/DateTable%20with%20date%20column%20in%20fact%20table.txt) | Snippet to create a correct date table based on the date range in a fact table. |
| [DateTable with date ID in fact table](https://github.com/selimovd/PowerBISnippets/blob/main/PowerBI_DAX/DateTable%20with%20date%20ID%20column%20in%20fact%20table.txt) | Snippet to create a correct date table based on the date range in a fact table when the fact table only contains date IDs (e.g. 20201030). |
| [ISO calender week](https://github.com/selimovd/PowerBISnippets/blob/main/PowerBI_DAX/ISO%20calendar%20week.txt) | DAX snippet to create the correct ISO week as calculated column |



## Power Query / M snippets

| M-Snippet | Description |
|--|--|
| [DateID from Date](https://github.com/selimovd/PowerBISnippets/blob/main/PowerQuery_M/Creat%20DateID%20column%20from%20Date.txt)  | Create the date ID in the format YYYYMMDD from a date column |
| [Date from UNIX-Timestamp](https://github.com/selimovd/PowerBISnippets/blob/main/PowerQuery_M/Create%20date%20from%20UNIX%20timestamp.txt) | If you get the date as UNIX-timestamp and you want to create a proper date from it |
| [ISO-Week from date](https://github.com/selimovd/PowerBISnippets/blob/main/PowerBI_DAX/DateTable%20with%20date%20ID%20column%20in%20fact%20table.txt) | Function to get the ISO week from a column in DATE format |
| [Time table with buckets](https://github.com/selimovd/PowerBISnippets/blob/main/PowerQuery_M/Time%20table%20with%20buckets%20in%20M.txt) | The easiest way to create a time table is in M. Just use this snippet to create an universal time table with buckets for 5, 15 and 30 minutes |
