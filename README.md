# datasets
csv files for MA206

This is a repository of multiple datasets used for MA206. Data pulled and adjusted from the locations listed below.

**Boston_Marathon.csv** - Data from 2015 and 2016 Boston Marathon finishers. Variables include Name, Age, M/F, Country, Official Time, Hour, Minute, Second, Overall, Gender, Division, Year.

**cars2.csv** - Dataset of 32 cars and their respective test measurements, as reported by Motor Trend magazine. Available in car (mtcars). Variables include Miles per Gallon (mpg), number of cylinders (cyl), Displacement in cubic inches (disp), gross horsepower (hp), rear axle ratio (drat), weight in 1000 lbs (wt), 1/4 mile time (qsec), v-shape or straight line engine (vs), transmission type (am), number of forward gears (gear), number of carburetors (carb).

**ChickWeights2.csv** - 238 observations from two groups of chicks, one group with a normal diet and one with a 40% protein replacement diet for 10 days. Variables include type of diet and weight (in grams).

**DopeyResults.csv** - Dopey Challenge results from January 2022. Original dataset compiled from Disney Marathon facebook page. Dopey Challenge includes 4 races in 4 days, a 5K, then 10K, then half marathon, then marathon. The first 4 variables are the finish time for each individual races. Last 4 variables are the converted overall miles per hour (average) for each individual race.


**Food.csv** - Food poisoning outbreak dataset available from CDC, lists instances from 1998 - 2015. Original dataset available https://data.world/cdc/foodborne-outbreak-database/workspace/project-summary?agentid=cdc&datasetid=foodborne-outbreak-database. Some cleaning and adjustment done here, variables are:
  **Year**: The year of the incident 
  **State**: The state where the incident originated
  **NY**: If the state is NY (True) or not (False)
  **Restaurant**: Did the outbreak trace back to a restaurant source? Yes (True) or No (False)
  **Illnesses**: How many people were reported sick
  **Hospitalizations**: How many people were hospitalized
  **Deaths**: How many people died


**HeightWeight** - 184 Body Measurements from Female students at Brigham Young University, available from Roger W. Johnson's 2021 article avialable https://www.tandfonline.com/doi/full/10.1080/26939169.2021.1971585. Using the formulat for body fat calculations found in AR 600-9 (Table B-5), a column was added for the estimated body fat percentage, which can be compared to the actual water-weight technique body fat measurement. 


**HudsonFish** - New York State Department of Environmental Conservation collected and measured PCB levels in four species of Hudson River fish collected between 2001 - 2011.
FDA limits PCBs in fish to 2 ppm or less for "safe human consumption". Is there a difference in Season or by Fish Type? ##Source - https://www.caryinstitute.org/eco-inquiry/hudson-data-jam-competition/datasets/pcbs-hudson-river-fish


**Kissing.csv** - Pseudo-recreation of Kissing Right dataset (Tintle textbook Exploration Exercise 3.1), variable is if the couple turned their heads right or left.


**Olympics.csv** - Medal Results for Olympics Games. Clarification for some variables are:
  **Sex**: M/F 
  **Age**: Age, in years
  **Height**: In cm
  **Weight**: In kg
  **Year**: Year
  **Season**: Summer or Winter
  **US**: Is the entry from the United States or not
  **Gold**: Is the entry a Gold Medal or not

**Pumpkin.csv** - Sample of pumpkins entered into the international GPC Pumpkin Weigh-Off of 2021. Original (complete) data found at http://www.bigpumpkins.com/WeighoffResultsGPC.aspx?c=P&y=2021. Variables include **Grower Name**, **Country**, **OTT** - the over-the-top measurement in inches for the size of the pumpkin, and **Weight**, the weight of the pumpkin in pounds.

**resignations.csv** - Senators who have resigned from 1900 - 2018. Variables are:
  **Member**: Name of the Senator
  **Party**: Political Party
  **State**: State the senator is from
  **Congress**: Which Congressional session
  **Resignation** Date: Date of Resignation
  **Reason**: Official reason of resignation
      
      
**Toast.csv** - Pseudo-recreation of Mythbusters Toast dataset (Tintle textbook problem 1.CE.4), variable is if bread landed butter side up or down.

**UFO.csv** - Sample of 5,000 reported UFO sightings collected from the National UFO Reporting Center (NUFORC). Variables include date, location, and description of UFO sighting. Variables of interest are **IsUS** and **IsDisc**, depicting if the UFO was sighting within the US (Y/N) and if the UFO shape could be classified as a Disc (Y/N). Original (complete) dataset available at https://www.kaggle.com/datasets/NUFORC/ufo-sightings.
