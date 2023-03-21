

<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Weight change

Final project for the Building AI course

## Summary

This AI project estimates weight change based on person, exercise and diet. Everyone is different, and a diet which works for one person may not work for another. Also, people respond differently to other exercise routines. 


## Background

Maintaining a healthy weight is essential, and as someone who used to be obese, I know it can be challenging to find the right combination of diet and exercise to achieve this. What works for one person may not work for someone else. Some people need more time or equipment for exercise. People like different foods, and the food contains various levels of calories. Also, when dieting or exercising, weight is not lost consistently over time, people usually lose a lot of weight at the start, but this weight loss slows down as more weight is lost. An AI system, which can work out how much you can expect to lose over time given a specific diet or exercise routine, can set expectations and reduce the loss of motivation when the initial loss rate is not maintained.




## How is it used?

The AI system will initially be trained using data from various diets and exercises to create a 'generic' AI. The system will be able to give results for a typical person, i.e. If a regular person eats 2000 calories a day, runs for 30 minutes, sleeps for 8 hours and has an initial BMI of 25, their weight will change by 4% per year. 

We can then refine the AI. We can provide it with the weight loss people have achieved using different types of diet, for example, Atkins diet, Ketogenic diet, Vegetarian diet, etc. All diets have various characteristics, not just reduced calories. Some are high in protein or fibre, and some are lower in fat. 

We can then add in the different types of exercise, rather than a generic; they exercised for so many minutes. For example, is it an aerobic exercise or a vigorous exercise? Is it a strengthening exercise which may replace fat with muscle rather than reducing weight loss? 

The AI results will reflect that different diets work differently with other exercises. For example, a Paleo diet would work poorly with exercise like running or cycling due to the need for carbohydrates.

As they track calories, sleep and exercise along with changes to their BMI / weight, the AI will more accurately estimate their weight changes in the future.



We could provide an API/interface into the AI system, allowing developers to incorporate the weight loss predictions into Apps and websites.


![Scales](https://www.pngall.com/wp-content/uploads/2016/09/Weight-Scale-Free-Download-PNG.png)


## Data sources and AI methods
There are many sources for the data. Initial food data is available from the USDA (U.S. Department of Argiculture), which provides database access:

https://fdc.nal.usda.gov/

This will give detailed information on individual food, for example, the Snickers bar I am currently eating:

https://fdc.nal.usda.gov/fdc-app.html#/food-details/169589/nutrients

For exercise, there are many APIs which will provide access to data. For example, several can be found at:

https://rapidapi.com/search/fitness

## Challenges

Initially, merging exercise and food analysis data will be a problem. This will be solved over time as our system is used and people provide their own results based on diet and exercise. The more people use the system, the more accurate it will become.

Currently, the project doesn't consider the person's metabolism. This would affect the rate of weight loss. Also, the system would need access to personal information, which we must protect.

## What next?

There are already apps which track each food eaten and provide a wealth of data which could be added to the model (Different types of fat, cholesterol, sodium, fibre, sugar, protein, vitamins, iron, etc).



