# python-api-challenge

## Module 6 Challenge

### Background

Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

### Before You Begin

1. Create a new repository for this project called<img width="161" alt="Screenshot 2023-10-31 at 12 47 44 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/36b6a24e-cf06-4773-9253-bb759dc18c80">. __Do not add this homework to an existing repository.__
2. Clone the new repository to your computer.
3. Inside your local Git repository, create a directory for this assignment. Use a folder name that corresponds to the Challenges, such as __WeatherPy__.
4. Inside the folder you just created, add the files called <img width="96" alt="Screenshot 2023-10-31 at 12 52 09 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/46181c91-adc8-41b9-917d-9f2b185c30f9"> , <img width="123" alt="Screenshot 2023-10-31 at 12 54 11 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/b1d7221c-16b4-4873-a423-69ad2a998e8d">, and <img width="131" alt="Screenshot 2023-10-31 at 12 54 37 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/558de8a8-e6ea-458c-bb73-73611879d920"> that you will find in the starter code ZIP file provided. These will be the main scripts to run for each analysis.
5. Before you push your changes to GitHub, add a .gitignore file.


### Add a .gitignore File

For this assignment, you will need to add a <img width="89" alt="Screenshot 2023-10-31 at 12 56 56 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/cda383d0-018b-4c68-bedb-05c2d98b830d"> file to your repo. Doing so will prevent the <img width="96" alt="Screenshot 2023-10-31 at 12 52 09 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/ebffd679-178b-46d5-bc3b-5040c5895354"> file that contains your API key from being shared with the public. If you skip this step, anyone using GitHub could copy and use your API key, and you may incur charges as a result.

To get started, type<img width="88" alt="Screenshot 2023-10-31 at 1 05 29 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/ae73839e-cb11-4e72-a038-146afbc9870b"> in the command line to see a list of all the untracked files that you have created so far.

To add only the <img width="123" alt="Screenshot 2023-10-31 at 12 54 11 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/9ae92093-6cd2-4acf-9c10-6c5fe298131d"> file to GitHub, for example, type <img width="64" alt="Screenshot 2023-10-31 at 12 59 24 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/fca4777a-86b6-40df-8977-47c66f1b3e94"> <img width="123" alt="Screenshot 2023-10-31 at 12 54 11 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/a989b774-f9fb-4823-863e-8851ee1635bf">. Keep in mind that you would have to add each file individually when adding or updating a file. A more efficient solution is to add all of the files that you don't want to track to the<img width="89" alt="Screenshot 2023-10-31 at 12 56 56 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/8447cd6e-a278-4cfc-bdaf-abd9f2a684be"> file.

Before adding your files to GitHub, add <img width="96" alt="Screenshot 2023-10-31 at 12 52 09 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/f9d8bc7f-96a2-472a-9f66-53aea987d16d"> to the <img width="89" alt="Screenshot 2023-10-31 at 12 56 56 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/4a2358a9-2f7b-4d54-9340-0178734b8550"> file by following these steps:

  1. Open your <img width="159" alt="Screenshot 2023-10-31 at 12 58 43 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/b8fa29cd-ae09-4383-b2ac-591725d0a38f"> GitHub folder in VS Code.
  2. Open the <img width="89" alt="Screenshot 2023-10-31 at 12 56 56 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/dfa829d7-7402-4fb6-b485-b164f8075da9"> file and type the following code on the first line:
  <img width="570" alt="Screenshot 2023-10-31 at 1 14 55 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/a6319341-7f62-49b0-9ebb-b1d03adb1019">
  
  3. In the command line, type <img width="85" alt="Screenshot 2023-10-31 at 1 22 33 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/1e78a1d2-68c5-4bb5-9f65-a2fb3d3606e2"> and press Enter. The output should indicate that the <img width="89" alt="Screenshot 2023-10-31 at 12 56 56 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/2a6f33ba-a0b9-4dda-a1a1-eb211dd34e96"> file has been modified and the <img width="96" alt="Screenshot 2023-10-31 at 12 52 09 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/25a2557c-042c-4dfd-946b-1d6e9dbf3f67"> file is untracked.
  4. Use <img width="64" alt="Screenshot 2023-10-31 at 12 59 24 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/828841a6-f9d8-4dce-a592-dbaac07774f6">, <img width="87" alt="Screenshot 2023-10-31 at 1 07 34 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/501649fb-aec9-4a93-9bab-6e3752a3175e"> and <img width="75" alt="Screenshot 2023-10-31 at 1 22 57 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/cdaeb370-615c-46af-932a-7ec0f761d041"> to commit the modifications to the <img width="89" alt="Screenshot 2023-10-31 at 12 56 56 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/ea3aa8dd-ee0f-47cc-b1fc-bfca1316b964">, <img width="123" alt="Screenshot 2023-10-31 at 12 54 11 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/a5ca6940-b1b4-4718-ae7c-81e93e9f1f05"> , and <img width="131" alt="Screenshot 2023-10-31 at 12 54 37 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/aec434ff-b941-4726-b662-ad3c67dda31c"> files to GitHub.
     
On GitHub, the only new python files you should find are <img width="123" alt="Screenshot 2023-10-31 at 12 54 11 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/e694455f-4623-4cfe-b3c4-5f3cb9df0aed"> and <img width="131" alt="Screenshot 2023-10-31 at 12 54 37 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/0e77b6d0-4024-40e5-87d5-22ce410d7139"> .


