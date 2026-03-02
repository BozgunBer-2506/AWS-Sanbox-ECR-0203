# CloudNotes Backend - AWS ECR Deployment

This repository contains the backend for the CloudNotes application, built with **FastAPI** and **SQLAlchemy**. It is designed to be containerized with **Docker** and deployed to **AWS Cloud**.

## 🚀 Features

- **FastAPI**: Modern, high-performance web framework for building APIs.
- **SQLAlchemy ORM**: Database management with support for SQLite (local) and PostgreSQL (RDS).
- **Dockerized**: Fully containerized environment for consistent deployment.
- **AWS Integration**: Ready to be pushed to **Amazon ECR** and deployed on **EC2** or **App Runner**.

## 🛠 Project Structure

- `main.py`: Entry point of the FastAPI application and API routes.
- `models.py`: SQLAlchemy database models.
- `schemas.py`: Pydantic models for data validation.
- `database.py`: Database connection logic.
- `Dockerfile`: Configuration for building the Docker image.

## 📦 Local Setup & Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/BozgunBer-2506/AWS-Sanbox-ECR-0203
   cd backend
   ```
