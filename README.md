# Quantitative-Economics
This is where I’m keeping the Python projects I’ve built during my first year at St. Xavier's College, Kolkata. I started learning Python in January 2026 to see how the macro models I was learning in class would actually behave in a simulation.

Everything here is built using NumPy and Matplotlib.

Projects
Macroeconomic Shock Simulator
A 120-month simulation of an economy to see how it reacts to a sudden interest rate hike.

The Logic: I set the Marginal Propensity to Consume (MPC) at 0.8. At Month 60, I bumped interest rates from 3% to 8%.

The Result: I watched the "multiplier effect" turn a $50 drop in investment into a $250 crash in total GDP.

The Reality Check: I added Gaussian noise and a "Black Swan" event (a 10% sudden hit to GDP at Month 45) so it looked like a real economy instead of a straight line.

Trading Strategy Backtester
A script to test a Mean-Reversion strategy (buying when a price drifts too low and selling when it's high).

The Strategy: It uses vectorized logic to find trading signals and includes a hard 2% stop-loss rule.

The Lesson: It was a reality check on "Alpha." It’s a lot easier to read about trading than it is to actually beat a random market.
