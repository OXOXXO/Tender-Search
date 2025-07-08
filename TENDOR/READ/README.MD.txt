# INTRO #
 Normally if u go on to scrape all the private listed companies of india tenders it will take several months to do so with a huge limitational barriers of a ton and tons of website to scrape and if u scrape them all you will have to use many code functions to extarct pdf data or pdf informations you will also require a login id of a govt eVendor which is none to impossible if u just want to see active tenders available 
 and hence the need of a free open sourced Tendor-Search has come up where any one can get any tendor details free of cost.
# STEPS TO RUN #
THERE IS A FOLDER NAME 'TENDER' WHICH HAS 3 FILES - READ , RUN & COLAB
you will find this readme.md in the READ files with a ER - Relationship Diagram i have created which shows the process of how i created the Tender-Search , u have to open the er diagram in (excalidraw.com) and can read the process
RUN files - IT HAS 2 SIMPLE COLAB NOTEBOOK NAMED - pvt_tender_2.ipynb & auth_names.ipynb WHICH WHEN IMPORTED [OPEN] IN COLAB NOTEBOOK WILL WORK EFFORTLESSLY 
1. YOU HAVE TO FIRST RUN THE auth_names.ipynb file in the colab and get all the authority names of the tender website of all around the world globally. {ONLY 1 TIME WORK ; I WILL ALREADY UPLOAD THE AUTH_NAMES.TXT FILE U CAN USE THAT TO UPLOAD IN THE pvt_tender_2.ipynb  
2. NOW GO AND RUN THE SECOND MAIN FILE pvt_tender_2 IN COLAB , WHERE U CAN THEN ENTER THE auth_names.txt file and can run the other cell afterwords which when used will ask u to enter your "ngrok OAUTH TOKEN" and will go and host the file online and u can now search any tender by authority name.

# FETAURES #
1. Save Time if u only want to check any company or authority or organisation Active Tenders in 1 click 
2. Can see All Possible Active Tenders of any company if avail.
3. Filters and Rank Tendors with near today Deadline
4. Export All Tendors in Excel in a click
5. open-sourced under MIT LICENSE
# ISSUES #
1. edm or bid not properly explained or missing on some tenders
2. cant get 100% accurate data (90% accuracy i guess, meaning if there is 100 tenders than there is a chance it shows 110 tenders or 87 Tenders which infact is a big drawback)
3. Duplicate or Repetancy Of Tenders Details
4. No Direct Link to the document to see Details of eProcurement
# why and how code works ? #
- - WHY - no 1 click solution to find all public , private tenders on a single trusted webpage and a barrier of misinformation or lack of information.
  - -  HOW - scraped the tender247 website, by using there cURL i get the python code to automate requests and get data of my choice in 1 click.
# Updated Versions or Bug Fix #
 - - updated versions will come in future if theres a public demand
   - no bugs found as of 8/july/2025 will see how it goes
