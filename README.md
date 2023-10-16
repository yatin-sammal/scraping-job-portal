# scraping-job-portal
Scarping Freshersworld Jobs Data Using Python

Freshersworld.com (A TeamLease Company) is the No.1 job Portal for freshers hiring in India with a database of over 1.5+ Crore resumes. More than 3 Lakh+ resumes are added every month from entry-level graduates across the country

The page https://www.freshersworld.com/ provides thousands of jobs in various streams. In this assignment, we will retrieve information for different job profiles using web_scraping: the process of extracting information from a website in an automated fashion using code. We will use Requests and BeautifulSoup to scrap data from this page.

The outline of this assignment is listed below:

Download the webpage using Requests
Parse the HTML source code using BeautifulSoup
Extract Company name, Job location, Apply link, Required qualification, Experience required, Last date
Compile extracted information using Python lists
Save the extracted information to a CSV file.
The CSV file which will be created will have the following format:

 job role,company name,job location,required qualification,experience required,last date,apply link
 
 eg: Data Analyst,CAW Studios,Hyderabad/Bangalore,BE/B.Tech/ME/M.Tech/CS/MS,2 Years,26 Feb 23,https://www.freshersworld.com/jobs/data-analyst-jobs-opening-in-caw-studios-at-gachibowli-bangalore-hyderabad-1667559
 ....
