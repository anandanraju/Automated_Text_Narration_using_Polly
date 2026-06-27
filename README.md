# 🎙️ Automated Text Narration Platform using AWS

A serverless cloud application that converts text into natural-sounding speech using **Amazon Polly**. The platform enables users to upload or enter text, generate high-quality audio, and download the synthesized speech in MP3 format. This project demonstrates the practical implementation of AWS serverless services and text-to-speech technology.

## 📌 Project Overview

The **Automated Text Narration Platform** leverages **Amazon Polly's neural text-to-speech** capabilities to transform written content into realistic audio. Built on a serverless AWS architecture, the application provides a scalable, cost-effective, and efficient solution for generating voice content from text files.

## 🚀 Features

* ✅ Convert text into natural-sounding speech
* 🌍 Support for multiple languages and voices
* 🎤 Neural and standard voice options
* 🎵 Generate downloadable MP3 audio files
* ☁️ Fully serverless AWS architecture
* ⚡ Fast and scalable processing
* 💻 Simple and user-friendly interface

## 🏗️ Architecture

```text
                +----------------+
                |     User       |
                +----------------+
                        |
                        ▼
               +-------------------+
               |  Upload Text File |
               +-------------------+
                        |
                        ▼
               +------------------+
               |   AWS Lambda     |
               +------------------+
                        |
                        ▼
               +------------------+
               |  Amazon Polly    |
               +------------------+
                        |
                        ▼
               +-------------------+
               | Generate MP3 File |
               +-------------------+
                        |
                        ▼
               +------------------+
               |    Amazon S3     |
               +------------------+
                        |
                        ▼
               +------------------+
               | Download Audio   |
               +------------------+

## 🛠️ AWS Services Used

| AWS Service       | Purpose                                         |
| ----------------- | ----------------------------------------------- |
| Amazon Polly      | Converts text into natural-sounding speech      |
| AWS Lambda        | Executes serverless backend logic               |
| Amazon S3         | Stores input text files and generated MP3 files |
| IAM               | Manages permissions and security                |
| Amazon CloudWatch | Logs and monitors Lambda execution              |


## 💻 Tech Stack

* Python
* Boto3
* AWS Lambda
* Amazon Polly
* Amazon S3

## ⚙️ How It Works

1. User uploads a text file or enters text through the application.
2. The request is sent to **AWS Lambda**.
3. Lambda retrieves the text content.
4. Lambda invokes **Amazon Polly** to synthesize speech.
5. Polly generates an MP3 audio stream.
6. Lambda stores the generated MP3 file in **Amazon S3**.
7. The user downloads the generated audio file.

## 🎯 Learning Outcomes

* Built a complete serverless application using AWS.
* Integrated Amazon Polly with Python using the Boto3 SDK.
* Implemented automated text-to-speech conversion.
* Managed cloud storage using Amazon S3.
* Configured IAM roles and permissions securely.
* Monitored serverless workloads using CloudWatch.
* Gained practical experience with AWS event-driven architecture.

## Deploy the Lambda function and configure:

* Amazon Polly
* Amazon S3 Buckets
* IAM Roles
* S3 Event Trigger
* API Gateway (Optional)

## 📄 License

This project is licensed under the **MIT License**.

## 👨‍💻 Author

**Anandan Raju**

If you found this project helpful, consider giving it a ⭐ on GitHub!
