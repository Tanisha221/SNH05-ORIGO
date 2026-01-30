# SNH05
Repository of Team Caffeinated coders for Smart Nitte Hackathon 2023

Ori-Go

Ori-Go is a hackathon project built to make learning more fun and interactive for kids using origami and image classification. The idea behind the project is to combine hands on creativity with technology so children can learn about animals while actually making something themselves.

Kids learn how to make origami animals, scan their origami using the app, and then get simple and interesting information about the animal they created. The project also focuses on spreading awareness about endangered species and how they can be protected.

What the app does

Ori-Go works in a simple flow that is easy for kids to understand.

First, the app provides YouTube playlists that show step by step instructions to make origami animals. These videos are selected to be easy to follow and suitable for children.

Once the origami is made, the child scans it using the app. A CNN model trained on origami animal images detects the shape and identifies which animal it represents.

After detection, the app displays information about the animal. This includes basic facts, habitat details, whether the animal is endangered, and simple actions kids can take to help protect the species.

Why we built Ori-Go

We wanted to move away from passive learning where kids only watch videos or read content. Origami makes learning active and engaging. Adding image recognition makes the experience exciting, and the animal awareness aspect gives the project a meaningful purpose.

Tech used

The image classification model is built using a Convolutional Neural Network trained on origami animal images.

The app interface was initially built using FlutterFlow. Due to limitations during the hackathon, full integration of the model was challenging, but the core idea and workflow were demonstrated.

YouTube playlists were used as the source for origami tutorials, and animal information was curated to be simple and child friendly.

Challenges faced

This was built during a hackathon, so time was limited.

Creating a usable dataset for origami animal shapes was challenging.

FlutterFlow had restrictions when integrating custom machine learning models.

Despite these challenges, we were able to present a working prototype and explain the full concept clearly.

Hackathon result

Ori-Go won first place for the assigned problem statement.

The project was also selected as a top 5 finalist overall out of 95 teams.

This project was built during the SART NITTE Hackathon.

Future improvements

The dataset can be expanded to improve detection accuracy.

The app can be rebuilt using a fully custom mobile framework.

More animals and endangered species can be added.

Game like elements can be introduced to make learning more engaging for kids.

Note

This repository represents a hackathon prototype and proof of concept. Some features are simplified due to time constraints.
