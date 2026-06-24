# Blood-Test-Report-Analyzer-using-LLM
An AI-powered blood report analysis system using a two-stage LLM pipeline to extract test values, detect abnormalities, and generate health summaries with Indian diet recommendations.

Blood Work Analyzer – Streamlit App

This project is a Streamlit-based web application that analyzes blood work reports using a Large Language Model. It provides a simple health summary and an Indian diet plan based on medical test results.

Overview

The application allows users to paste a blood work report and receive:

A structured analysis of blood test values
A health summary written in simple language
A practical Indian diet plan based on the results

The system uses a two-stage LLM pipeline behind the interface.

Features
Interactive Streamlit web interface
Easy input through a text area
Real-time analysis using Google Gemini LLM
Clean separation of health summary and diet plan
Scrollable output sections for better readability
Indian diet-focused recommendations
How It Works
Stage 1: Blood Report Analysis

The model:

Extracts all medical test values
Compares them with reference ranges
Labels each value as HIGH, LOW, or NORMAL
Stage 2: Health Insights and Diet Plan

Based on the analysis, the model generates:

A simple 4–5 line health summary
An Indian diet plan with:
Foods to eat more of
Foods to avoid
Uses commonly available Indian foods like dal, rice, roti, and vegetables
User Interface

The Streamlit app contains:

Left side: Input area for pasting blood reports and an Analyze button
Right side: Output sections for:
Health Summary
Suggested Diet Plan

Both output sections are scrollable for better user experience.

Technologies Used
Python
Streamlit
LangChain
Google Gemini LLM
dotenv for environment configuration
Workflow
User pastes blood report into the app
Clicks Analyze
LLM extracts and classifies blood test values
Second LLM prompt generates health summary and diet plan
Results are displayed in structured UI format
Key Highlights
Two-stage LLM reasoning pipeline
Clean and user-friendly UI using Streamlit
Real-time medical report interpretation
Indian diet recommendations for practicality
Scrollable and well-structured output layout
Use Cases
Personal health report understanding
Educational medical AI demo
Nutrition guidance prototype
AI-powered health assistant interface