### Files

Download the following files to help you get started:

[Module 6 Challenge files](https://static.bc-edx.com/data/dl-1-2/m6/lms/starter/Starter_Code.zip)  📁


### Instructions

This activity is broken down into two deliverables, WeatherPy and VacationPy.

### Part 1: WeatherPy

In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the [citipy Python library](https://pypi.python.org/pypi/citipy) 📁 , the [OpenWeatherMap API](https://openweathermap.org/api) 📁 , and your problem-solving skills to create a representative model of weather across cities.

For this part, you'll use the <img width="123" alt="Screenshot 2023-10-31 at 12 54 11 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/4b6d5793-8233-470e-b5ec-c31acfffbe67"> Jupyter notebook provided in the starter code ZIP file. The starter code will guide you through the process of using your Python coding skills to develop a solution to address the required functionalities.

To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

#### Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude

To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

#### Requirement 2: Compute Linear Regression for Each Relationship

To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values as you can see in the following image

<img width="536" alt="image" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/72e5ecb1-c385-490a-830a-cff21e37e673">

You should create the following plots:

* Northern Hemisphere: Temperature vs. Latitude
* Southern Hemisphere: Temperature vs. Latitude
* Northern Hemisphere: Humidity vs. Latitude
* Southern Hemisphere: Humidity vs. Latitude
* Northern Hemisphere: Cloudiness vs. Latitude
* Southern Hemisphere: Cloudiness vs. Latitude
* Northern Hemisphere: Wind Speed vs. Latitude
* Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.


### Part 2: VacationPy

In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

To succeed on this deliverable of the assignment, open the <img width="131" alt="Screenshot 2023-10-31 at 12 54 37 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/7a3af973-f49d-4055-b070-12ac3093b984"> starter code and complete the following steps:

  1. Create a map that displays a point for every city in the <img width="105" alt="Screenshot 2023-10-31 at 1 30 40 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/f2a6b906-889d-4755-abfb-791e563803af"> DataFrame as shown in the following image. The size of the point should be the humidity in each city.

![image](https://github.com/wsylliac/python-api-challenge/assets/140991773/6305f029-12ab-4827-a178-317bdaa1b119)

  2. Narrow down the<img width="105" alt="Screenshot 2023-10-31 at 1 30 40 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/4acc560b-0203-460a-9a16-3f2fa73091ec"> DataFrame to find your ideal weather condition. For example:
      
      * A max temperature lower than 27 degrees but higher than 21
      * Wind speed less than 4.5 m/s
      * Zero cloudiness

<img width="105" alt="Screenshot 2023-10-31 at 1 32 04 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/6d054477-c3c0-4866-a96e-4658ee47b560">Feel free to adjust your specifications but make sure to set a reasonable limit to the number of rows returned by your API requests.



    3. Create a new DataFrame called <img width="72" alt="Screenshot 2023-10-31 at 1 32 26 AM" src="https://github.com/wsylliac/python-api-challenge/assets/140991773/020e80fb-dec8-42cf-91b9-af3e59b0010f"> to store the city, country, coordinates, and humidity.
    
    4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
    
    5. Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:

![image](https://github.com/wsylliac/python-api-challenge/assets/140991773/79a3c363-1d29-4bb7-97c6-b71d5477a322)

### Hints and Considerations

* The city data that you generate is based on random coordinates and different query times, so your outputs will not be an exact match to the provided starter notebook.

* If you'd like a refresher on the geographic coordinate system, this site Links to an external site. has great information.

* Take some time to study the OpenWeatherMap API. Based on your initial study, you should be able to answer basic questions about the API: Where do you request the API key? Which Weather API in particular will you need? What URL endpoints does it expect? What JSON structure does it respond with? Before you write a line of code, you should have a crystal-clear understanding of your intended outcome.

* A starter code for citipy has been provided. However, if you're craving an extra challenge, push yourself to learn how it works by using the citipy Python library Links to an external site.. Before you try to incorporate the library in your analysis, start with simple test cases outside of your main script to confirm that you are using it correctly. Often, when introduced to a new library, learners spend hours trying to figure out errors in their code when a simple test case can save you a lot of time and frustration.

* You will need to apply your critical thinking skills to understand how and why we're recommending these tools. What is citipy used for? Why would you use it in conjunction with the OpenWeatherMap API? How would you do so?

* While building your script, pay attention to the cities you are using in your query pool. Are you covering the full range of latitudes and longitudes? Or are you choosing 500 cities from one region of the world? Even if you were a geography genius, simply listing 500 cities based on your personal selection would create a biased dataset. Try to think of ways that you can counter these selection issues.
      
     * __Hint__: Consider the full range of latitudes.

* Once you have computed the linear regression for one relationship, you will follow a similar process for all other charts. Optionally, try to create a function that will create these charts based on different parameters. (Note: there will be no extra points for completing this.)

* Remember that each coordinate will trigger a separate call to the Google API. If you're creating your own criteria to plan your vacation, try to reduce the results in your DataFrame to 10 or fewer cities.

* Ensure that your repository has regular commits and a thorough README.md file.

* Lastly, remember that this is a challenging activity. Push yourself! If you complete this task, you can safely say that you've gained a strong understanding of the core foundations of data analytics, and it will only get better from here. Good luck!












