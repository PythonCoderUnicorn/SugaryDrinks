# SugaryDrinks

A dataset for North American beverages and their sugar content. 

All data is collected from each company's website pdf or interactive nutrition information application.


## Companies included in the dataset
Tim Hortons, McDonalds, Orange Julius, Jugo Juice, Booster Juice, Second Cup (coffee)

### columns are: 
- `data_date` for date of nutrition information
- `country` of website (.com)
- `servSize_ml` serving size in ml 
- `item` name of beverage product
- `calories` number of calories for beverage based on serving size
- `fat_g` for grams of fat (total fat) in a beverage
- `SatFat_g` for Saturated Fat in grams 
- `Carbs_g` for grams of carbohydrates in a beverage
- `Fibre_g` grams of fibre (fiber) in a beverage
- `Sugars_Total_g` the total amount of sugar in grams for a beverage

Other nutritional information was neglected for brevity and selection of primary concerns regarding nutrition content for Diabetic sugar and carbohydrate intake volumes.

---

The **WHO** guideline recommends adults and children *reduce their daily intake of free sugars ~ 25 g (6 tsps) per day*

This includes: 
- glucose and dextrose, fructose, household sugar (sucrose)
- malt sugar (maltose) and also sugars that are found in honey, syrups, fruit juices and fruit juice concentrates. 
- Free sugars are either added to the food by the consumers themselves (e.g. sugar in coffee, honey in muesli, …), but they are also found in many processed foods (e.g. ready meals, soft drinks, cookies) and in the catering sector (e.g. sugar in desserts)




### Excluded drinks
- McDonalds smoothies are excluded, as their serving size is in grams. 

## Reference guide on grams of sugar

| Teaspoons to grams | Coca-Cola Sugar | US oz. | ml |
|--------------------|-----------------|--------|----|
| 1 teaspoon = 4.2g	|
| 2 teaspoons = 8.4g |	
| 3 teaspoons = 12.6g |
| 4 teaspoons = 16.7g |
| 5 teaspoons = 20.9g |
| 6 teaspoons = 25.2g | 25 g | 7.5 | 221 |
| 6.5 teaspoons       | 26 g | 8   |
|                     | 28 g | 8.5 |
| 7 teaspoons = 29.3g |
| 8 teaspoons = 33.5g |
| 9 teaspoons = 37.7g |
|                     | 39 g | 12 | 354 |
|                     | 52 g | 16 | 473 |
|                     | 65 g | 20 | 591 |
|                     |      | 22 | 650 |
|                     |      |    |     |

| pasta  | size |  carbs |
|--------|-------|-------|
| macaroni (wheat durum semolina) | 3/4 cup (85 g) | 67 g |
| calories: 310, fat: 1.5, sat. fat: 0.4g, fiber: 4g, sugar: 2g |








