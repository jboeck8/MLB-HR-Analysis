# MLB Home Run Power Analysis — 2024 Season
**Tools:** Python, pandas, matplotlib  
**Data:** Baseball Savant Leaderboards via Kaggle

## Question
What hitting metrics best predict home run power in MLB?

## Data Sources
Three Baseball Savant leaderboards were merged on player ID and season year:
- Bat Tracking (bat speed, attack angle)
- Home Runs (HR total, no-doubter %)
- Batted Ball (fly ball rate, pull rate)

## Key Findings
- **Bat speed is the strongest predictor of home runs** (r = 0.43). Players with above-median bat speed averaged 19.6 HRs vs 11.9 for below-median — a 65% difference.
- **Fly ball rate is nearly as important** (r = 0.40). Getting the ball airborne consistently matters almost as much as raw bat speed.
- **Attack angle is weaker than expected** (r = 0.28), suggesting the "launch angle revolution" narrative may be overstated at the individual level.
- **No-doubter % showed the weakest correlation** (r = 0.23), indicating that pure raw power without consistent contact doesn't translate to HR volume.

## Conclusion
Home run production is best explained by a combination of bat speed and fly ball tendency rather than any single metric. Aaron Judge (61 HR, 77.1 mph avg bat speed) and Kyle Schwarber (39 HR, 77.5 mph) exemplify this combination at the top of the leaderboard.
