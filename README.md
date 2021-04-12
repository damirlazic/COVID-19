<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# COVID-19 LockDown possibility

Final project for the Building AI course

## Summary

This project's goal is to provide a tool, that would predict COVID-19 LockDown. AI-based tool to help people knowing will LockDown put in place and when. Building AI course project


## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?
People are confused with a current panemic situation and place measures, don't know when everything will be closed or opened.

This is how you make a list, if you need one:
* when LockDown will be placed
* how long it will last
* when all be opened again


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Solution would be available for everyone, yet everyone would be using it on their own responsibility, predictions are still only predictions! The use itself would be very simple - just give the program an index of a tested patients, give it time to process the data and check out the results.

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://www.eu-cord.org/2015/wp-content/uploads/2020/04/covid-19.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://www.eu-cord.org/2015/wp-content/uploads/2020/04/covid-19.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Croatia', 'Germany', 'England', 'Norway', 'Sweden']
   testedpatients = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   positivepatients = [1891, 2652, 3800, 11611, 1757]

   tottestedpatiens = sum(testedpatiens)
   totCovid = sum(positivepatients)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
Data are entered by myself for now...

If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?
Project does not solve the pandemic, for sure challenge is the huge amount of unknowns within this COVID-19 story.

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 
Data gathering, building a simple model for first tests and looking where it goes!

## Acknowledgments
The Elements of AI Team for giving an inspiration to think about this project
The rest will come with the project's progress :)
* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
* 
