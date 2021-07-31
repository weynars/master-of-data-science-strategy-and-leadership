Source: https://www.practicaldatascience.org/html/exercises/Exercise_CommandLine_1_Basics.html

**1. Download the data**
`curl -LJO https://https://github.com/nickeubank/MIDS_Data/raw/master/NYC_311_ServiceRequests/NYC_311calls_2018.zip`

**2. Unzip the file**
`unzip NYC_311calls_2018.zip`

**3. Navigate to the folder**
`cd NYC_311calls_2018`

**4. Copy the Thursday and Friday files to new folder**
`cp raw\ data/*_Thu* thursdays_and_fridays`
`cp raw\ data/*_Fri* thursdays_and_fridays`