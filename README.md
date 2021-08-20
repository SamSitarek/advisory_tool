# Higher Education Advisory Tool
## Executive Summary
 
        
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


    I’m always looking to learn and grow. I've found searching for my next path to continue education to be
    a bit of a maze. There are so many options of where and how to learn that I would like to provide a
    centralized tool that can truly light the path for learning.

## Data Question


    What class choices can be made towards my education goals? Advisors face this difficult question every day,
    without a strong tool to help them visualize the path for the student.

## Minimum Viable Product (MVP)


    This will be an interactive dashboard to allow someone to explore the following:

        •	the degrees/certificates offered at Belmont University

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


## Data Sources


    https://www.belmont.edu/

    https://www.lipscomb.edu/

    https://www.vanderbilt.edu/

## Known Issues and Challenges


    Will require more than a fair amount of web-scraping to collect the following:
    •	Degrees/Certifications offered
    •	Majors/Minors/Concentrations offered
    •	Requirements of each program
    •	Will have to make sure the interactivity can execute as intended


## Discovered Issues and Challenges


    The website wasn't as balanced as I would have hoped with a <div> for each section in the courses.
    It didn't break up the sections to where there was a specified <div> with a class or id that I could
    pull the course description from or the prerequisites/corequisites.

    
