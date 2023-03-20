

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

Food calorie data from ....

Exercise data from .....

Individual data from ....

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?


![Scales](https://www.pngall.com/wp-content/uploads/2016/09/Weight-Scale-Free-Download-PNG.png)


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

Currently the project doesn't consider the persons metabolsim. This would effect the rate of weight loss. Also the system would need access to personal infromation which would need to be protected.

## What next?

There are already apps which track each individual food eaten, and provide a wealth of data which could be added to the model (Different types of fat, cholesterol, sodium, fiber, sugar, protien, vitamins, iron, etc).


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
