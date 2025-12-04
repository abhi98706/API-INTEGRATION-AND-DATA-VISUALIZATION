# API-INTEGRATION-AND-DATA-VISUALIZATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: ABHIJIT DAS

*INTERN ID*: CT06DR1737

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*

The task of API integration and data visualization involves three major phases: collecting data from an external source using an API, processing that data to make it usable, and finally visualizing it to understand patterns or trends. In this project, the OpenWeatherMap API is used to gather real-time weather forecast data, which is then processed using Python and visualized using libraries such as Matplotlib or Seaborn. This workflow demonstrates how modern applications handle real-time data and transform it into meaningful insights.

1. What is API Integration?
An API (Application Programming Interface) acts as a bridge that allows communication between two different systems. In this task, Python communicates with the OpenWeatherMap server to request specific weather information. You build a URL that contains your API key, the city name, and the desired weather forecast endpoint. When the request is sent using the requests library, the server processes it and sends back a response in JSON format. JSON (JavaScript Object Notation) is a light, readable data format commonly used for exchanging data between servers and applications. The API response contains various weather details such as temperature, humidity, wind speed, pressure, weather conditions, and timestamps. Before the program proceeds, it checks if the API has returned a successful response (status code 200). If there is an error—like an invalid API key or incorrect city name—the code prints the error message and stops execution. This is an important step because real-world applications must always handle errors properly.

2. Data Processing Using Python and Pandas
Once the weather data is successfully fetched, the next step is data processing. The JSON response is nested and not immediately suitable for analysis. Here, the pandas library plays a crucial role. Pandas is widely used in data science because it can convert raw, unorganized data into clean and structured tables called DataFrames. A DataFrame is similar to an Excel sheet with rows and columns. By selecting the required fields from the JSON response, such as date-time (dt_txt), temperature, humidity, and weather description, the program organizes these values into a DataFrame. It also converts the date-time strings into proper Python datetime objects, making them easier to sort, filter, or plot on graphs. Data cleaning is important because API responses may include extra information that is not needed for visualization. The use of pandas ensures the data is consistent, well-structured, and ready for visual representation. This step mirrors the real-world data preprocessing stage used in analytics, machine learning, and reporting systems.

3. Data Visualization Using Matplotlib or Seaborn
After preparing the data, the final stage is visualization. Visual representation of data helps users quickly understand trends, patterns, and variations that may not be obvious from raw numbers. In this project, libraries like Matplotlib or Seaborn are used to create line graphs or other types of charts. Matplotlib is a powerful plotting library that allows complete control over the appearance of graphs. Seaborn, built on top of Matplotlib, provides more visually appealing and modern charts with minimal code. With these tools, the program plots temperature and humidity against time. The x-axis represents the forecast date-time, while the y-axis shows the temperature or humidity values. These graphs help in observing how weather conditions change over time—whether temperature is rising, falling, or staying constant.

4. Purpose and Importance of the Task
The entire task demonstrates a complete workflow commonly used in data-driven applications. It shows how real-time data can be fetched from external sources, cleaned, structured, and visualized. This skillset is essential in fields like software development, data analytics, machine learning, IoT, and scientific research. The project also builds an understanding of how backend systems communicate with online services and how visualizations help interpret complex datasets. Overall, the task combines programming, data handling, and analytical thinking, making it a valuable exercise in practical data science and application development.

*OUTPUT*

<img width="1201" height="571" alt="Image" src="https://github.com/user-attachments/assets/7759463d-b92d-4b12-9bd2-5225a1c535a5" />
