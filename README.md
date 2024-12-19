Signature Work Portfolio

By Nahom Woldehawariat

								Introduction

 	This portfolio highlights three distinct projects that reflect my journey as a computer science student while addressing real-world challenges.

Over my time at St Thomas as a double major in Computer Science and Operations & Supply Chain Managment, I have had the chance to do many different types of research and projects. Utilizing my computer science knowledge and I have done project in Coffee logistics research, using R and Python to create cool visuals to understand supply chain. I participated in Center for Applied Mathematics summer research were I used my computer science knowledge to create tools to advance research in Biology. In the process learning Cuda programing and how to utilize GPU in computation. The third project was just a small web project in creating a website to track course work for my database class. This portfolio highlights three distinct projects that reflect my journey as a computer science student while addressing real-world challenges. Each project demonstrates my technical and collaborative skills and showcases how my work connects to the broader mission of advancing the common good.

 Some of these project did have the collaboration of different student and professor but majority of the work was done by myself. I will reflect on the projects next. 



							1. Ethiopian Coffee Investment Research

									Overview

For starters, the inspiration for this project was in hopes to understand what is going on in the biggest industry of my home country. My background and supply chain and computer science motivated me to create an understanding of what is actually going on; how it can be improved upon; and different ways we can apply computer science and supply chain into the industry.This research examines the Ethiopian coffee market and aims to provide actionable insights for investors, particularly the Ethiopian diaspora. Coffee is Ethiopia’s largest export, but a lack of accessible market data creates barriers to investment. My research addresses these challenges by collecting and analyzing data to guide investment strategies. Also looking into what other data 

Well, I did engage in different data analytics using R code, and some visualization was mostly focused on industry insights and understanding what the current environment looks like. Here are the techniques I've used in this process:

								Technical Highlights

								     Data Analysis

The cornerstone of this research was analyzing data from the Ethiopian Commodity Exchange (ECX) and USDA reports. Using R programming, I conducted a comprehensive analysis that included:
	•	Time-Series Analysis: Examined trends in coffee prices over a seven-year period (2013–2019) to identify seasonal patterns, long-term price movements, and market anomalies. This analysis revealed consistent growth in coffee prices with occasional dips linked to geopolitical or economic factors.
	•	Descriptive Statistics: Summarized key metrics, such as average prices, price variability, and regional differences in coffee production and sales. These insights helped highlight which regions and warehouses consistently performed better and offered the most potential for investment.
	•	Price Trend Forecasting: Built predictive models to estimate future price movements based on historical data. This technique identified likely increases in coffee prices due to growing demand in international markets, particularly from Germany, the United States, and Japan.

								Visualizations

I created a series of visualizations just using R code to create time line plots and so on:
	•	Trend Charts: Illustrated the monthly and yearly changes in coffee prices across various warehouses, showcasing high-performing regions like Jimma and Sidama.
	•	Regional Performance Maps: Mapped warehouse locations and linked them to their average closing prices, helping investors visualize areas with higher profitability and investment potential.
	•	Comparative Analysis: Created bar charts comparing coffee grading and price differences based on defect levels, enabling deeper insights into quality-price relationships.

These visual were in an effort to create an easy understanding of the industry using different variable and factors. 

								Outcome

The research proposes the development of an open-source platform that consolidates market data and insights for Ethiopian coffee and different commodities that have investment potential. This platform aims to address the lack of accessible and reliable market data for Ethiopian coffee, empowering investors with tools and insights to make strategic decisions.
Key features of this platform would include:
	•	Interactive Dashboards: Allowing users to explore trends, regional performance, and investment opportunities through user-friendly tools.
	•	Investment Guides: Providing actionable recommendations tailored to diasporas looking to invest in Ethiopia.
	•	Community Contributions: Enabling users to add or validate data, fostering a collaborative ecosystem for informed decision-making.




							2. Personal Tracker Database Project

Overview

In a team-based effort, we developed a personal tracker app for students and professionals to manage courses, assignments, and reminders. The project utilized Flask for back-end development and SQLite for database management. This project was done just as extra credit to demonstrate our ability to use databases and pull from them and make something useful. We coordinated meetings outside of class time to work on the project as a team. Sometimes we met in person, other times we met over Teams. We used Python, HTML, CSS, and the Flask framework to build our interface. We set up routes linked to methods with our desired functionality like viewing and adding courses, exams, assignments, resources, and reminders. We had template HTML pages for each of these entities, with some of them having forms through which new data could be entered into the database through the interface. 


Features
	•	Add and view courses, exams, and assignments through a user-friendly interface.
	•	Interactive forms to enter data into the database, with seamless updates via Flask routes.
	•	Using CSS and HTML to create an interface.

								Technical Highlights

