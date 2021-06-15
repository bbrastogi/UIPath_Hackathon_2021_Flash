# Flash - Accelerate Your Performance Execution
This solution is developed in UIPath with integration of JMeter, Influx DB and Grafana. 

This solution automates the process of starting performance test execution in JMeter and also enables real-time monitoring of ongoing test. After the test is complete, the solution analyses the results and sends an email to the user, which contains Excel report and interactive chart.

# Prerequisites
1. JMeter must be installed as this solution takes the JMeter bin directory as input
2. This solution also takes JMeter script path (.jmx file) as input, If you don't have .jmx file please consider using jmx file for testing available under /resources folder

# Installation Steps
1. Install UIPath Studio
2. Open Main.xaml in UIPath Studio, goto Manage Packages and install dependences : 

    "CommandPrompt.Activities": "[1.0.8]",
    
    "UiPath.Excel.Activities": "[2.10.4]",
    
    "UiPath.Form.Activities": "[1.2.1-preview]",
    
    "UiPath.Mail.Activities": "[1.10.4]",
    
    "UiPath.System.Activities": "[21.4.0]",
    
    "UiPath.UIAutomation.Activities": "[21.4.3]",
    
    "UiPath.WebAPI.Activities": "[1.7.0]"
    
3. Run the framework from Main.xaml workflow inside UIPath Studio
