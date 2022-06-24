<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->
# Project Title
Final project for the Building AI course
## Summary
This project will use data collected about how a user exercices to recommend the activities for the day that will best meet their goal. Taking into acount factrors such as sleep, fatigue, and what the user finds fun, AI methods can be used to better avoid injury and make progress while not burning out.
## Background
Sometimes exercise is seen as a chore, and often people are not good at managing their workout schedule to maximize the efficiency of their workouts while avoiding injury. Hopefully this project can succeed in a way that no other solution thus far has -- exercise should still be fun and sometimes the raw efficiency of a workout should be set aside in order for someone to enjoy themselves. I envision this project as being a companion through a lifetime of exercise, not a tool to be used to train for a marathon and then ignored. Instead, AI could enrich the user's life by emphasizing the importance of exercise and fitting it within the existing structure of someone's life.

## How is it used?
Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?
Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)
If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">
This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]
   totPop = sum(pop)
   totFish = sum(fishers)
   # write your solution here
   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%
main()
```
## Data sources and AI methods
With wearable devices collecting things like heart rate and GPS posiiton, many people who run can collect very detailed data on their workout. For bikers, power meters allow for constant measurement of work output during a workout. Many other activities benefit from the same technology, including rowing, swimming, skiing, and hiking.

## Challenges
What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?
This project is limited by the same things that make exercise planning difficult. It probably cannot work for someone who misses a lot of workouts or ignores the plan. 
## What next?
How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 
## Acknowledgments
* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
