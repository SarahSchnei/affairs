This is my Python attempt at a Yale Econometrics assignment that is expected to be done in R.
The dataset comes from an R package, AER, which was created for the Econometrics course, and is full of datasets for the homeworks.

The data comes from Ray C. Fair's 1978 "A Theory of Extramarital Affairs" in the Journal of Political Economy. It data comes from self reported surveys in Redbook and Psychology Today, asking participents to provide information regarding their relationship happiness, years married, presence of children, and other factors. 
Fair was testing his own model about the allocation of an individual's time spent between a spouse and other activites. The surveys supported his model, but he needed more evidence.
In reading Fair's paper, I think the dataset in AER doesn't have all of the attributes that Fair is working with when testing his own model.

My model asks how likely someone is to have an affair with the given data. Fair's model asks about the link between time spent with a spouse and having an affair.

**Data Dictionary**

affairs
numeric. How often engaged in extramarital sexual intercourse during the past year?

gender
factor indicating gender.

age
numeric variable coding age in years: 17.5 = under 20, 22 = 20–24, 27 = 25–29, 32 = 30–34, 37 = 35–39, 42 = 40–44, 47 = 45–49, 52 = 50–54, 57 = 55 or over.

yearsmarried
numeric variable coding number of years married: 0.125 = 3 months or less, 0.417 = 4–6 months, 0.75 = 6 months–1 year, 1.5 = 1–2 years, 4 = 3–5 years, 7 = 6–8 years, 10 = 9–11 years, 15 = 12 or more years.

children
factor. Are there children in the marriage?

religiousness
numeric variable coding religiousness: 1 = anti, 2 = not at all, 3 = slightly, 4 = somewhat, 5 = very.

education
numeric variable coding level of education: 9 = grade school, 12 = high school graduate, 14 = some college, 16 = college graduate, 17 = some graduate work, 18 = master's degree, 20 = Ph.D., M.D., or other advanced degree.

occupation
numeric variable coding occupation according to Hollingshead classification (reverse numbering).

rating
numeric variable coding self rating of marriage: 1 = very unhappy, 2 = somewhat unhappy, 3 = average, 4 = happier than average, 5 = very happy.

