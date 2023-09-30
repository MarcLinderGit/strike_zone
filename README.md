# Exploring Baseball Strike Zones with Machine Learning

In this project, I will harness the power of Support Vector Machines (SVMs) to uncover the elusive decision boundary that defines the strike zone in Major League Baseball (MLB). SVMs are formidable machine learning models known for their ability to create intricate decision boundaries that adapt to the training data.

**Key Project Objectives:**

1. **Explore the Data**: To kick off this project, we'll embark on a comprehensive exploration of datasets related to two prominent baseball players, Aaron Judge and Jose Altuve. With an eye for detail, we'll dive into the features of each pitch they faced during the 2017 season.

2. **Decipher Pitch Descriptions**: Before we swing for the fences, it's crucial to decode the pitch descriptions. We'll unravel the mystery behind these descriptions and gain a profound understanding of how balls and strikes are meticulously recorded.

3. **Label Data for Classification**: To make our analysis more effective, we'll transform the string labels 'S' and 'B' into numerical values. This conversion will pave the way for seamless data preparation and modeling.

4. **Visualize Pitch Locations**: Armed with clean data, we'll create insightful visualizations to understand how the pitch's location, represented by 'plate_x' and 'plate_z' columns, influences its classification.

5. **Build an SVM Model**: The heart of our project lies in constructing an SVM model capable of creating a decision boundary that mirrors the real strike zone. We'll split the data into training and validation sets for model validation.

6. **Visualize the Decision Boundary**: To provide a visual representation of our SVM's decision-making prowess, we've crafted a custom function called `draw_boundary`. This function will help us understand how the SVM classifies pitches.

7. **Assess Model Accuracy**: We won't be swinging blindly. We'll assess the accuracy of our SVM classifier to gauge its performance in predicting balls and strikes.

8. **Optimize SVM Parameters**: Seeking perfection, we'll experiment with SVM parameters such as gamma and C to discover the optimal configuration that outperforms previous models.

9. **Explore Other Players**: Beyond Aaron Judge and Jose Altuve, we'll extend our exploration to other players, like David Ortiz. This comparative analysis will allow us to gain insights into how different players' strike zones vary.

10. **Enhance SVM with Additional Features**: In our quest for perfection, we'll explore the inclusion of additional features, such as the count of strikes. These extra dimensions might be the key to a more accurate classifier.

Join me in this riveting journey into the realm of baseball strike zones, where we'll deploy machine learning to unlock hidden patterns and gain a deeper appreciation for the intricate art and science of America's favorite pastime.
