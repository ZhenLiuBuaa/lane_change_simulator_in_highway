# lane_change_simulator_in_highway
This repository aims to try different methods in lane change scenario.

high_env_simulator
run script with rule-based window selection.
python model_test.py --type rule-based

The yellow window is the target window with the minimum chasing window time.

![1](https://user-images.githubusercontent.com/45850504/112853528-86e20c00-90df-11eb-9c72-20a9d252b9aa.gif)
![2](https://user-images.githubusercontent.com/45850504/112853547-8a759300-90df-11eb-88df-747e4b6f60c9.gif)



run script with data-driven window selection.
python model_test.py --type data-driven
![3](https://user-images.githubusercontent.com/45850504/112853549-8ba6c000-90df-11eb-8a0b-bae5041b86ea.gif)


The yellow window is the target window with the highest window confidence and blue windows are all feasible lane change window. (The train dataset comes from rule-based window selection simulations.)
