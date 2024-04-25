# Modeling and Simulation Portfolio
## Academic and professional Projects from Fall 2022 until Spring 2024

## Two-Year Summary

Over the past two years, I've been deeply engaged in the world of modeling and simulation through my work at the Study of Metacognition and Advanced leaRning Technologies (SMART) Lab and my commitment to volunteer activities. During this time, my focus has been on enhancing AI-human interactions, particularly in the domain of intelligent tutoring systems.

### SMART Lab Experience
At the SMART Lab, I contributed to several projects aimed at improving user interaction with AI systems. My role involved extensive data analysis, simulation of user interactions, and the development of models that predict and enhance learning outcomes. This hands-on experience not only sharpened my technical skills but also provided me with invaluable insights into the complexities of human-AI collaboration.

![*SMART Lab*](Images/SMART_LAB.jpeg)

### Research Contributions
My research during this period led to significant contributions to the field, particularly in intelligent tutoring systems. I authored and co-authored several papers that were accepted at prestigious conferences:

- "Investigating Pedagogical Agents’ Scaffolding of Self-regulated Learning in Relation to Learners’ Subgoals" accepted at the [International Conference of Artificial Intelligence in Education (AIED)](./Papers_and_Presentations/AIED.docx) conference. Tokyo, Japan.

- "Gender Differences in Self-Regulated Learning Strategy Use in an Intelligent Tutoring System" accepted at the [European Association for Research on Learning and Instruction (EARLI)](./Papers_and_Presentations/EARLI.docx) conference. Macedonia, Greece.  

- "Examining Gender Differences in Self-Regulated Learning with MetaTutor " accepted at the [American Educational Research Association (AERA)](./Papers_and_Presentations/AERA.docx) conference. Chicago, USA.

Each of these papers underscored the potential of AI to transform educational methodologies through adaptive learning environments and data-driven insights.

I have also contributed to the making and presentation of research posters including:

- "Examining Gender Differences to Leverage Self-Regulated Learning Scaffolding in an Intelligent Tutoring System." Poster submitted and
accepted to the 2023 UCF Student Scholar Symposium. UCF, Orlando, Florida. 

![*Poster Presentation*](Images/Poster_presentation.jpg) 

[Full poster here](Images/Poster.png)

This period has been instrumental in shaping my understanding and expertise in AI-driven educational tools, setting a solid foundation for my ongoing contributions to the field of modeling and simulation.

## Volunteering and Leadership
Beyond the lab, I dedicate my time to volunteering with organizations that promote science and technology education. My efforts are particularly focused on inspiring young students to explore and embrace technology, specifically artificial intelligence, as a crucial tool for problem-solving and innovation. As part of my commitment, I actively participated in National Center for Simulation events, representing them at major Modeling & Simulation (M&S) conferences. This included playing a key role in assisting with the annual Interservice/Industry Training, Simulation, and Education Conference (I/ITSEC) for 2022 and 2023, as well as contributing to the Florida Simulation Summit in April 2024. These experiences allowed me to contribute to the field's growth while fostering connections between educational initiatives and the broader simulation community.

## Key Projects

### Project 1: Multimedia Language Acquisition Research

#### Overview
This project leverages a rich array of multimedia tools—including PowerPoint presentations, websites, audio, and video content—to elucidate my research on language acquisition. The goal was to create an accessible and engaging educational resource that highlights the importance and intricacies of how we acquire languages.

#### Details
The multimedia approach was carefully chosen to cater to diverse learning styles, enabling a deeper understanding and retention of the material presented. By integrating dynamic visuals in PowerPoint, interactive elements on a dedicated website, and both audio and video explanations, the project offers a comprehensive learning experience. These elements work together to simulate various language learning scenarios and present research findings in an innovative manner.

