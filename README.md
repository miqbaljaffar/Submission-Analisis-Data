# Submission Dicoding "Belajar Analisis Data dengan Python" Bangkit 2024

## Deskripsi

Submission ini bertujuan untuk menganalisis data E-Commerce Public Dataset sebagai bagian dari course program Bangkit 2024.

## Struktur Direktori

- **/Dataset**: Berisi file data dalam format .csv yang digunakan untuk analisis.
- **/Dashboard**: Berisi file `app.py` yang digunakan untuk membuat dashboard hasil analisis data.
- **Notebook.ipynb**: File Jupyter Notebook yang digunakan untuk melakukan analisis data.

## Setup Environment

Untuk menjalankan proyek ini di Google Colab dan Streamlit, ikuti langkah-langkah berikut:

1. **Mount Google Drive**:
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```

2. **Install Streamlit**:
    ```bash
    !pip install streamlit -q
    ```

3. **Start Streamlit**:
    ```bash
    !wget -q -O - ipv4.icanhazip.com
    !streamlit run app.py & npx localtunnel --port 8501
    ```

Untuk tutorial lebih lanjut, Anda dapat mengunjungi [video tutorial ini](https://youtu.be/ZZsyxIWdCko?si=kesEvi7940SQK2xq).
