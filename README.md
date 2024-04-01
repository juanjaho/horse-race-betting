<br />
<div align="center">
  <h2 align="center">Improving Horse Race Betting using Machine Learning</h2>
</div>

### Results

- Using a single-bet betting strategy where we only bet the horse with the highest probability of winning in a race, we are able to make substantial profits
- Overall, all models are able to predict the winner of a race more than 50% of the time
  - Average Race Speed Regressors: 57.3% accuracy (Highest Cum Returns)
  - Finish Time Regressors: 55.1% accuracy
  - Finishing Position Classifiers: 53.9% accuracy

### Using a Flat Betting Strategy

<img src="chart/result/fb_race_speed_result.png">

> Cumulative returns using an ensemble of regressors to predict the average race speed of a horse

<img src="chart/result/fb_finish_time_result.png">

> Cumulative returns using an ensemble of regressors to predict the finish time of a horse

<img src="chart/result/fb_finish_position_result.png">

> Cumulative returns using an ensemble of classifiers to predict the finishing position of a horse

### Using Kelly Criterion to allocate bet amounts

<img src="chart/result/kc_race_speed_result.png">

> Cumulative returns using an ensemble of regressors to predict the average race speed of a horse

<img src="chart/result/kc_finish_time_result.png">

> Cumulative returns using an ensemble of regressors to predict the finish time of a horse

<img src="chart/result/kc_finish_position_result.png">

> Cumulative returns using an ensemble of classifiers to predict the finishing position of a horse

## Project Report and Presentation

- [QF206 Project Report](./QF206%20G1T3%20-%20Report.pdf)
- [QF206 Project Presentation](./QF206%20G1T3%20-%20Slides.pdf)
