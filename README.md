# EEP 153 – Project 4: TBD

## 📌 Overview
This project analyzes nutritional outcomes in Nigeria using a demand system and nutrient composition data to evaluate the effectiveness of policy interventions. We combine household food demand estimates with a Food Composition Table (FCT) to construct a nutrient system that maps consumption into nutrient intake. Using this framework, we measure nutritional adequacy relative to recommended dietary requirements (RDI) and simulate how different policies affect calorie and micronutrient deficiencies.


## 📊 Data
We use Nigeria's Living Standards Measurement Study (LSMS) data, sourced from six survey rounds between 2010 and 2016 (Q3 2010, Q1 2011, Q3 2012, Q1 2013, Q3 2015, Q1 2016). The dataset includes three components merged together:

- Food Expenditures (household-level spending by food item)
- Food Prices (market prices by quarter and market)
- Household Characteristics (demographic composition by age-sex group)


All datasets are stored in the `data/` folder.

---

## 📈 Goals

The project includes:

- Estimate a demand system describing how Nigerian households allocate food spending as a function of prices, income, and household composition.
- Map food quantities into nutrient intakes using Nigeria's Food Composition Table.
- Identify the most significant nutritional deficiencies.
- Simulate policy interventions (cash transfers and food subsidies) to assess their effectiveness in reducing deficiencies.
