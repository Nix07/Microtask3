# Third Microtask
This is a mockup for the first 3 screens of the tool.

Live - https://nix07.github.io/Microtask3/index.html

Screenshots - Present in "Screens" directory

### Screen 1
Screen 1 represents the landing page of the tool. It has a navigation bar (standard in all screens). A brief introduction about the tool is provided, to inform the new users. 
There are 2 ways to enter the username :
* Directly enter the username in the first field. It will be helpful if only a few developers' contribution statistics have to be fetched.
* Click on "Browse" button and select the CSV or Excel file containing the list of usernames.

User will also have the flexibility to select the platform from which he/she wants to fetch the data, i.e a user may select GitHub only or all the three platforms.
Then the user has to enter the start date and end date for the timeframe and click on "Fetch Stats" to move to screen 2 which display statistics.

### Screen 2
Screen 2 represents the overall statistics, i.e combined stats of all entered developers. It will display a pie chart, to represent the relative contribution of developers, as well as a bar chart to represent the actual number of contributions (merged patches in this case). 
Following that, there will be a list containing the details about each entered developer. Only 10 developer's details will be shown at a time. To get the next set of 10 developers, "Load More" option can be used. The list can be sorted based on various options like merged patches, commits, assigned tasks etc, which can be selected using the dropdown. Further, there will be a search option which will be useful to the user for searching for a particular developer. 
When clicked on any developer's detail in the list, screen 3 will be opened with the contribution details of the corresponding developer. Even in the pie chart and bar chart, when the entry corresponding to a developer is clicked the same action is taken.
Each chart will have two extra options, i.e, to download the graphic or generate a sharable link. When Download option (near a graphic) is clicked, the tool will automatically start downloading the corresponding graphic. Whereas when Share option is clicked, the tool will display the sharable link in a modal. The generated list can also be download in CSV format using the corresponding download option. 

### Screen 3
Screen 3 represents the individual statistics of the selected developer. It displays 3-4 key statistics for the developer in the graphical form (this stats are randomly chosen right now, user feedback will be used to select the most important stats).
It will contain at most 3 lists, each corresponding to the platform selected by the user in screen 1. Each list will consist of individual contributions made by the developer on that platform. When clicked on list entries, the tool will redirect the user to that particular contribution's webpage. Load More, Download and Share options are used for the same purpose as in screen 2.
