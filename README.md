# Datavisualization_with_python


Data visualization is the representation of data through the use of common graphics, such as charts, plots, infographics, and even animations. These visual displays of information communicate complex data relationships and data-driven insights in a way that is easy to understand.

Data visualization is commonly used to spur idea generation across teams. They are frequently leveraged during brainstorming or Design Thinking sessions at the start of a project by supporting the collection of different perspectives and highlighting the common concerns of the collective. While these visualizations are usually unpolished and unrefined, they help set the foundation within the project to ensure that the team is aligned on the problem that they’re looking to address for key stakeholders.

Visualizing data is a crucial skill in the data science field. So we used Dashboards in python using Dash. Dash is a python framework created by Plotly for creating interactive web applications. Dash is written on the top of Flask, Plotly.js, and React.js. With Dash, you don’t have to learn HTML, CSS, and Javascript in order to create interactive dashboards; you only need python. Dash is open source, and the applications built using this framework are viewed on the web browser. 

The above .py file is an example of the implementation of the Dash. We took data from google and imported it, and we processed data and visualized it using the Dash framework in python.

To get Data set:

airline_data = pd.read_csv(
    'https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/airline_data.csv',
    encoding="ISO-8859-1",
    dtype={'Div1Airport': str, 'Div1TailNum': str,
           'Div2Airport': str, 'Div2TailNum': str})
