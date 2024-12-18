# London Prescribing Map

Mini-app to visualise drug prescription across various spatial district data zones in London. It contains prescribing data aggregated by Clinical Commissioning Group (CCG) regions in London between 2011-2013. Data that can be visualised includes the percentage of items prescribed corrected to the population and the cost per person. Drug types that can be compared includes statins, anti-depressants and diabetes drugs.
Output and allows users to interactive explore and visualise their data.

## Background

Three drug types that are topical and frequently in the news are statins, anti-depressants and diabetes drugs.

### Statins

Statins are medicines which lower the level of cholesterol in the blood. High levels of 'bad cholesterol' can increase the risk of having a heart attack or a stroke and of developing cardiovascular disease. [http://www.bbc.co.uk/news/health-18101554]
The National Institute for Health and Care Excellence (NICE) says the scope for offering this treatment should be widened to save more lives. The NHS currently spends about £450m a year on statins. If the draft recommendations go ahead, this bill will increase substantially, although the drugs have become significantly cheaper over the years. It is not clear precisely how many more people would be eligible for statin therapy than now, but NICE says it could be many hundreds of thousands or millions. [http://www.bbc.co.uk/news/health-26132758]

### Anti-depressants

The use of antidepressants rose significantly in England during the financial crisis and subsequent recession, with 12.5m more pills prescribed in 2012 than in 2007, a study has found. Researchers from the Nuffield Trust and the Health Foundation identified a long-term trend of increasing prescription of antidepressants, rising from 15m items in 1998 to 40m in 2012. But the yearly rate of increase accelerated during the banking crisis and recession to 8.5%, compared to 6.7% before it. [http://www.theguardian.com/society/2014/may/28/-sp-antidepressant-use-soared-during-recession-uk-study]
The report also found that rises in unemployment were associated with significant increases in the number of antidepressants dispensed and that areas with poor housing tended to see significantly higher antidepressant use.

### Diabetes drugs

It is estimated that more than 1 in 17 people in the UK have diabetes. In 2014, 3.2 million people had been diagnosed, and by 2025 this number is estimated to grow to 5 million. [https://www.diabetes.org.uk/Documents/About%20Us/Statistics/Diabetes-key-stats-guidelines-April2014.pdf]
Diabetes, when present in the body over many years, can give rise to all sorts of complications. These include heart disease, kidney disease, retinopathy and neuropathy. Diabetes is the leading cause of amputations. [http://www.diabetes.co.uk/diabetes-and-amputation.html]
Data

## Checkout and run

You can clone this repository by using the command:

```
git clone https://github.com/Aridhia-Open-Source/shiny-demo-london-prescribing-map
```

Open the .Rproj file in RStudio and use `runApp()` to start the app.

### Deploying to the workspace

1. Download this GitHub repo as a .zip file.
2. Create a new blank Shiny app in your workspace called "london-prescribing-map".
3. Navigate to the `london-prescribing-map` folder under "files".
4. Delete the `app.R` file from the `london-prescribing-map` folder. Make sure you keep the `.version` file!
5. Upload the .zip file to the `london-prescribing-map` folder.
6. Extract the .zip file. Make sure "Folder name" is blank and "Remove compressed file after extracting" is ticked.
7. Navigate into the unzipped folder.
8. Select all content of the unzipped folder, and move it to the `london-prescribing-map` folder (so, one level up).
9. Delete the now empty unzipped folder.
10. Start the R console and run the `dependencies.R` script to install all R packages that the app requires.
11. Run the app in your workspace.

For more information visit https://knowledgebase.aridhia.io/article/how-to-upload-your-mini-app/
