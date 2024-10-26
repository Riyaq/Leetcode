# Query 1
[511. Game Play Analysis](https://leetcode.com/problems/game-play-analysis-i/description/)

```sql
select player_id, min(event_date) as first_login
from Activity 
group by player_id
```
