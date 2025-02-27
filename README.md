# GroceryList Application

## Overview
GroceryList is a web application that helps users organize their grocery lists using AI. The application takes a grocery list (e.g., written on a whiteboard), processes it using ChatGPT, and reorganizes the items according to the layout of the user's preferred store.

## Workflow
1. Users manually define store categories/sections and their order in the store layout
2. Users take a photo of their handwritten grocery list
3. Users upload the photo to the application
4. The application sends the image to OpenAI's GPT-4o API
5. The AI organizes the grocery items according to the predefined store layout
6. The application displays the reorganized list to the user

## Technical Implementation
- **Backend**: Flask
- **Database**: SQLite with SQLAlchemy
- **Frontend**: HTML, Bootstrap for styling, JavaScript for image preview
- **AI Integration**: ChatGPT API for image recognition and list organization

## Key Features
- Category management (add, edit, delete store sections)
- Image upload and preview
- AI-powered grocery list reorganization
- Mobile-friendly responsive design

## Status
The project is a work in progress (WIP) but already implements the basic workflow of uploading an image of a grocery list and using AI to organize it according to store layout.

## Purpose
I found myself rewriting my grocery lists to match the stores layout and thought "Why not automate this?" so I decided to make a project out of it.
