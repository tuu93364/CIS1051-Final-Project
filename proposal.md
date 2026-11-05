# Proposal

## What will (likely) be the title of your project?
ClosetIQ: Smart Virtual Wardrobe 

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")
An interective virtual wardrobe application that lets users upload and organize pictures of their clothes and generate outfit suggestions for different occasions and weather conditions. We also hope to use optimization techniques to help users plan outfits and pack efficintly for trips.

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?
Our goal is to create a practical application that makes choosing outfits easier and helps people get more use out of the clothes they already own. Users will upload pictures of their clothing items and enter information such as category (tops, bottoms, shoes, and outerwear), color, season, and style. The application will display these items in a digital closet, where users can browse, filter, add, and remove pieces. Clothing information will be saved so that users do not have to rebuild their wardrobe every time they open the program.

The main feature will be an outfit generator that combines items from the user's own closet. Rather than selecting clothes completely at random, we plan to create rules to filter and rank outfits according to factors such as occasion, weather, and color compatibility. If time permits, we also want to build a weekly outfit planner to reduce repetition and a travel packing feature that selects a limited number of versatile items for a multi-day trip. This would let us explore optimization concepts that relate to our Industrial and Systems Engineering major.

We plan to implement the project primarily in Python. We are considering a visual interface built with Streamlit or Tkinter, and a library such as Pillow to display clothing images. Users would run the application on a computer and interact with it through its interface. We plan to create the recommendation and optimization logic ourselves, using functions, loops, conditionals, lists, dictionaries, and file handling.

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?
I am not combining my final project with any other course's final project. 

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.
My name is Yasmin Costa, my email adress is tuu93364@temple.edu, my TA's name is Faegheh Seifhashemi and I am collaborating with Sarp Dickmen, his email address is tuu57295@temple.edu, and his TA's name is Lavdrim Islami.

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?
- A working digital closet where users can add clothing items with pictures and basic information.
- Clothing categories and filters so users can browse their wardrobe.
- A way to save and reload wardrobe information.
- A basic outfit generator that creates combinations from the available clothes.

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?
- Everything in the GOOD outcome.
- An outfit recommendation system that considers occasion, weather, season, and color compatibility.
- A scoring or ranking method that shows users the most suitable outfit combinations.
- An improved visual interface for browsing clothes and viewing recommended outfits.

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?
- Everything in the GOOD and BETTER outcomes.
- A travel packing optimizer that recommends a small collection of clothes capable of creating outfits for several days while respecting a clothing-item limit.
- A weekly outfit planner that suggests varied outfits and avoids unnecessary repetition.
- Additional refinements, such as favorite outfits or basic wardrobe-use statistics, if time allows.

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?
Our first step will be to decide on the interface framework and design how clothing information will be stored. We will research how to build an interactive Python interface, upload and display images, and save data using files or a simple database. Next, we will create a small sample wardrobe and develop the basic logic for combining clothing items into outfits. Once that works, we will research recommendation and optimization techniques to filter, score, and rank combinations. If we have enough time, we will extend the program to the weekly planner and packing optimizer. Throughout development, we will test the program with different wardrobes and document our progress in GitHub.

We plan to divide the work so that I focus initially on the digital closet, image handling, data storage, and interface, while Sarp focuses initially on outfit generation, compatibility rules, and optimization features. We will work together on the overall design, integration, debugging, testing, documentation, and final demonstration. Both of us will contribute code and make sure we understand the complete application.