This project revolved around creating a personal tracker application using Python, Flask, and SQLite. It was designed to help users manage their academic and personal tasks with efficiency and ease.
Flask-Based Application Development:
Leveraged Flask to build a back-end for the application. Key components included:
	•	Implemented routes for creating, reading, updating, and deleting tasks such as courses, exams, and assignments.
 	•	This was also an opportunity to use frameworks like flashk and Django in the development of this tool.	
	•	Blueprints and Modular Design: Organized the application into Blueprints for better scalability and maintainability.
	•	Database Models: Designed and implemented database schemas using Flask-SQLAlchemy and did ORM classes using python to handle relationships between tasks, users, and reminders.
	
Built the front-end using HTML and CSS for a seamless user experience:
	•	Created interactive forms that allow users to input and update data directly into the database.
	•	Styled the application with CSS to ensure usability across different browser, even though that was not a requirement.
	•	Incorporated features such as a University of St. Thomas theme like purple and white pages.


									Impact
This project was just a way for us to actually test our skills and database management, web creation and a small but creative way. We were able to spend about a day in creating the friend and then back in interaction between the database and just have an overall understanding of how a tool like this is developed using different frameworks. In our process of trying to develop this, we gain skills in using different frameworks understanding what is like to debug and work with databases. and have a simple understanding of how different HTML and CSS code interacts with database systems. Building this tool highlighted the importance of collaborative problem-solving and iterative development. 








							3. Meadowlark Simulation in Computational Biology

Overview

I have been working on extending this computational model to a specific question: How will two different signaling traits (song and feather colors) each evolve to solve two different problems meadowlarks face? How will the two species of meadowlarks evolve to use each signaling trait to determine? Who they can potentially mate with, and who can they share territories with?  So, through coding and model analyses, I will generate hypotheses about biological evolution in Eastern and western meadowlark. This model is a part of the bigger ACD model that we are working with. This research gave me a chance to use new and different coding languages like Cuda. Utilize GPU processing power in a scientific analysis. Working on a project that's mainly focused on developing new ideas and using new tools to understand a very large and broad topic required extensive computing power.


								Technical Highlights

It combines advanced computational techniques with biological insights.
	•	CUDA/C++ Implementation:
Developed a highly parallelized simulation model using CUDA and C++ to explore the evolution of traits such as song type and feather color in meadowlarks. Key contributions include:
	•	Territorial Interaction Functor:
Simulated complex interactions based on recognition phenotypes and fighting abilities. The functor calculates probabilities of recognition and success in territorial disputes using:
	•	Bivariate Normal Distributions: Modeled the relationship between two signaling traits (e.g., song and feather color) to predict recognition probabilities.
	•	Bernoulli Distributions: Simulated success/failure outcomes in interactions based on calculated probabilities.
	•	Configuration File Generator:
Developed a configuration file framework to define simulation parameters such as genetic traits, environmental factors, and replicates.
	•	Parallel Processing:
Utilized NVIDIA GPUs to accelerate computations, making large-scale simulations feasible. This allowed the model to process multiple scenarios simultaneously, offering deeper insights into evolutionary dynamics.
	•	Biological Relevance:
Integrated real-world data into the model to simulate how meadowlarks use distinct traits for mating and territorial defense. The analysis provides hypotheses about the evolutionary pressures shaping these behaviors.


									Impact
Impact on skills:
				Overall, this impact this has on my overall experience with working in different backgrounds with my computer science skills, using it in scientific concepts and learning how to use a Linux environment, and working consistently on the terminal has been huge and beneficial.
Advancing Scientific Understanding:
				This project contributes to evolutionary biology by offering a computational framework to study character displacement. It helps researchers understand how species adapt signaling traits to resolve conflicts and avoid hybridization. This project has been in the works for about 10 years by Professor Okamoto and being able to contribute to this work has been a pleasure.
Conservation Applications:
				Insights from this research can inform conservation strategies by identifying key traits that maintain species boundaries and biodiversity.
Showcasing Computational Power:
				By leveraging GPU parallelization, this project demonstrates the potential of computational models to solve complex biological problems, bridging the gap between computer science and biology.



									Conclusion
GitHub Repository Links
Ethiopian Coffee Investment Research: https://github.com/NahifromEast/nahom/blob/main/CAM%20intro%20presentation.docx
Personal Tracker Database Project: https://github.com/NahifromEast/nahom/blob/main/FInal%20HW8.zip
Meadowlark Simulation in Computational Biology: https://github.com/NahifromEast/nahom/blob/main/Finall%20Excel%20Paper.pdf

Through these projects, I have demonstrated how technical skills can address challenges in diverse fields such as economics, education, and biology. By connecting these efforts to real-world problems, I aim to contribute to a better understanding of global issues and create solutions that promote progress and sustainability. Overall, these projects have made up my understanding of real world experience in analytics. But I was able to also use my computer science, knowledge and supply chain knowledge in my internship where I utilize some of the same concepts and driving real world decisions.












