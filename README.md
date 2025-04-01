# HopHacks Hackathon Submission
Won the 5th Prize

## Inspiration
Despite the many advances in image processing and computer vision, they are still largely used for "fun purposes" such as AR games and SnapChat filters. How can we make use of these widely available tools to help improve the healthcare outcomes of patients?

## What it does
PhysioDetect is an application that allows users to continue physiotherapy at home and monitor how much progress they are making. Currently PhysioDetect specifically targets facial movement tracking to carefully monitor how Bell's Palsy patients are conducting and responding to exercises. The Mediapipe face mesh is able to track 468 points on the face in near real-time. Using the relative positioning of the points, we are able to get an accurate idea of the muscle movements and positioning. With this we are able to both diagnose and treat patients from the comfort of their own home. Tracking the progress over time, PhysioDetect is able to help doctors better care for their patients and for patients to be more aware of their own health. Furthermore, with the ongoing pandemic , many patients are having trouble continuing with their physiotherapy. Our application helps solve this problem and many others including accessibility and affordability of healthcare.

## How we built it
The frontend was first designed in Canva and further built out on HTML to leverage its lightweight, cross-platform, and highly expandable features. Python scripts were used to execute functions as needed such as accessing the mediapipe library or processing video data. Javascript was used to make API calls to write video files to the Google Firebase database.

## Challenges we ran into
Humans are not born to be still, people shift around, get closer to the camera for a better look, and it is hard to keep our head in one place. In order to accurately determine muscle movement from image data, we not only needed to normalize all our measurements, we also needed to make design considerations that would incentivize the user to hold still and face into the camera for the entirety of the exercise.

## Accomplishments that we're proud of
Currently , we have a prototype and wireframe ready for our website. In such a short time span, we were all pushed outside of our comfort zones, learned to work with a team across timezones, study disciplines, and backgrounds. We made calls to balance the importance of MVP features against easy wins that would produce little value. And most importantly, we spent this time learning.

## What we learned
Teamwork was the biggest skill we learned, how to work effectively individually but also to make the most of our time on calls together to have fun and get the job done.

## What's next for Physiodetect
Launching the website, moving from calculated face ratios to true machine learning by creating and training with a dataset, and developing an interface for physicians to access and use the video data.

## Built With
canva
html
javascript
mediapipe
py
python

## Hackathon Page
https://devpost.com/software/physiodetect
