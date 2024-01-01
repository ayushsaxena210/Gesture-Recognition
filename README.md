# Gesture Recognition for Smart TV

This project focuses on implementing gesture recognition for consumer electronics, specifically Smart TVs. The objective is to create a feature that can identify five distinct hand gestures, allowing users to control the TV without relying on a remote.

The gestures are captured through continuous monitoring by the TV's webcam, and each gesture corresponds to a specific command:
- Thumbs up: Increase the volume
- Thumbs down: Decrease the volume
- Left swipe: 'Jump' backward by 10 seconds
- Right swipe: 'Jump' forward by 10 seconds
- Stop: Pause the movie

To train the model, we utilized a dataset comprising several hundred videos, categorized into one of the five gesture classes. Each video, typically lasting 2-3 seconds, is divided into a sequence of 30 frames (images). These videos feature different individuals performing the specified gestures in front of a webcam, mimicking the conditions the Smart TV will encounter.

Access the dataset [here](https://drive.google.com/uc?id=1ehyrYBQ5rbQQe6yL4XbLWe3FMvuVUGiL).