#### Project Website
For a more interactive experience and to explore the resources developed for this project, visit the [Language Acquisition Multimedia Project website](https://organistammproject.weebly.com/).

### Project 2: Cognitive Architecture for Intelligent Tutoring Systems

#### Overview
This project was conducted as part of the "Understanding Humans for Modeling and Simulation" course. It involved a collaborative effort where my partner and I combined our expertise to develop a cognitive architecture model. The model is designed to depict the intentions of an intelligent tutoring system that is trained to monitor students' affective states for emotion regulation and to improve math performance.

#### Approach
The project employed an innovative approach by collecting multichannel multimodal data, which includes physiological, behavioral, and interaction data. This comprehensive data collection enabled the system to understand and react to student emotions effectively, thereby tailoring the learning experience to enhance both engagement and domain knowledge outcomes. In this case, Calculus.

#### Model Description
Our model integrates various components of cognitive architecture with advanced machine learning techniques to predict and respond to student needs dynamically. The emphasis was on creating a system that not only supports academic achievement but also fosters a positive emotional and psychological environment for learning.

On the student's end, the model begins with the assessment of their understanding and emotions. The student's judgment of learning (JOL) and feeling of knowing (FOK) prompt them to either seek help or continue working independently. As they engage with the material, their working memory is employed for rehearsal and encoding information into long-term memory. Emotional states are constantly monitored, with equilibrium signifying steady progress and disequilibrium indicating struggles that activate a cognitive reappraisal loop. This loop involves reflecting on their emotions and potentially re-framing their approach to the content.

In the physical world aspect, the Personal Affective Learning (PAL) assistant assesses the student's affective state. If a negative state is detected, affective interventions, such as encouragement or advice on study strategies, are employed. The PAL also provides scaffolding when the student faces problems, helping them to build upon their existing knowledge without direct instruction.

The virtual component of the ITS involves a cognitive monitor that assesses the student's mastery of content even when they're not actively asking for help. Similar to the PAL, a virtual affective monitor observes data to gauge the student's emotional state. Positive or neutral states continue the learning loop normally, while negative states trigger the affective monitor to provide suitable interventions to regulate emotions and maintain engagement.

The system is designed to facilitate a seamless flow of information between the student's cognitive and emotional domains, the physical PAL assistant, and the virtual tutor. By doing so, it aims to create a supportive environment that adapts to the student's learning and emotional needs, thereby promoting effective learning and emotional well-being.

#### Model:
![Cognitive Architecture Model](Images/Final_Model.png)

### Project 3: Supervised Learning in Language Acquisition Demographics

#### Overview
This project delved into the impact of demographics on language learning by employing supervised learning techniques. The objective was to determine how various demographic factors affect a student's language speaking score, with the score as the response variable (y) and demographic characteristics as the predictor variables (x).

#### Key Findings
- **Model Improvement**: The inclusion of additional predictors significantly enhanced the model's explanatory power, evidenced by a higher R^2 value.
- **Influence of Language Features**: High negative correlation coefficients for new sounds and features suggest that unfamiliar phonetic and linguistic characteristics of a target language may result in lower speaking scores.
- **Demographic Impact**: Interestingly, the variable 'sex' showed a significant negative effect on speaking scores, indicating a gender disparity where males exhibited lower scores compared to females.
- **Model Performance**:
  - The low deviance and a Pseudo R-squared value of 0.3392 indicate moderate model accuracy, explaining approximately 34% of the variance in speaking scores.
  - Comparative analysis of model evaluation methods showed k-Fold Cross-Validation to be the most effective due to its balance of computational efficiency and accuracy, with the Test Mean Squared Error (MSE) being the lowest at 1113.2612345510613.
  
#### Model Evaluation
The k-Fold Cross-Validation method emerged as the preferred technique for model evaluation over alternatives such as Bootstrap and Out-of-Bag (OOB) error estimation due to its robustness and manageable computational demands.

#### Visualizations
To view the graphical representations of the findings, check out the images below:
- ![Average Scores](images/average.png)
- ![Relative Feature Importance](images/relative_future_importance.png)




