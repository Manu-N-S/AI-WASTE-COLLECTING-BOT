# AI Waste Collecting Bot

## DEMO IMAGES:
![Screenshot 2024-06-25 134401](https://github.com/Manu-N-S/AI-WASTE-COLLECTING-BOT/assets/98375679/dd5438d4-1167-4fa5-9442-744b4402cef3)


## DEMO VIDEO
link:
https://github.com/Manu-N-S/AI-WASTE-COLLECTING-BOT/assets/98375679/c9f3daea-7389-41ca-bc06-68f520831129

## Working Flow
![FLow](https://github.com/Manu-N-S/AI-WASTE-COLLECTING-BOT/assets/98375679/8247179a-1f1d-4253-b48c-45dadba0737e)

## Circuit Diagram
![circuit](https://github.com/Manu-N-S/AI-WASTE-COLLECTING-BOT/assets/98375679/92a099d4-b48c-4ef3-bf6f-31504ead87a9)

## Overview

The AI Waste Collecting Bot is an innovative project that utilizes computer vision algorithms and robotics to automate waste collection and segregation. This bot is equipped with a custom-trained YOLOv5 object detection model to identify waste objects in its vicinity. It then uses robotic arms to automatically pick up the waste and segregate it into categories such as paper, plastic, metallic, and unknown.

## Key Components

- **YOLOv5 Object Detection:** Custom-trained YOLOv5 model for real-time waste object detection.
- **Raspberry Pi:** Embedded system for controlling the bot's operations and processing the detected objects.
- **OpenCV:** Library for image processing and interfacing with the camera module.
- **Robotic Arms:** Mechanism for picking up waste objects and segregating them based on categories.

## Features

- **Real-time Object Detection:** Utilizes YOLOv5 for accurate and efficient waste object detection.
- **Automated Waste Collection:** Robotic arms automatically pick up detected waste objects.
- **Segregation:** Waste objects are segregated into categories such as paper, plastic, metallic, and unknown.
- **User Interface:** Provides a user-friendly interface for monitoring bot operations and controlling manual interventions.

## Installation

To set up the AI Waste Collecting Bot, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ai-waste-collecting-bot.git
   ```

2. Set up the Raspberry Pi:
   
   - Install required dependencies and libraries.
   - Connect peripherals such as camera module, robotic arms, and motor drivers.

3. Install Python dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Configure the environment:
   
   - Set up YOLOv5 model weights and configurations.
   - Configure OpenCV settings for camera interfacing.

5. Run the application:

   ```bash
   python main.py
   ```

## Usage

1. Start the AI Waste Collecting Bot application.
2. The bot will continuously scan its surroundings for waste objects using the camera module.
3. When a waste object is detected, the bot's robotic arms will pick it up and segregate it based on its category.
4. Monitor the bot's operations through the user interface and intervene manually if required.

## Customization

- **Training YOLOv5 Model:** Customize and train the YOLOv5 model for detecting specific types of waste objects.
- **Adding Segregation Categories:** Modify the segregation process to accommodate additional waste categories.
- **Enhancing Robotic Arms:** Integrate advanced robotic mechanisms for improved waste collection and segregation efficiency.

## Contributing

Contributions are welcome! If you'd like to contribute to the AI Waste Collecting Bot project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the YOLOv5 team for their outstanding object detection framework.
- OpenCV library for providing essential tools for image processing and computer vision.
- Raspberry Pi community for their continuous support and development of embedded systems.
