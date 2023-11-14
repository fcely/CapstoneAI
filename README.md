# CapstoneAI
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project Title: Retail Flower Sales Forecasting</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        h1 {
            color: #333;
        }

        h2 {
            color: #555;
        }

        p, li {
            color: #777;
        }
    </style>
</head>

<body>

    <h1>Project Title: Retail Flower Sales Forecasting</h1>

    <p><strong>Author:</strong> Fernando Cely</p>

    <hr>

    <h2>Executive Summary</h2>
    <p>This project focuses on predicting flower sales at a retailer to minimize waste and enhance profitability through improved sales forecasts.</p>
    <h3> Please note Keys and passwords were removed before pusblishing to Git, As some of the APIs are paid and the sales info is confidential, replace with your own </h3>

    <hr>

    <h2>Rationale</h2>
    <p>This initiative aims to enhance sales predictions by employing time series analysis and integrating exogenous variables such as fuel prices, weather conditions, truck occupation, and GDP.</p>

    <hr>

    <h2>Research Question</h2>
    <p>How can we refine sales predictions by incorporating time series analysis and leveraging exogenous variables like fuel prices, weather, truck occupation, and GDP?</p>

    <hr>

    <h2>Data Sources</h2>
    <ul>
        <li>Historical Sales: Sales data categorized by store and product for 188 stores.</li>
        <li>Fuel Prices: Obtained through an API, categorized by region.</li>
        <li>Weather Data: Fetched via an API, focusing on Seattle in this instance.</li>
        <li>Pending Sources: Yet to acquire GDP data and truck occupation indicators for a comprehensive economic outlook.</li>
    </ul>

    <hr>

    <h2>Methodology</h2>
    <p>The chosen methodology for the forecasting model is SARIMAX. Given the highly seasonal nature of flower sales influenced by yearly cycles and key holidays, SARIMAX is preferred, especially when integrating exogenous factors.</p>

    <hr>

    <h2>Results</h2>
    <p>The forecast model is a work in progress, with ongoing efforts to enhance accuracy, identify optimal hyperparameters, and complete the list of exogenous variables. The goal is to finalize these improvements in the next deliverable.</p>

    <hr>

    <h2>Next Steps</h2>
    <ol>
        <li>Extend Testing: Implement the model across multiple stores for a more comprehensive assessment.</li>
        <li>Aggregate Sales Data: Consider combining historical sales data from all stores and use the collective forecast as an additional exogenous variable to account for regional trends.</li>
        <li>Complete Exogenous Variables: Acquire remaining exogenous variables through APIs for a fully automated model.</li>
        <li>Database Integration: Develop a mechanism to submit results to an SQL database, facilitating easy access and utilization by the company.</li>
    </ol>

    <hr>

    <h2>Outline of Project</h2>
    <ul>
        <li><a href="#">Link to Notebook 1</a></li>
        <li><a href="#">Link to Notebook 2</a></li>
        <li><a href="#">Link to Notebook 3</a></li>
    </ul>

    <hr>

    <h2>Contact and Further Information</h2>
    <p>For inquiries or additional information, please contact Fernando Cely at <a href="mailto:your@email.com">your@email.com</a>.</p>

</body>

</html>
