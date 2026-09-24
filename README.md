# KCPC-bot

- Linking discord accounts with all major competitive programming websites.
```Text
Command Set:
  /link codeforces <handle>
  /link atcoder <handle>
  /profile
  /rank
  /handle
```

- Sourcing random competitive programming problems + their solutions.
- - Problem (week 1) - Friday 
- - Solution (week 2) - Friday
```Text
Command Set:
  /randproblem <topic> <difficulty>
```
```Text
Storage:
  problem_id
  date_selected
  topic
  difficulty
  source
  solution_posted
```

- Contest live tracking.
```Text
Contest List:
  Codeforces Round
  AtCoder Contest
  ICPC-related contests
```

- Automated workshop pinging (24 hours before a workshop is to be hosted, and then 1 hour before the hosting) - data ingestion from luma with live tracking updating.
- - Do not repeat event pings.
```Text
Command Set:
  /event next
  /event this-week
```

```Text
Storage: 
  event_id
  luma_id
  name
  start_time
  end_time
  url
  last_synced
```

[OPTIONAL FEATURE SET]
- Random monthly data structure / algorithm selection
- - Link to i.e. GeeksForGeeks
