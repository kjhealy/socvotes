# socvotes data

## Kieran Healy / @kjhealy

# About the data

Data from an informal pairwise-comparison survey conducted in 2013 on the AllOurIdeas platform. Participants were asked “In your judgment, which of the following is the better Sociology department?” followed by a choice between two departments. This subset of the data excludes votes where no choice was made. 

The `socvotes.csv` file has 46,317 rows each recoding a pairwise vote from one of 635 distinct respondents. There are seven columns in the file:

- `id` Unique respondent ID
- `vote_id` Unique vote ID
- `winner_id` Numerical ID of winning department
- `loser_id` Numerical ID of losing department
- `winner_text` Name of winning department
- `loser_text` Name of losing department
- `response_time_s` Time it took voter to cast vote, in seconds

See the following for more detail, and some analysis:

1. https://kieranhealy.org/blog/archives/2013/03/25/sociology-department-rankings-for-2013/

2. https://kieranhealy.org/blog/archives/2013/03/26/sociology-rankings-and-the-fabio-effect/
