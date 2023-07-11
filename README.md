<h1 align="center"> &#127936; &nbsp; EDA Basketball &nbsp; &#127936; </h1>

<p align="center">Web app developed with Streamlit containing a simple exploratory data analysis (EDA) about NBA data.<p>
<p align="center">
    <a href="https://github.com/Vinicius999/EDA-Basketball-Streamlit#demo-app">Demo App</a> |
    <a href="https://github.com/Vinicius999/EDA-Basketball-Streamlit#run-project">Run Project</a> |
    <a href="https://github.com/Vinicius999/EDA-Basketball-Streamlit#technologies">Technologies</a> |
    <a href="https://github.com/Vinicius999/EDA-Basketball-Streamlit#data">Data</a> |
    <a href="https://github.com/Vinicius999/EDA-Basketball-Streamlit#web-app">Web App</a>
</p>

## Demo App

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://eda-basketball.streamlit.app/)



## Run Project

To install all the necessary libraries to run this project, we will use the [`requirements.txt`](https://github.com/Vinicius999/EDA-Basketball-Streamlit/blob/main/requirements.txt) file. To do this, launch the terminal, navigate to the project folder and run the following command:

```
pip install -r requirements.txt
```

After that we can run the [`main.py`](https://github.com/Vinicius999/EDA-Basketball-Streamlit/blob/main/main.py) file using the command:

```
streamlit run main.py
```



## Technologies

<p style='margin: 16px 4px 32px;'>
    <a href="https://www.python.org/" target="_blank" rel="noopener noreferrer">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Vini-python" width="40" height="40" />
    </a>
	<a href="https://streamlit.io/" target="_blank" rel="noreferrer">
        <img src="https://github.com/Vinicius999/Simple-Stock-Price/blob/main/images/streamlit-logo-1.png?raw=true" alt="Vini-streamlit" width="40" height="40" />
    </a>
</p>

## Data

- Data Source: [basketball-reference.com](https://www.basketball-reference.com/)

- Original data (2022):

  ![Original data](https://github.com/Vinicius999/EDA-Basketball-Streamlit/blob/main/images/data-image-website.png)



## Web App

<div>
    <h3>Sidebar</h3>
    <p>
	In the sidebar we have the <strong>User Input Features</strong>, where we can filter the results presented based on 3 different filters:
    <ul>
        <li>Year</li>
        <li>Team</li>
        <li>Position</li>
    </ul>
    In the demo below we can see the sidebar and how filters can be applied.
    </p>
    <img src="https://github.com/Vinicius999/EDA-Basketball-Streamlit/blob/main/images/sidebar.gif">
</div>


<div>
    <h3>Display and Download Data</h3>
    <p>
    	<p>By applying the filters, we can view the resulting data shown in a table (dataframe).</p>
	<p>
		The table with the results is interactive and we can sort the data displayed based on any of the columns in ascending or descending order. In addition, we can expand the table to a full screen view and we can also select one or several cells to copy and paste the data contained in it.
	</p>
	<p>To download the table with the filtered data, we can use the <strong>Download CSV File</strong> button.</p>
	The demo below shows the interactions with the results table, as well as how to download the table.
    </p>
    <img src="https://github.com/Vinicius999/EDA-Basketball-Streamlit/blob/main/images/table-and-download.gif">
</div>


<div>
    <h3>Intercorrelation Heatmap Button</h3>
    <p>
    	<p>In addition to the table with the filtered data, we can also visualize an intercorrelation matrix of these data graphically.</p>
    	<p>We can view this graph through the "intercorrlation heatmap" button as shown in the demonstration below.</p>
    </p>
    <img src="https://github.com/Vinicius999/EDA-Basketball-Streamlit/blob/main/images/heatmap-button.gif">
</div>


<h5 align="center"> &#128679; Projeto &#128640; em construção... &#128679; </h5>
