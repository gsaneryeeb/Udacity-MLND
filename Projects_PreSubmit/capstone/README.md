# Store Sales Forecast
## I. Definition
### Project Overview
Sales forecast is an integral part of JD.com's credit evaluation for small business loan. Accurate sales prediction translates into loan efficiency, improving capital utilization. 

### Background
JD Finance's supply chain finance has over 100,000 enterprise clients, providing USD 250 billion of loans in total with focus on serving SMEs. Supply chain finance is an industry supply chain based financial activities, its purpose is through the industrial supply chain to provide support for financial activities. In the past few years, it launched products like Jing Bao Bei, Jing Xiao Dai, and Dong Chan Rong Zi based on JD's big data. Among them, Jing Xiao Dai is a credit-based financial product, with high degree of loan autonomy, zero collateral, instant grants, low-cost financing, no payback terms, and online approval procedure.
Enterprises can log into the JD financial platform using store accounts for details on loan qualifications and application. Once successful, loans will be put into the store account, seamlessly connecting the payment procedure with JD. To make fintech even more beneficial, JD supply chain finance incorporates emerging companies with traditional companies, providing embedded service and technical support for online and offline risk control. 

### Details
Measuring and tracking store loan is the key to forecasting store sales. Through forecasting sales, we could better assess the financing needs and loan amount for each shop. This task requires the team to establish a forecasting model base on the simulated data of sales records, merchandise information, product evaluation, and advertising costs of the stores provided by the contest to predict the sales of the stores in the coming 90 days.
Datasets are simulated data based on real business scenario. All the data are sampled and desensitized. Field values and distributions are different from the real business data. 

### Metrics

For each shop, to estimate the difference between the real sale revenue and predicted revenue, scores will be calculated based on the following formula: yi is the real value, y_hati is the predicted value, and m represents the total number of shops to be evaluated.

![WMAE](https://raw.githubusercontent.com/gsaneryeeb/Udacity-MLND/master/Projects_PreSubmit/capstone/sample_score.png)


