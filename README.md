<p align="center"> 
  <img src="https://github.com/vithika-karan/Zomato-Restaurant-Clustering-and-Sentiment-Analysis/blob/main/image/food.png?raw=true" alt="Food Logo.png" width="280px" height="140px">
</p>
<h1 align="center"> Zomato Restaurant Clustering </h1>
<p align="center"> 
</p>
<h2>Problem Statement of Project</h2>

<p>Zomato, an Indian restaurant aggregator and food delivery platform, was established in 2008 by Deepinder Goyal and Pankaj Chaddah. It serves as a comprehensive resource, offering restaurant information, menus, and user reviews, alongside food delivery services in select cities.

India's vibrant culinary landscape, characterized by its diverse multi-cuisine offerings across numerous restaurants and hotel resorts, presents a dynamic and continuously evolving market. The increasing inclination of Indian consumers towards dining out and food delivery underscores the significant growth within this sector. This burgeoning restaurant presence nationwide served as the primary motivation for this project: to conduct an in-depth analysis of Zomato's extensive restaurant data for various Indian cities, thereby extracting valuable insights, trends, and key performance indicators within the Indian food industry.

This project specifically focuses on deriving actionable intelligence for both customers and Zomato as a company. We aim to analyze the sentiment embedded within customer reviews to draw meaningful conclusions, which will be presented through compelling visualizations. Furthermore, a key objective involves clustering Zomato restaurants into distinct segments, providing a structured view of the market. The visualization of this data is designed to facilitate instant analysis and understanding. This analytical approach directly addresses critical business cases, enabling customers to efficiently identify optimal dining options in their locality, and empowering Zomato to pinpoint areas for strategic growth and operational enhancement.

Beyond these core objectives, the dataset's rich information on cuisine and costing will enable comprehensive cost-benefit analyses. Additionally, the metadata associated with reviewers can be leveraged for advanced sentiment analysis and to identify influential critics within the industry.</p>

<h2>Overview Project Summary and Plan of Action</h2>
<p>This project conducts a comprehensive analysis of Zomato data, a prominent Indian restaurant aggregator and food delivery platform, driven by the dynamic growth of India's diverse culinary sector. The initiative aims to extract actionable insights for both customers and Zomato as a company.

The project architecture spans Exploratory Data Analysis (EDA) to understand business problems and data distributions, Data Cleaning (handling missing values and outliers), Feature Engineering (encoding and creating new features), and Pre-processing (scaling). This leads into Model Implementation, focusing on restaurant clustering using methods like K-means to segment restaurants and inform a robust recommendation system. Additionally, sentiment analysis of customer reviews will derive actionable conclusions, and critic identification will leverage reviewer metadata. The analysis also includes a cost-benefit assessment using cuisine and costing data.

Key objectives include:

Identifying optimal dining options for customers.

Pinpointing areas for Zomato's strategic growth and operational enhancement.

Understanding customer sentiment and influential critics.

The analysis utilizes core data science libraries such as Pandas, Matplotlib, Seaborn, NumPy, and Scikit-learn, with visualized insights designed for immediate comprehension.<p>

<h2> :floppy_disk: Crucial Project Files</h2>

<p>The Project include the Main Jupyter Notebook file as follows:</p>
<ul>
  <li><b>Machine_Learning_Capstone.ipynb</b> - Google Collab notebook containing data summary, exploration, visualisations, clustering and sentiment analysis.</li>
</ul>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<details>
<summary><h3>How to Run the Jupyter Notebook</h3></summary>

To explore this project's analysis and insights, you can run the provided Jupyter Notebook. Follow these steps to set up your environment and execute the notebook:

<b>1. Prerequisites:</b>

Before you begin, ensure you have the following installed:
<b>Python 3.x:</b> We recommend Python 3.8 or newer.
<b>Jupyter Notebook:</b> This is the interactive environment where the analysis is performed.
<b>Required Python Libraries:</b> The project relies on several key libraries.

<b>2. Setting Up Your Environment:</b>

It's highly recommended to use a virtual environment to manage project dependencies.

<b>Create a Virtual Environment (Optional, but Recommended):</b>
    ```bash
    python -m venv venv
    ```
<b>Activate the Virtual Environment:</b>
    <b>On Windows:</b>
        ```bash
        .\venv\Scripts\activate
        ```
    <b>On macOS/Linux:</b>
        ```bash
        source venv/bin/activate
        ```

<b>Install Required Libraries:</b>
    Navigate to the project's root directory (where `requirements.txt` is located, if you have one, or list the libraries directly).

  ```bash  
  #If you have a requirements.txt file
  pip install -r requirements.txt
  #OR, if you need to install them manually:
  pip install pandas matplotlib seaborn numpy scikit-learn notebook # Add any other libraries you used, e.g., plotly, nltk, etc.
  ```
    
<b>3. Running the Jupyter Notebook:</b>

Once your environment is set up and dependencies are installed:

<b>Navigate to the Project Directory:</b>
    Open your terminal or command prompt and change your current directory to the folder where you've downloaded/cloned this project.
    ```bash
    cd path/to/your/project/folder
    ```
<b>Launch Jupyter Notebook:</b>
    ```bash
    jupyter notebook
    ```
<b>Open the Project Notebook:</b>
    This command will open a new tab in your web browser, displaying the Jupyter Notebook interface. Navigate to and click on the main project notebook file (e.g., `Zomato_Clustering_Analysis.ipynb` or `Project_Understanding.ipynb`).

<b>4. Interacting with the Notebook:</b>

The notebook will open in your browser. You can execute cells individually by clicking on them and pressing `Shift + Enter`.
To run all cells in the notebook sequentially, go to `Cell > Run All` in the Jupyter menu.
The notebook contains detailed comments, code, and visualizations that walk you through the data loading, cleaning, feature engineering, clustering, and sentiment analysis processes.

<b>5. Deactivating the Virtual Environment (When Done):</b>

When you're finished working with the notebook, you can deactivate your virtual environment:
```bash
deactivate
```  

</details>  

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> :books: References</h2>
<ul>
  <li><p> Dr Michael J Garbade, 'K Means Clustering'. [Online].</p>
      <p>Available: https://towardsdatascience.com/understanding-k-means-clustering-in-machine-learning-6a6e67336aa1</p>
  </li>
  <li><p>Builtin.com, 'Principal Component Analysis'. [Online].</p>
      <p>Available:https://builtin.com/data-science/step-step-explanation-principal-component-analysis</p>
  </li>
  <li><p>Prashant Sharma, 'Understanding K Means'. [Online].</p>
      <p>Available: https://www.analyticsvidhya.com/blog/2021/11/understanding-k-means-clustering-in-machine-learningwith-examples/</p>
  </li>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
