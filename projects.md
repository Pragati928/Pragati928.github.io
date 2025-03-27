<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projects | Pragati's Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .project-card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .project-card:hover {
            transform: translateY(-5px);
        }
        .project-image {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 8px;
        }
        .project-title {
            font-size: 20px;
            font-weight: bold;
            margin-top: 10px;
        }
        .tech-used {
            font-style: italic;
            color: #777;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🚀 Featured Projects</h1>
        <div class="projects-grid">
            <div class="project-card">
                <img src="images/real_estate.png" alt="Real Estate Analytics" class="project-image">
                <div class="project-title">🏠 Integrated Real Estate Solution</div>
                <div class="tech-used">Tech Used: Python, Power BI, SQL</div>
                <p>Developed a full-cycle real estate analytics project to enhance decision-making.</p>
            </div>
            <div class="project-card">
                <img src="images/insurance.png" alt="Health Insurance Analysis" class="project-image">
                <div class="project-title">📊 Analysis of Indian Health Insurance Data</div>
                <div class="tech-used">Tech Used: Python, SQL, Tableau</div>
                <p>Analyzed and visualized health insurance trends, identifying a 2.5x increase in insured individuals.</p>
            </div>
            <div class="project-card">
                <img src="images/customer_churn.png" alt="Customer Churn" class="project-image">
                <div class="project-title">📞 Customer Churn Prediction</div>
                <div class="tech-used">Tech Used: Python, Machine Learning, Power BI</div>
                <p>Built a predictive model to analyze customer churn in a telecom company, achieving 85% accuracy.</p>
            </div>
            <div class="project-card">
                <img src="images/sales_forecast.png" alt="Sales Forecasting" class="project-image">
                <div class="project-title">📈 Sales Forecasting Using Time Series Analysis</div>
                <div class="tech-used">Tech Used: Python, SQL, Power BI</div>
                <p>Forecasted future sales for a retail company using ARIMA & Prophet models, improving sales planning.</p>
            </div>
        </div>
    </div>
</body>
</html>
