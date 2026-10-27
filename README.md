# CSI4130

# Adaptive AI Study Assistant Using RAG and Personalized Learning

## Project Overview
This project aims to develop an AI-powered study assistant that helps students prepare for exams by generating personalized practice questions from their lecture materials.

Unlike traditional AI quiz generators, this application will use Retrieval-Augmented Generation (RAG) and adaptive learning techniques to create questions based on uploaded course materials and adjust future questions according to student performance.

## Problem Statement
Students often spend significant time creating study materials and identifying which topics they need to review. Traditional study tools typically provide the same questions regardless of a student's understanding.

This project aims to address this problem by developing an AI system that identifies students' weak areas and automatically generates targeted practice questions to improve their understanding.

## Proposed Method
The application will be developed using Python, Flask, and React.

The system will:

1. Allow students to upload lecture notes in PDF format.
2. Extract and process text from uploaded documents.
3. Use Retrieval-Augmented Generation (RAG) to retrieve relevant information from the lecture materials.
4. Integrate a LLM API to generate multiple-choice practice questions and explanations.
5. Track student performance and identify topics where additional practice is needed.
6. Implement an adaptive learning algorithm that adjusts question selection and difficulty based on previous answers.

The project will also compare traditional LLM-based question generation with RAG-based generation to evaluate answer accuracy, relevance, and quality.

## Data Sources
The project will use educational materials such as lecture notes, publicly available course documents, and sample study materials.

Student quiz responses will be used to evaluate performance and test the adaptive learning system. A manually reviewed set of generated questions will be used to evaluate question quality and accuracy.

## Technologies
- **Python:** Backend development and AI processing
- **Flask:** Backend API
- **React:** User interface
- **LLM API:** AI-generated questions and explanations
- **RAG:** Retrieval of relevant lecture content
- **PyMuPDF:** PDF text extraction
- **SQLite:** Storage of questions and student performance
