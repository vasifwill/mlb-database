# MLB Database

## Instructions
In the initial commit to this project you have been provided with data about the stats accumulated by MLB players on a single day of games. You are tasked with creating an Entity Relationship Diagram in [Lucidchart](https://www.lucidchart.com/) to represent a normalized database design for storing this data. When you have completed your chart create a PNG image of it (File -> Export -> PNG) and save it to your repo.

### Notes on Data
* Players are broken into two categories: pitchers and hitters
  * A pitcher is any player with a position of SP or RP
  * A hitter is any player that is not a pitcher
* Pitchers do not accumulate hitting stats and hitters do not accumulate pitching stats
* Throws and Bats refer to the handedness of the player. R means right handed, L means left handed and B means the player can use either hand
* Players can move between teams many times during their career and can have more than one stint with a given team (ex. a player can start in BOS, get traded to SEA, move to HOU, and then get traded back to BOS)
* An inning consists of three outs. For a pitcher, each out is 0.1 for their Innings Pitched number with three outs being a full inning 1.0. Therefore a picther with an Innings Pitched stat of 3.2 pitched in the game for 11 outs.
* There are only two leagues: AL and NL
* Each league has three divisions: East, Central, West
* A team belongs to a single division within a single league
* The following are considered hitting stats: At Bats, Runs, Hits, Doubles, Triples, Home Runs, Runs Batted In, Walks, StrikeOuts, Steals
* The following are considered pitching stats: Wins, Innings Pitched, Hits (Pitcher), Runs (Pitcher), Earned Runs, Walks (Pitcher), Strike Outs (Pitcher)
