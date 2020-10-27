**REDA1-CE1000: Introduction to Real Estate Data Analytics**

**Week 1: Course Introduction and Overview**
Demystifying the Unmystical
Like a hammer and nails, this class is about ideas and the tools to implement them
The ideas do not change, but the tools to impliment them do

Course Introduction and Overview
* Who I am
    * Principal Data Scientist at Fidelity Investments
    * Previously, Head of Quantitative Modelling at CBRE
* What matters
    * Econometrician/economist by training
    * Data scientist by practice

Perspective
   -  Like every other major industry, CRE will be disrupted by the application of technology empowered by data analytics.
   - It will be called different things, but it is the same thing.
      -  Econometrics and forecasting
      -  Statistical learning
      -  Machine learning
      -  Artificial intelligence (not really)
    
* Why?
    * Example: I want to predict what the 10-Year U.S. Treasury is going to be in the future to determine a realistic DCF for my property.
    * Example: I want to predict what the cap rate on this property is, based on its characteristics.
    * Example: I want to predict how likely my current tenant is to churn at the end of her lease term. (And whether I can intervene to affect the decision.)
    * Example: I want to predict how labor costs will change with time.
    * Example: Given the current interest rate environment, demand for hard assets like CRE is strong. Algorithmic deployment of capital.
        * The same thing happened with bond and equity trading.


My Goals
* Develop a common language among us through rapid immersion.
    * Exploring conjectures about the world (without data, this is now called "thought leadership").
    * Time series as storytelling and for forecasting.
    * Examples of when algorithms fail and considerations about causation.
* Introduce you to R and R Studio to rapidly expand your tool kit.
    * Provide historical background in probability and statistics.
    * R is a low-level programming language developed by Ross Ihaka and Robert Gentleman (hence R).
* I will be using Jupyter notebooks (as a substitute for PowerPoint).
    * Occasional use of Python graphics in class.
    * Visualizations and Monte Carlo methods rather than mathematical proofs.
        * You are not responsible for Python.
        * You will use R and R Studio with sample R code to be implemented in class.
            * Why R and R Studio?
                * Stable code base and platform
                * Open source and free
                * Learning curve is not steep, allowing for immediate immersion in data acquisition and analysis
                * Compatible with other statistical learning environment, and this class is focused on ideas (not necessarily tools)
                * Open source and free
        * These notes will live until we turn out the lights.
* Provide you with many examples from a variety of sources, including real estate and finance.
* Typical week: Lecture with multiple examples, together with graded weekly assignments.
    * I know of no other way to learn data analytics than to do it repeatedly.
    * Data analytics is a contact sport.
* By the end of this class, you will know more about data analysis than the chief economists of either CBRE or JLL.
* Never forget: If I can do this, so can you. And you'll be better RE professionals.


Prominent CRE Brokerage Forecast for 2020 (in December 2019)
* Fed Funds target rate of 1.25% or 125 basis points (bps).
* "Good, not great" output growth.
* Slight decline in capitalization rates 
￼
*  slightly higher real estate values.

Concurrent Forecast Errors
* FOMC had already lowered its target rate by 40% to 1.5% during 2019.
    * Inconsistent with a forecast of 1.25%.
* Long-term interest rates fell substantially during 2019 with the 10-year U.S. Treasury declining by 30%.
    * Reflecting slowing output growth.
* Yield curve (10-year minus 3-month) was below 50 bps and had been falling since 2017.
    * It was negative for substantial portions of 2019: Professor Campbell Harvey's recession predictor.
* In other words, the predictions were not consistent with the economic data at the time the predictions were made.
    * Live by the forecast, die by the forecast error.
* One might call this the state of artificial intelligence in commercial real estate.

In Truth, There Is No AI
* For the difficult questions that we face in CRE, there is no artificial intelligence.
* We have tools, and you must put the human back into machine learning.
* You must think about relationships given your domain knowledge in real estate.
    * Finance: Can you predict interest rates or cap rates?
    * Development: Can you predict labor costs?

A Review of the Syllabus

An Introduction to R and R Studio
* R v. Python v. Excel
    * Access to a massive collection of algorithms and datasets
    * R has better time-series algorithms
    * R, Python and Excel are merely tools to implement ideas
        * Present Discounted Value: It a built-in function in Excel, but why do we discount?
* Jupyter v. PPT: instantenous updating
    * I have a standard talk on the current state of the macroeconomy and its implications for CRE that I can update it in real time.
R and R Studio
* Installing and loading libraries
* CRAN, task views, and R vignettes
* Graphics and story telling
* Linear regression
* Dataframes as spreadsheets
* Application Protocol Interfaces (APIs)
* Webscrapping
* Feature engineering (data manipulation)
* Practical examples

Credits

This notebook is based on materials developed by Timothy H. Savage. Used with permission.
https://github.com/thsavage
