Deployment of AI Pickle Model directly from a PC using Visual Studio Code:


Step 1: Download the following files present in the GitHub (https://github.com/NimishaKR887/streamlit.git) to a folder named ("New") in the local drive in the your personal computer.


        1.Covid_19_effects.ipynb - interactive python note book
        2.Covid_effect.csv  - Dataset
        3.Streamlit_app.py  - Steamlit code written file
        4.Covid_preprocessed_data.csv - independent data used for uploading into streamlit graphical user interface (GUI) after deployment 
        5.Decision_tree_model_covid.pkl  - Pickle model of machine learning model
        6.requirements.txt  - Required libraries to be installed.


Step 2: Open "Visual Studio Code" from Anaconda Navigator (Anaconda 3) 


Step 3: Open this folder named "New" from the Visual Studio Code. So, all the above 6 files will be displayed in the side window of the visual studio code. 


Step 4: To create the virtual environment, type the following code in the terminal: 

"conda create --name myenv python=3.9"
 
Here "myenv" can be any name as we like.

For creating virtual environment in python type in terminal:
"python -m venv myenv"



Step 5: To activate the virtual environment, type the following code in the terminal:

"conda activate myenv"

For activating virtual environment in python,if python environment is created, type in terminal:

myenv\Scripts\activate



Step 6: Enter the code "pip install -r requirements.txt" in the terminal of VScode.

Step 7: Select the file "Covid_19_effects.ipynb" from the left side. Then it will open on the tab(To open .ipynb file, you need to install Jupyter notebook in VSCode. 

Also execute "pip install numpy","pip install pandas", "pip install matplotlib", "pip install seaborn", "pip install plotly", "pip install scikit-learn" in jupyter cell.

When all the above installations completed, and "Covid_19_effects.ipynb" is opened, select "run all" from the top of the Jupyter notebook. This will generate a pickle file named "Decision_tree_model_covid.pkl". This pickle file wraps fitted data in the machine learning model. 


Step 8: Enter "streamlit run streamlit_app.py" in the terminal of VS code. 

When running the above code, a browser will open and a streamlit web app will create and the machine learning model is deployed in the browser.


Install and Uninstall NumPy:

For any case to uninstall numpy and re-install use:

pip uninstall numpy -y
pip install --no-cache-dir numpy




