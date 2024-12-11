# Ontology Requirements Specification Document (ORS-D)

## 1. Introduction

### 1.1 Objective
This document describes the necessary requirements for the development of an ontology focused on affective computing in education, aiming to model interactions between students, teachers, digital learning objects, and students' emotions. The ontology aims to adapt learning activities based on students' emotional states, monitor their emotions during the educational process, and provide emotional feedback.

### 1.2 Scope
The scope of the ontology includes:
- The modeling of concepts and relationships in the context of education and affective computing.
- The adaptation of learning activities based on the emotions captured from students.
- Providing emotional feedback to students based on their interactions with the system.

## 2. Functional Requirements

The functional requirements of the ontology are formulated as competency questions. These questions must be answered by the ontology modeling process. Below are the main competency questions the ontology needs to answer:

### 2.1 Competency Questions

#### 2.1.1 What is the role of a Teacher in the teaching process using Digital Learning Objects?
The ontology must model the concept of **Teacher** and how they use the **DigitalLearningObject** to teach and interact with students. This question is answered by an association between **Teacher** and **DigitalLearningObject**.

#### 2.1.2 How does a student's emotion affect their interaction with learning activities?
The ontology needs to describe how students' emotions (**Emotion**) influence the adaptation of educational activities (**Activity**) through the **DigitalLearningObject**. This question is answered by modeling the association **adaptActivitiesBasedOnEmotion**, which links **Emotion** to **Activity**.

#### 2.1.3 How are students' emotions captured and associated with learning?
The ontology must include mechanisms for modeling the capture of students' emotions, represented by the association **capturesEmotionFrom**, which relates **DigitalLearningObject** to **Student** and **Emotion**.

#### 2.1.4 What is the relationship between students and emotional feedback during the learning process?
The ontology must model the relationship between the **EmotionDetectionSystem** and the **SoftwareWeb**, which is the process of providing emotional feedback through the association **providesEmotionFeedbackTo**.

### 2.2 Expected Responses in the Modeling Process
The modeling process should answer these questions using the definition of entities, relationships, roles, and stereotypes as core elements to represent:
- The dynamic adaptation of educational content based on students' emotions.
- The interaction between students and teachers through digital learning objects.
- The continuous monitoring of students' emotions during the teaching process and the emotional feedback generated.

## 3. Non-Functional Requirements

Non-functional requirements are essential for the application, use, and dissemination of the ontology, covering technical and organizational aspects.

### 3.1 Ontology Publication Languages
The ontology will be published using **OWL (Web Ontology Language)**, a standard format for representing ontologies on the web. The ontology may be complemented with **OWLDoc** to provide human-readable documentation.

### 3.2 Availability of Additional Documentation
Additional documentation will be available on platforms such as **GitHub**, allowing collaboration, version control, and contributions from the community.

### 3.3 Ease of Use and Adoption
The ontology will be structured in a way that is intuitive and easy to understand for educational system developers, affective computing researchers, and educators. The ontology will be designed for easy integration with other existing educational ontologies and learning tools. The **GitHub** platform will allow the community to contribute to the ontology's evolution, increasing its acceptance and practical application.

## 4. Conclusion
This Ontology Requirements Specification Document (ORS-D) outlines the functional and non-functional requirements necessary for creating an ontology focused on affective computing in the educational context. The ontology will enable the adaptation of learning activities based on students' emotions, the capture of emotions during the educational process, and the provision of emotional feedback.

The implementation of this ontology will help build more dynamic educational systems that are sensitive to students' emotional states, promoting more personalized and effective learning.
