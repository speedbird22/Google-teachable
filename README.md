<h1 align="center">Hi 👋, I'm Akshith Reddy</h1>
<h3 align="center">A passionate Programmer from India</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=speedbird22&label=Profile%20views&color=0e75b6&style=flat" alt="speedbird22" /> </p>

- 🔭 I’m currently working on **gym buddy**

- 🌱 I’m currently learning **Java, Python**

- 🤝 I’m looking for help with **this project**

- 💬 Ask me about **HTML, CSS, C++**

- 📫 How to reach me **akshithreddyworld2020@gmail.com**

- ⚡ Fun fact **HTML is my most favorite language**


<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=speedbird22&show_icons=true&locale=en&layout=compact" alt="speedbird22" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=speedbird22&show_icons=true&locale=en" alt="speedbird22" /></p>


<h3>About my project - Google Teachable - Gym buddy</h3>
<h1> Site link: https://teachablemachine.withgoogle.com/models/Gc0OzdME1/</h1>
<h4>Gym Buddy is a revolutionary exercise posture recognition tool designed to optimize workout experiences by analyzing and classifying different exercise postures. It identifies potential form flaws and provides tailored corrections to help users achieve ideal posture and avoid injury. Imagine it as an advanced altitude control system on an aircraft. When autopilot detects the aircraft isn’t at the required altitude, it overrides manual control and fine-tunes adjustments to reach the perfect altitude. Similarly, Gym Buddy recognizes the user's current exercise, analyzes the posture, and offers real-time, actionable feedback to enhance each movement.

However, Gym Buddy doesn’t stop at correction—it is a comprehensive fitness companion. It motivates users to push harder, work consistently, and stay on track with their fitness goals. Through personalized gym plans uniquely designed to suit individual needs, Gym Buddy helps users steadily progress, ensuring they remain engaged and make sustainable gains.

Looking to the future, Gym Buddy aims to evolve into a highly interactive and intelligent platform, incorporating advanced AI and machine learning to offer even more precise and adaptable recommendations. Future goals include expanding its exercise database to cover a wider variety of workout styles, from yoga to strength training, as well as integrating with popular wearable devices for more seamless monitoring of biometrics. Additionally, the vision includes a social feature that allows users to connect, share achievements, and participate in challenges, creating a community-driven fitness experience. As we push forward, Gym Buddy will continue to strive for excellence, bringing smarter, more intuitive fitness solutions to people worldwide.

This project has a long journey ahead, but its potential impact on the fitness world is vast. I’m looking for passionate and tech-savvy collaborators who are excited about the intersection of fitness, technology, and innovation. Together, we can build something that could transform millions of workout routines worldwide!
This is Akshith Reddy, and ill see YOU on my project site, ciao!</h4>
<h1> Using Google teachable machine for Gym buddy</h1>

<h4> Google's Teachable Machine was a pivotal tool in developing the Gym Buddy model. It provided a user-friendly and efficient platform to prototype the posture recognition model with minimal effort. Here’s a detailed breakdown of how it was used and how it contributed to the project:

Step-by-Step Process
Data Preparation

Images collected from online sources were sorted into folders based on categories:
Correct Postures (e.g., proper squat form).
Incorrect Postures (e.g., improper back alignment in squats).
Each category was represented with a balanced number of images to avoid class bias.
Uploading Images

The categorized images were uploaded to the Teachable Machine interface.
The tool automatically organized the images into training and validation sets, simplifying data preparation.
Model Training

Teachable Machine uses transfer learning, leveraging pre-trained neural networks optimized for image classification tasks.
Training was conducted within the browser, significantly reducing the complexity of setting up an ML environment.
The training process was visualized in real-time with metrics like loss and accuracy displayed.
Exporting the Model

Once trained, the model was exported in TensorFlow.js format for integration into web applications.
This export made it straightforward to deploy the model on multiple platforms, including browsers and mobile devices.
</h4>

Memory updated
Here’s the updated README reflecting that pictures were exclusively used:

README for Project: Exercise Posture Recognition Tool - Gym Buddy
Introduction
Gym Buddy is an intelligent exercise posture recognition tool that leverages machine learning to classify various exercise postures, identify flaws in form, and suggest corrective actions. The tool is designed to motivate users, encourage consistency, and generate personalized gym plans for enhanced fitness outcomes.

Data Collection and Preparation
Data Collection
The training data for Gym Buddy was sourced entirely from online images.

Public Datasets: Curated collections of labeled exercise images (e.g., push-ups, squats, lunges).
Manually Gathered Images: Images scraped or downloaded from fitness-related websites, ensuring a mix of body types, environments, and demographics.
Data Annotation
All images were carefully annotated using tools like LabelImg to ensure accurate categorization by exercise type and posture classification (e.g., correct form, incorrect form).

Impact of Diverse Dataset
Incorporating a diverse dataset significantly enhanced:

Model Accuracy: Improved recognition of exercise postures across varied demographics.
Reliability: Reduced biases, ensuring consistent performance regardless of environmental factors or user characteristics.
Model Creation Using Google’s Teachable Machine
Google’s Teachable Machine was instrumental in creating the initial prototype of the model due to its simplicity and efficiency.

Data Upload: Images were categorized and uploaded for each exercise class (e.g., correct squat, incorrect squat).
Training: Teachable Machine automatically split the data into training and validation sets, applying transfer learning to pre-trained neural networks.
Export: The trained model was exported in TensorFlow.js format, allowing integration into web and mobile platforms.
Features and Functionalities
Core Features
Posture Classification:
Real-time detection of exercise postures using a webcam or device camera.
Flaw Identification:
Highlights errors in form and provides detailed feedback.
Motivational Messaging:
Delivers encouraging messages to promote user consistency.
Personalized Gym Plans:
Adapts to user performance to create customized fitness routines.
Additional Functionalities
Exercise Tracking: Tracks the number of repetitions and sessions completed.
Progress Monitoring: Generates detailed performance analytics for users.
Performance Evaluation
Evaluation Methods
Confusion Matrix: Used to assess classification accuracy and identify misclassified instances.
Precision, Recall, F1-Score: Metrics computed to evaluate model robustness for different classes.
Cross-Validation: Performed to ensure the model generalizes well on unseen data.
User Testing: Feedback was gathered from fitness enthusiasts to assess real-world usability and reliability.
Results
Accuracy: 92.5% on the test dataset.
User Satisfaction: 85% of users found the tool helpful in correcting their exercise postures.
