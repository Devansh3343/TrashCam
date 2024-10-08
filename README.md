# Real-Time Waste Classification

This project was developed by our team during **Hack The Valley 9**. We built a **Real-Time Waste Classification** application that leverages cutting-edge technologies to promote better waste management and sustainability.

## Project Overview

Our application uses **computer vision** and **object detection** models to classify waste items into three categories: **compost**, **recycling**, and **inorganic waste**. The project integrates the following components:

- **COCO SSD** and **Google Cloud Vision**: These are used for object detection and waste identification in the images provided by users.
- **Gemini API Backend**: Once the waste is identified, it is passed to the Gemini API for logical classification into the appropriate waste category.
- **NEXT.js**: The front-end framework used to create a responsive and intuitive user interface.
- **PostgreSQL** and **Prisma**: For database management, storing user scores, and maintaining a leaderboard.

## Features

- **Real-Time Waste Classification**: Users can upload images of waste items, and our system will classify them in real-time.
- **Leaderboards**: Users can track their classification scores and compete with others.
- **Interactive UI**: The front end provides a seamless user experience for waste submission and leaderboard tracking.

## Tech Stack

- **Frontend**: NEXT.js
- **Backend**: Gemini API, COCO SSD, Google Cloud Vision
- **Database**: PostgreSQL, Prisma ORM

## How It Works

1. **Image Upload**: Users upload an image of the waste they want to classify.
2. **Object Detection**: The image is analyzed using **COCO SSD** and **Google Cloud Vision** to identify the waste items.
3. **Waste Classification**: The identified waste is passed to the Gemini API, which classifies it into **compost**, **recycling**, or **inorganic waste**.
4. **Leaderboard**: Users’ classifications are recorded in the PostgreSQL database, and their scores are updated on the leaderboard.



## Access the Application

You can access the live project at [TrashCam](https://trashcam.alphastone.ai/).

## Contributing

We welcome contributions! If you'd like to help improve the project, feel free to open an issue or submit a pull request.
