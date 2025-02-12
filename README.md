# AutoML-Studio

## About the Project
AutoML Studio is a web application designed to simplify the process of building and deploying machine learning models. It provides the following features:
- **Dataset Upload**: Users can upload datasets in various formats (e.g., CSV, Excel).
- **Pre-processing**: Automatically handles missing values, scaling, encoding, and other data preparation tasks.
- **Model Selection**: Dynamically selects the best machine learning model based on the problem type (e.g., classification, regression, clustering).
- **Model Training**: Trains the selected model on the dataset.
- **Model Usage**: Allows users to make predictions using the trained model.
- **User Authentication**: Supports user registration, login, and secure access to the application.

This project is built with:
- **Frontend**: Next.js and Material-UI (MUI).
- **Backend**: Python (FastAPI) for API development and machine learning operations.
- **Database**: SQLite/PostgreSQL for user management and metadata storage.

---

## Project Setup

### Prerequisites
- Python 3.8+
- pip (Python package manager)
### Backend Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Vishnu-Singh/AutoML-Studio.git
   cd automl-studio/backend