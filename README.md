# my-new-project
Building AI course project

# Project Title

Optimizing recycling with AI

## Summary

GreenAI is a mobile application that uses image recognition to identify waste items. It tells users the correct recycling bin and provides educational tips to reduce contamination, making recycling easier and more effective for everyone.

## Background

Recycling is a key action for sustainability, but it's often done incorrectly.A large percentage of recyclable waste ends up in landfills because people are unsure how to sort items correctly. Recycling rules can be confusing and vary by municipality. It's impractical for a person to memorize all the specifics for every piece of packaging. I often find myself standing in front of multiple bins, holding a piece of packaging and guessing where it goes. This project aims to solve that moment of confusion with a quick, AI solution. 


## How is it used?

Users simply open the app and point their phone's camera at a piece of waste, like a yogurt cup or a crumpled wrapper. The AI identifies the object in real-time and overlays an icon on the screen indicating the correct bin, for an example a blue arrow for recycling, a green bin for compost etc. 

## Data sources and AI methods

The model would be trained on a large, open-source dataset of waste imagery, such as the TACO Trash Annotations in Context dataset. We would also collect and label additional images to improve accuracy for specific, common items.

## Challenges

This app does not solve the root cause of waste, which is overconsumption and non-recyclable product design. It is a tool for better management within the current system. Accuracy can be affected by lighting, damaged packaging, and very new or obscure products. It also requires local recycling rules to be programmed into its database. We must also be cautious of data privacy. Images should be processed on the device rather than being sent to a cloud server to be stored. The app should be free to ensure equitable access.

## What next?

Collaborate with municipalities and waste management companies to integrate local recycling rules directly and promote the app. Add a feature to scan entire shopping baskets to assess the recyclability of products before purchase, encouraging better consumer choices. Moving forward would require more expertise in mobile app development and deploying optimized ML models to edge devices.


## Acknowledgments

Inspired by: https://wasterobotic.com/
[TACO dataset](http://tacodataset.org/)
