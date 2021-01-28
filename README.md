# Analyzing-Wine-Attributes

Determining which wine attributes are related to customers rating wines as good versus bad?

### The description of the different attributes as below:

**fixed acidity:** most acids involved with wine are fixed or non-volatile (do not evaporate readily)

**volatile acidity:** the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste

**citric acid:** found in small quantities, citric acid can add ‘freshness’ and flavor to wines

**residual sugar:** the amount of sugar remaining after fermentation stops, it’s rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet

**chlorides:** the amount of salt in the wine

**free sulfur dioxide:** the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine

**total sulfur dioxide:** amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine

**density:** the density of wine is close to that of water depending on the percent alcohol and sugar content

**pH:** describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale

**sulphates:** a wine additive which can contribute to sulfur dioxide gas (S02) levels, which acts as an antimicrobial and antioxidant

**alcohol:** the percent alcohol content of the wine

**quality:** score assigned by taster on a scale of 0 to 10

**color:** red or white

### Final Insights

If I were addressing this as a business problem such as what kind of wine to produce based on this data, I would make the following conclusions. First, wines that receive good reviews are high in alcohol content(corr_coef: 0.44)<sup>1</sup>, have fixed acidity(corr_coef: 0.48)<sup>2</sup> and are sweet(corr_coef: 0.22)<sup>3</sup>. Meanwhile, wines that received bad reviews are high in chlorides (corr_coef: -7.73)<sup>4</sup>, high in volatile acidity (corr_coef: -3.57)<sup>5</sup>, and are more dense(corr_coef: -0.27)<sup>6</sup>

Ref. 1

<img width="326" alt="Screen Shot 2021-01-28 at 3 24 06 PM" src="https://user-images.githubusercontent.com/51058259/106206197-e756da80-617c-11eb-9607-07bc0bcd52d8.png">

Ref. 2

<img width="346" alt="Screen Shot 2021-01-28 at 3 48 24 PM" src="https://user-images.githubusercontent.com/51058259/106208223-4702b500-6180-11eb-9244-e5859677e822.png">

Ref. 3

<img width="321" alt="Screen Shot 2021-01-28 at 3 49 26 PM" src="https://user-images.githubusercontent.com/51058259/106208316-67cb0a80-6180-11eb-9935-0251bdaee5a7.png">

Ref. 4

<img width="352" alt="Screen Shot 2021-01-28 at 3 49 58 PM" src="https://user-images.githubusercontent.com/51058259/106208375-7ca79e00-6180-11eb-82b9-40b7e9b759df.png">

Ref. 5

<img width="327" alt="Screen Shot 2021-01-28 at 3 50 31 PM" src="https://user-images.githubusercontent.com/51058259/106208410-8fba6e00-6180-11eb-9d3c-279a9ee7c01f.png">

Ref. 6

<img width="319" alt="Screen Shot 2021-01-28 at 3 51 06 PM" src="https://user-images.githubusercontent.com/51058259/106208454-a3fe6b00-6180-11eb-92f7-514e78b8ea5e.png">
