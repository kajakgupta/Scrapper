
# Scrapper
# UiPath Packages scraping in RPA

# Web scraping web harvesting, or web data extraction is data scraping used for extracting data from websites.

In this example I have collected the UiPath package ID, URL, Version of the **UiPath Package** from a proxy. We can use this program when we can not find the package available in the Package Manager in UiPath or when we are not able to open Package Manager at all. 

Fresher like me can use this program to get the desired package as it was very difficult for me to find some of the required package in the UiPath for the work I was doing and this program can collectively give the list of package in the csv format.

The program will open the [proxy site](https://www.myget.org/gallery/workflow) and list the packages with their URL and version available in the page and all possible next page. 

If one is using this code to get the available package and to install it if required one if found, then we need to go to the URL followed by the package name and download it to local drive. Than open UiPath package Manager and right click on any of the nodes like Installed->All.. , Available-> All.. On click  event *Configure Sources* will pop up, point that to the directory where package is downloaded in the local. Further all the downloaded packages will appear on the UiPath package manager.
