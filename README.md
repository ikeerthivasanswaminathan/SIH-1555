# Smart India Hackathon Workshop

# Date : 20/05/2025

## Register Number : 212223220046

## Name : KEERTHIVASAN S

## Problem Title
SIH 1555: Create a Virtual Herbal Garden that provides an interactive, educational, and immersive experience to users, showcasing the diverse range of medicinal plants used in AYUSH (Ayurveda, Yoga & Naturopathy, Unani, Siddha, and Homeopathy).

## Problem Description
Background: The AYUSH sector relies heavily on medicinal plants and herbs, which form the backbone of traditional healing practices. However, physical gardens that are not accessible to everyone. A Virtual Herbal Garden will bridge this gap by offering a digital platform where users can explore, learn, and understand the significance of various medicinal plants from the comfort of their homes. Description: Participants are tasked with developing a Virtual Herbal Garden that is engaging, informative, and user-friendly. This virtual garden should include: Interactive 3D Models: Realistic 3D models of medicinal plants that users can rotate, zoom, and explore from different angles. Detailed Information: Comprehensive details about each plant, including its botanical name, common names, habitat, medicinal uses, and methods of cultivation. Multimedia Integration: High-quality images, videos, and audio descriptions to enhance the learning experience. Search and Filter Options: Advanced search functionality to easily locate specific plants and filter them based on various criteria like medicinal uses, region, and type. Virtual Tours: Guided virtual tours highlighting specific themes, such as plants for digestive health, immunity, skin care, etc. User Interaction: Features that allow users to bookmark favourite plants, take notes, and share information on social media. Expected Outcome: The expected outcome is a comprehensive Virtual Herbal Garden that serves as a valuable educational tool for students, practitioners, and enthusiasts of the AYUSH sector. This platform should make the knowledge of medicinal plants accessible to a wider audience, promoting awareness and understanding of traditional herbal practices. It should be visually appealing, informative, and interactive, providing users with an immersive experience that combines technology with traditional knowledge.

## Problem Creater's Organization
Ministry of Ayush

## Idea
To develop a gamified, AI-assisted virtual herbal ecosystem that not only showcases medicinal plants but also personalizes the learning experience for users based on their interests, health concerns, or regional language.

## Proposed Solution / Architecture Diagram

### Components:
1. Frontend: 3D interactive UI built with React + Three.js, optimized for mobile and web
2. Backend: Node.js + Express server with MongoDB for plant data storage
3. AR/VR Module: Using Unity + WebXR for immersive experiences
4. AI Chat Assistant: Built with NLP (like BERT) to answer herbal-related queries
5. Recommendation Engine: Based on user preferences and previous interactions
6. Multimedia Library: Hosted on cloud (e.g., AWS S3 or Firebase Storage)
7. Search Engine: ElasticSearch-based search and filter system

![architecture](https://github.com/user-attachments/assets/a04e7494-aab2-46c2-8c5b-c3da38302cab)

## Use Cases

1. Student Learning Tool - Students can explore medicinal plants categorized by subject (e.g., Botany, Ayurveda, Biology). Quiz and gamification features for engagement
2. Herbal Recommendation Explorer - Users can enter symptoms (e.g., “cold”, “skin rash”) to get plant suggestions with relevant usage instructions
3. Virtual Herbal Therapy Walkthroughs - Thematic virtual tours like “Immunity Boosters”, “Mental Wellness Plants”
4. Practitioner Reference Guide - AYUSH doctors and herbal practitioners can use it as a reference for plant identification and medical uses
5. Regional Explorer - Filter plants based on the user’s location to show region-specific herbs

## Technology Stack

![technologystack](https://github.com/user-attachments/assets/caa394df-d020-46b4-865e-fab1e09028a9)

## Dependencies

1. 3D Plant Models (open-source or custom created using Blender)
2. Multilingual Support (i18n libraries and Google Translate API)
3. AYUSH Knowledge Base (official data from the Ministry of AYUSH, research journals)
4. Authentication (Firebase Auth or OAuth2 for personalized experience)
5. API Integration for sharing/bookmarking (Twitter, Facebook APIs)
