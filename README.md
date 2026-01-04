# Resume Screening App

A Streamlit-based web application that uses Machine Learning to classify resumes into various job categories. The app supports PDF, DOCX, and TXT file formats.

## 🚀 Features

- **Multi-format Support:** Upload resumes in PDF, DOCX, or TXT format.
- **Text Cleaning:** Automatically cleans and preprocesses resume text (removes URLs, special characters, etc.).
- **Category Prediction:** Predicts the job category using a pre-trained Machine Learning model (SVM with TF-IDF vectorization).
- **Interactive UI:** Built with Streamlit for a smooth and user-friendly experience.

## 🛠️ Technologies Used

- **Python**: Core programming language.
- **Streamlit**: Web framework for building the interactive UI.
- **Scikit-learn**: Machine learning library for TF-IDF vectorization and SVM classification.
- **PyPDF2**: For extracting text from PDF files.
- **python-docx**: For extracting text from DOCX files.
- **Pickle**: For loading pre-trained models and encoders.

## 📋 Categories Supported

The model is trained to recognize various job categories, including:
- Data Science
- HR
- Advocate
- Arts
- Web Designing
- Mechanical Engineer
- Sales
- Health and fitness
- Civil Engineer
- Java Developer
- Business Analyst
- SAP Developer
- Automation Testing
- Electrical Engineering
- Operations Manager
- Python Developer
- DevOps Engineer
- Network Security Engineer
- PMO
- Database
- Hadoop
- ETL Developer
- DotNet Developer
- Blockchain
- Testing

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Resume-Screening-App
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   *Note: Ensure you have `streamlit`, `PyPDF2`, `python-docx`, `scikit-learn`, `pandas`, and `numpy` installed.*

4. **Run the application:**
   ```bash
   streamlit run app.py
   ```

## 📂 Project Structure

- `app.py`: Main Streamlit application file.
- `clf.pkl`: Pre-trained SVM model.
- `tfidf.pkl`: TF-IDF Vectorizer.
- `encoder.pkl`: Label Encoder for job categories.
- `UpdatedResumeDataSet.csv`: Dataset used for training.
- `Resume Screening with Python.ipynb`: Jupyter Notebook containing the training logic.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.