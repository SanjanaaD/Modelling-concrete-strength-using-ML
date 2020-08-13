# Modelling-concrete-strength-using-ML
A regression problem to predict the strength of concrete using the given components

## Data Description
Concrete is the most important material in civil engineering. The concrete compressive strength is a highly nonlinear function of age and ingredients. Given the components, we are to predict the strength of the mixture

Data is provided in .csv format

### File descriptions
train_data.csv - the training set<br>
test_data.csv - the test set<br>
sample.csv - a sample submission file in the correct format<br>
meta.txt - supplemental information about the data<br>

### Data fields
Independent:<br>
cement - Cement (component 1)(kg in a m^3 mixture)<br>
blast - Blast Furnace Slag (component 2)(kg in a m^3 mixture)<br>
flyash - Fly Ash (component 3)(kg in a m^3 mixture)<br>
water - Water (component 4)(kg in a m^3 mixture)<br>
sp - Superplasticizer (component 5)(kg in a m^3 mixture)<br>
ca - Coarse Aggregate (component 6)(kg in a m^3 mixture)<br>
fa - Fine Aggregate (component 7)(kg in a m^3 mixture)<br>
age - Age (day)<br><br>
Dependent:<br>
strength - Concrete compressive strength(MPa, megapascals)
