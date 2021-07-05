
## mediAR: Interactive 3D Imaging to Optimize Healthcare
Emerging biotechnologies continue to rapidly transform the healthcare industry. We will utilize augmented reality to help doctors rapidly analyze and diagnose patients via interactive 3D imaging.

# Inspiration
Incredible breakthroughs in modern technology have allowed physicians to optimize patient healthcare, with an emerging focus on targeted therapies to fight diseases such as cancer. Over the past decade, augmented reality and machine learning technologies have specifically emerged as vehicles for personalized medicine to become more widespread. We believe that the next breakthrough in healthcare will be focused on using such technologies to provide personalized medicine tailored to the characteristics of individual patients. 

# What it does
mediAR is a comprehensive augmented reality application that helps physicians visualize 3D models for a variety of uses, such as pre-surgery/training or emergency diagnoses. To build an accurate model of a patient, a scan is taken of the outside body. Machine learning algorithms then combine external data from x-rays and CT scans in order to generate the model through augmented reality. Artificial intelligence can then utilize noticeable physical characteristics and previous diagnoses obtained from the patient’s data in order to visualize potential locations where there may be an issue or identify an early indicator of terminal disease. For surgeries, mediAR can utilize computer vision to pinpoint precise cuts and give recommendations for what tools should be used. Physicians can control and adjust the view of augmented reality models through built-in hand tracking and a companion phone app, which provides a log of potential symptoms and diagnoses. 

# How we built it
To create a simulation for the human body model, we primarily utilized the echoAR cloud-based augmented reality platform. Using the built-in console application, we imported a 3D model of a human body created using OnShape. Then, we wanted to create a test application that could utilize Apple’s ARKit framework to visualize what this would look like in real time. Using Xcode 12.4 and React JS, we used the API key containing the imported .obj file and built a test application for devices running iOS 13.0 or higher. We tested the application on iPhone 11/12 simulators and an actual iPhone SE. The companion app was modeled using the Figma software, including the app layout and graphical user interface. This allows us to simulate the app on most major smartphones running iOS or Android without using Xcode or the Android SDK. 

# Challenges we ran into
The main challenge that we faced was thinking about how to build the connections and interactions throughout the application. The goal was to focus on how physicians would actually use this new data, and ensure that the interactions between the augmented reality and companion phone app were intuitive enough that it wouldn’t slow down their process. Internally, we built a development flowchart to map out the functions of all the components of the mediAR system. The seamlessness of the echoAR cloud platform was able to solve a lot of our challenges, and made it easy to upload and simulate models within the console.  

# Accomplishments that we're proud of
Over the past 72 hours, we were able to gain a deeper insight in how we could take our programming knowledge from prior experiences and translate them to actual uses for the real world. We were able to utilize a wide variety of applications to build mediAR, including ReactJS, Xcode, Lucid Flowcharts, Figma, and Canva. The ongoing COVID-19 pandemic has accelerated the pace of change in the medical world. While development or engineering processes may traditionally take up to several months or years, it is now more important than ever for those in the industry to build and optimize treatments in a short timeframe. We believe that we demonstrated the skills to meet the demand of modern medicine and patient care. 

# What we learned
The main concept we learned was how to properly integrate augmented reality into existing or new applications. We wanted to build an app where augmented reality was not an extra feature, but rather the main focus. Through echoAR and ARKit, we are able to have our 3D models scale and work seamlessly within the demo app. The echoAR documentation was particularly useful in helping us achieve this goal, as we were able to set up everything properly after some minor adjustments.

# What's next for mediAR
The next logical step for mediAR is to consult medical professionals, AR researchers, and scientists on how we can transform the idea from a demo to a fully-fledged application. Additionally, we want to be able to understand the workflows of physicians and their interactions with patients in order to understand how to properly integrate this technology into their everyday lives. We will continue researching, developing, and building upon the product in order to expand the outreach of mediAR and optimize it for real world use. 



