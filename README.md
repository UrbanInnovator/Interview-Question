# Interview-Question
Basic Interview question involving nested data structures




 Depth Chart

In team sports (NFL, NBA, etc), teams maintain a "depth chart" per player position.
A depth chart contains a list of players per position, and the individual "rank" of each player,
where the lowest rank player is the preferred starting player. For example,
the NFL's Ben Rothenberger is the starting `QB` on the QB depth chart,
and his backup (Mason Rudolph) is listed as the 2nd person on that depth chart.

## Data Model
Assume player objects look like this. Note that players can be on the depth chart for positions that are not their own.

```
{
  "player_id": 1,
  "name": "Ben Rothenberger",
  "position": "QB"
}
```

1. Write a method to add a player to a depth chart for a given position (at a specific spot).
If no `position_depth` is provided, then add them to the end of the depth chart for that position.
If you are entering two players into the same slot, the last player entered gets priority and bumps the existing player down a depth spot.
 */

     
    Output:
    WR: ["alice", "bob", "charlie"],
    KR: ["bob"]
    
