# lane_change_simulator_in_highway
This repository aims to try different methods in lane change scenario.

high_env_simulator
run script with rule-based window selection.
python model_test.py --type rule-based

The yellow window is the target window with the minimum chasing window time.




run script with data-driven window selection.
python model_test.py --type data-driven


The yellow window is the target window with the highest window confidence and blue windows are all feasible lane change window. (The train dataset comes from rule-based window selection simulations.)
