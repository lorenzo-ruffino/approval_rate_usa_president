# U.S. Presidential Approval Ratings (1937-2024)

This repository contains historical data on U.S. presidential approval ratings from 1937 to 2024.

## Dataset Description

### historical_approval_polls.csv

This file contains individual approval polls from 1937 to 2024 with the following information:

- `president_number`: Sequential number identifying each president
- `president`: Name of the president
- `term_number`: Number of the presidential term
- `term_start`: Start date of the presidential term
- `term_end`: End date of the presidential term
- `polling_institute`: Name of the polling organization that conducted the survey
- `poll_start`: Start date of the polling period
- `poll_end`: End date of the polling period
- `sample_size`: Number of respondents in the poll
- `approval`: Percentage of respondents who approve of the president
- `disapproval`: Percentage of respondents who disapprove of the president
- `no_opinion`: Percentage of respondents with no opinion

### historical_net_approval_rate_first_term.csv

This file contains the daily average net approval rating in wide format, specifically for the first term only of each president. The net approval rating is calculated as the approval percentage minus the disapproval percentage.

Structure:
- `days`: Numeric column indicating the day number of the term (1-1460)
- The remaining 14 columns are named after U.S. presidents, with each containing that president's net approval rating for the corresponding day of their first term:
  - Barack Obama
  - Bill Clinton
  - Donald Trump
  - Dwight D. Eisenhower
  - George H.W. Bush
  - George W. Bush
  - Gerald Ford
  - Harry S. Truman
  - Jimmy Carter
  - Joe Biden
  - John F. Kennedy
  - Lyndon B. Johnson
  - Richard Nixon
  - Ronald Reagan
