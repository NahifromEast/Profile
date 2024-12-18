Signature Work Portfolio

By Nahom Woldehawariat

Introduction

	Over my time at St Thomas as a double major in Computer Science and Operations & Supply Chain Managment, I have had the chance to do many different types of research and projects. Utilizing my computer science knowledge and I have done project in Coffee logistics research, using R and Python to create cool visuals to understand supply chain. I participated in Center for Applied Mathematics summer research were I used my computer science knowledge to create tools to advance research in Biology. In the process learning Cuda programing and how to utilize GPU in computation. The third project was just a small web project in creating a website to track course work for my database class. This portfolio highlights three distinct projects that reflect my journey as a computer science student while addressing real-world challenges. Each project demonstrates my technical and collaborative skills and showcases how my work connects to the broader mission of advancing the common good.

 Some of these project did have the collaboration of different student and professor but majority of the work was done by myself. I will reflect on the projects next. 

Reflection

1. Ethiopian Coffee Investment Research

Overview

For starters, the inspiration for this project was in hopes to understand what is going on in the biggest industry of my home country. My background and supply chain and computer science motivated me to create an understanding of what is actually going on; how it can be improved upon; and different ways we can apply computer science and supply chain into the industry.This research examines the Ethiopian coffee market and aims to provide actionable insights for investors, particularly the Ethiopian diaspora. Coffee is Ethiopia’s largest export, but a lack of accessible market data creates barriers to investment. My research addresses these challenges by collecting and analyzing data to guide investment strategies.

Well, I did engage in different data analytics using R code, and some visualization was mostly focused on industry insights and understanding what the current environment looks like. Here are the techniques I've used in this process:

Technical Highlights

Data Analysis

The cornerstone of this research was analyzing data from the Ethiopian Commodity Exchange (ECX) and USDA reports. Using R programming, I conducted a comprehensive analysis that included:
	•	Time-Series Analysis: Examined trends in coffee prices over a seven-year period (2013–2019) to identify seasonal patterns, long-term price movements, and market anomalies. This analysis revealed consistent growth in coffee prices with occasional dips linked to geopolitical or economic factors.
	•	Descriptive Statistics: Summarized key metrics, such as average prices, price variability, and regional differences in coffee production and sales. These insights helped highlight which regions and warehouses consistently performed better and offered the most potential for investment.
	•	Price Trend Forecasting: Built predictive models to estimate future price movements based on historical data. This technique identified likely increases in coffee prices due to growing demand in international markets, particularly from Germany, the United States, and Japan.

Visualizations

To make the data actionable and comprehensible, I created a series of visualizations:
	•	Trend Charts: Illustrated the monthly and yearly changes in coffee prices across various warehouses, showcasing high-performing regions like Jimma and Sidama.
	•	Regional Performance Maps: Mapped warehouse locations and linked them to their average closing prices, helping investors visualize areas with higher profitability and investment potential.
	•	Comparative Analysis: Created bar charts comparing coffee grading and price differences based on defect levels, enabling deeper insights into quality-price relationships.

These visualizations not only made the data accessible to stakeholders but also provided clear, evidence-based guidance for potential investors.

Outcome

The research proposes the development of an open-source platform that consolidates market data and insights for Ethiopian coffee. Key features of this platform would include:
	•	Interactive Dashboards: Allowing users to explore trends, regional performance, and investment opportunities through user-friendly tools.
	•	Investment Guides: Providing actionable recommendations tailored to diasporas looking to invest in Ethiopia.
	•	Community Contributions: Enabling users to add or validate data, fostering a collaborative ecosystem for informed decision-making.

This platform aims to address the lack of accessible and reliable market data for Ethiopian coffee, empowering investors with tools and insights to make strategic decisions.

Reflection

This project exemplifies how data science can address global challenges, promoting economic empowerment and sustainability in underrepresented communities.

2. Personal Tracker Database Project

Overview

In a team-based effort, we developed a personal tracker app for students and professionals to manage courses, assignments, and reminders. The project utilized Flask for back-end development and SQLite for database management.

Features
	•	Add and view courses, exams, and assignments through a user-friendly interface.
	•	Interactive forms to enter data into the database, with seamless updates via Flask routes.
	•	CSS enhancements for a visually appealing design.

Technical Highlights

This project revolved around creating a personal tracker application using Python, Flask, and SQLite. It was designed to help users manage their academic and personal tasks with efficiency and ease.
	•	Flask-Based Application Development:
Leveraged Flask to build a robust back-end for the application. Key components included:
	•	CRUD Operations: Implemented routes for creating, reading, updating, and deleting tasks such as courses, exams, and assignments.
	•	Blueprints and Modular Design: Organized the application into Blueprints for better scalability and maintainability.
	•	Database Models: Designed and implemented database schemas using Flask-SQLAlchemy to handle relationships between tasks, users, and reminders.
	•	Interactive User Interface:
Built the front-end using HTML and CSS for a seamless user experience:
	•	Dynamic Forms: Created interactive forms that allow users to input and update data directly into the database.
	•	Responsive Design: Styled the application with CSS to ensure usability across various devices.
	•	Custom Enhancements: Incorporated features such as a University of St. Thomas logo and polished design elements for a professional look.
	•	Debugging and Optimization:
Collaborated with ChatGPT for:
	•	Fixing issues like form validation errors and broken routes.
	•	Streamlining Flask application architecture to enhance performance.
	•	Improving the visual appeal of the interface by integrating modern design suggestions.

Impact
	•	Enhancing Productivity:
This application provides students and professionals with an easy-to-use tool for managing their academic and personal lives. It reduces stress by consolidating tasks into one organized platform.
	•	Promoting Scalability:
The modular structure of the app allows for future expansion into broader task management tools, catering to a wider audience.
	•	Fostering Learning:
Developing this project helped the team deepen their understanding of full-stack development and real-world application design, laying the groundwork for future technological innovations.

Reflection

Building this tool highlighted the importance of collaborative problem-solving and iterative development. By streamlining task management, this project enhances productivity and reduces stress, contributing to the well-being of users.

3. Meadowlark Simulation in Computational Biology

Overview

This project models the evolution of signaling traits in meadowlarks, focusing on traits like song type and feather color. These traits are critical for mating and territorial recognition, providing insights into character displacement in closely related species.

Technical Highlights

This project focuses on modeling the evolution of signaling traits in meadowlarks using GPU-accelerated computing. It combines advanced computational techniques with biological insights.
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
	•	Advancing Scientific Understanding:
This project contributes to evolutionary biology by offering a computational framework to study character displacement. It helps researchers understand how species adapt signaling traits to resolve conflicts and avoid hybridization.
	•	Conservation Applications:
Insights from this research can inform conservation strategies by identifying key traits that maintain species boundaries and biodiversity.
	•	Showcasing Computational Power:
By leveraging GPU parallelization, this project demonstrates the potential of computational models to solve complex biological problems, bridging the gap between computer science and biology.

Reflection

This project integrates computer science and biology, showcasing the potential of computational tools to address questions of ecological and evolutionary significance.


GitHub Repository Links
	•	Ethiopian Coffee Investment Research: 
	•	Personal Tracker Database Project: 
	•	Meadowlark Simulation in Computational Biology: 


 Conclusion

Through these projects, I have demonstrated how technical skills can address challenges in diverse fields such as economics, education, and biology. By connecting these efforts to real-world problems, I aim to contribute to a better understanding of global issues and create solutions that promote progress and sustainability.












