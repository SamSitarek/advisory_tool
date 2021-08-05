# Advisory Tool
## Executive Summary
##### This section provides an overview to the project. It should briefly touch on the motivation, data question, data to be used, along with any known assumptions and challenges. 

    Trying to navigate a path of education in a vast world of learning can be overwhelming; where do you start?
    It can be daunting to figure out what classes would be best?
    If you select a specific course will it go toward the degree you want?
    What if you are an undeclared major because you’re considering several paths?
    What do you do?
    
    The dashboard I’m looking to create will help you visualize the path you can take and how long it will take
    to get there. It will show you which courses will satisfy each program requirement and provide clarity for
    you and your advisor.

    This tool will be heavy with information and will come from the school’s website providing the degrees
    and/or certifications they offer, the programs they offer and their course requirements, the class
    description, and the ability for the tool to accumulate a calculating list of the courses pertaining to
    that student. Being that it will be collecting a large amount of data (via web-scraping) the time to
    execute the collection is crucial.


## Motivation
##### Here you will go into more detail about why you have chosen this project.

    I’m always looking to learn and grow. I've found searching for my next path to continue education to be
    a bit of a maze. There are so many options of where and how to learn that I would like to provide a
    centralized tool that can truly light the path for learning.

## Data Question
##### Present your question. Feel free to include any research/articles that are relevant or show where others have attempted to answer this question.

    What class choices can be made towards my education goals? Advisors face this difficult question every day,
    without a strong tool to help them visualize the path for the student.

## Minimum Viable Product (MVP)

##### Define your MVP. This should be a description of what your final capstone will look like, including visualizations, how the analysis will be presented, who the intended audience is, etc.

    This will be an interactive dashboard to allow someone to explore the following:

        •	3 colleges/universities in TN (Belmont, Lipscomb and Vanderbilt)

        •	the degrees/certificates offered there

        •	the requirements of the program and the courses that will satisfy each

        •	allow it to assemble the list of courses for a student on the dashboard & assemble the credit count

        •	class description (or link to it depending on space on dashboard)

        •	have an example of how it can be ‘Save-As”ed for a student and you can open a student’s most recent
            dashboard upon their next visit to continue exploring their next steps while still having a history
            of each visit in their folder

    In order to take it further:

        •	the class time options available for the upcoming semester
  
        •	will show a location on the map where the class is on campus
  
        •	All colleges/universities in TN
   
        •	Show a location of the college/university that offers the selection
            (in event searching which colleges/universities offer a certain program)
    
        •	search bar to be able to explore class descriptions by keywords
    
        •	cost of class selection for that semester (credit cost*number of credits)
    
        •	total accumulated cost
    
        •	have it check if the prerequisites in that class have already been taken

## Schedule (through <8/20/21>)
    1.	Get the Data (<8/9/21>)
    2.	Clean & Explore the Data (<8/13/21>)
    3.	Create Presentation of your Analysis (<8/16/21>)
    -	Should be a presentation, but could include a Jupyter Notebook or dashboard (Excel/Tableau/PowerBI)
    4.	Internal demos (<8/16/21>)
    5.	Demo Day!! (<8/20/21>)

## Data Sources
##### Document the data you use and the source of that data

    https://www.belmont.edu/

    https://www.lipscomb.edu/

    https://www.vanderbilt.edu/

## Known Issues and Challenges
##### Explain any anticipated challenges with your project, and your plan for managing them. Be sure to include:
##### ●	    If you need to request data or an api key

##### ●	    Based on your data sources, known data cleaning steps

    Will require more than a fair amount of web-scraping to collect the following:
    •	Degrees/Certifications offered at each school
    •	Majors/Minors/Concentrations offered at each school
    •	Requirements of each program
    •	Will have to make sure the interactivity can execute as intended

