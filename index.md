<img style="float: right;" src="img/1024.png" height="150px" width="150px">

# Welcome to ProjectAble Home Page 

> A Helpful Status Reporting and Forecasting App for iPhone

## What is ProjectAble?
**ProjectAble** uses a traditional project management technique called Earned Value Analysis to forecast the outcome of the project accurately and reliably.

### Budget Distribution
**ProjectAble** uses the reporting frequency, start and end dates, and the selected budget distribution curve to spread the project budget accordingly. **ProjectAble** does this by dividing the duration into quarters and applying rates to each reporting period within each quarter in order to get the right distribution.

### Treatment Of Time
**ProjectAble** uses time only to calculate the project duration and number of reporting periods. Each time you add a new progress update, **ProjectAble** calculates the percentage complete and spend for the reporting period. The reporting period is important but **ProjectAble** doesn't use the current date and time in it's calcultations. When you add the final progress update, **ProjectAble** will set the percent complete to 100%. As with all progress updates, you can overwrite the pre-calculated values. Setting the percent complete to less than 100% will allow the project to continue but in these circumstances the calculations may behave unexpectedly.

### Completing a project
A project is completed when the percent complete is set to 100% either with the final reporting period or by clicking the button on the Project Details screen.

## Use of Earned Value (EVA) techniques
**ProjectAble** uses the earned value calulation methods published in the **Project Management Book of Knowledge (PMBoK)** [PMBOK / EVA](https://www.pmi.org/learning/library/make-earned-value-work-project-6001).

Calculation | Descriptive Method
------------|-------------------
Planned Value (BCWS) | Percent Complete * Budget At Complete (original project budget)
Earned Value (BCWP) | Actual Percent Complete * BAC
Schedule Variance | EV - PV
Schedule Performance Index | EV / PV
Cost Variance | EV - AC (Actual cost to date)
Cost Performance Index | EV / AC
Estimate At Complete | BAC / CPI
IEAC1 (independent EAC1) | (AC + (BAC-EV)) / CPI
IEAC2 (independent EAC1) | (AC + (BAC-EV)) / (CPI * SPI)
Estimate To Complete | EAC - AC
To Complete Project Index | (BAC - EV) / (BAC - AC)


## ProjectAble General Notes
- ProjectAble **_is_** a helpful tool to enable project professionals to track the status and forecast of a project quickly, reliably and accurately
- ProjectAble **_is not_** intended to replace good planning, estimation, monitoring or control processes. Other tools are available for those purposes.


You can use the [editor on GitHub](https://github.com/SnowyAlcazar/aleynmoor/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.


