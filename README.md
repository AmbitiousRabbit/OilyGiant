# OilyGiant

You work for the OilyGiant mining company. Your task is to find the best place for a new well.

Steps to choose the location:
* Collect the oil well parameters in the selected region: oil quality and volume of reserves;
* Build a model for predicting the volume of reserves in the new wells;
* Pick the oil wells with the highest estimated values;
* Pick the region with the highest total profit for the selected oil wells.

You have data on oil samples from three regions. Parameters of each oil well in the region are already known. Build a model that will help to pick the region with the highest profit margin. Analyze potential profit and risks using the Bootstrapping technique.

# Project description of the three regional datasets
* `id` — unique oil well identifier
* `f0`, `f1`, `f2` — three features of points (their specific meaning is unimportant, but the features themselves are significant)
* `product` — volume of reserves in the oil well (thousand barrels).


# Project Process

## Step 1 | Access & Study the data
* Open and skim to become familiar with the data
## Step 2 | Prepare the data
* Convert the data to the necessary types
* Find & Eliminate errors in the data
## Step 3 | Analyze the data
* Conduct EDA & SDA while exercising the 5 analytic frameworks (if applicable):
  * What happened? - Descriptive 
  * Why did it happen? - Diagnostic 
  * What will happen? - Predictive
  * How can we make it happen? - Prescriptive
## Step 4 | Build a predictive model 
* Consider and select useful data to analyze the information on the oil regions' behavior that can pinpoint the most lucrative region.
## Step 5 | General Conclusion
* State found insights in a clear, concise manner.
