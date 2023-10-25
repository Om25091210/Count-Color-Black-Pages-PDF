<!--Please do not remove this part-->
![Star Badge](https://img.shields.io/static/v1?label=%F0%9F%8C%9F&message=If%20Useful&style=style=flat&color=BC4E99)
![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)

# PDF Page Color Counter

## 🛠️ Description
This Python project provides a simple yet powerful tool for analyzing PDF documents and counting the number of black and color pages. Whether you're working on document analysis, quality control, or just curious about the composition of your PDF files, this code helps you gain insights into the document's visual characteristics.

**Key Features:**

* Easy Integration: With a few lines of code, you can integrate this functionality into your Python applications or workflows.

* PDF Expertise: Utilizing the PyMuPDF (MuPDF) library, this project efficiently processes PDF files, making it suitable for a wide range of applications.

* Color Page Detection: It accurately identifies color and black & white pages within the PDF document, providing valuable statistics.

* Use Cases: This code can be employed in various scenarios, such as document archiving, printing optimization, or content analysis.

## ⚙️ Languages or Frameworks Used
- **Python**: The primary programming language used for the project.
- **FastAPI**: A modern, fast (high-performance) web framework for building APIs with Python.
- **PyMuPDF (MuPDF)**: A lightweight and efficient PDF processing library for Python.
- **OpenCV**: Used for image analysis and processing.
- **Pillow (PIL)**: Python Imaging Library for working with images.

## 🌟 How to run
 - ### Install all the requirements
    Run `pip install -r requirements.txt` to install all the requirements.
 - ### Setup a Virtual Enviroment

   - Run this command in your terminal `python -m venv myenv`.
   - Change your directory by `cd myenv/Scripts` if on windows.
   - Activate the virtual enviroment by running this command `source activate`.
   - Move out from virtual env to your **Project Directory** by `cd..` .
   - Install the packages if not present - `uvicorn`, `fastapi`, `fitz`, `frontend`, `tools`, `opencv-python`, `pillow`, `python-multipart`, `PyMuPDF`.
   ```
   pip install uvicorn fastapi fitz frontend tools opencv-python pillow python-multipart PyMuPDF
   ```

- ###  Now Just, Run the project
   
   -Now Run the following command - `uvicorn main:app --reload`.
   -Open the localhost link on your browser and put `/docs` at your endpoint to see the fastapi docs UI.
   -Now, Click on **POST** and then **Try it out**.
   -Click on **Choose file** to select a pdf, which you want to count the number of black and color pages.
   -Click on **Execute**.


## 📺 Demo
![image](https://github.com/MBSA-INFINITY/MBSA-Forms/assets/85332648/2200ef81-57de-4619-ba33-4bed2cf31780)
![image](https://github.com/MBSA-INFINITY/MBSA-Forms/assets/85332648/ad83c91d-e140-4f4b-9b30-81b4903f1011)

## 🤖 Author

Github - [MBSA-INFINITY](https://github.com/MBSA-INFINITY)
LinkedIn - [MBSAIADITYA](https://www.linkedin.com/in/mbsaiaditya/)
Portfolio - [MBSA](https://mbsaiaditya.in/)




