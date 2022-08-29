# Philly Voting Map
Hello, I hope you are having a good day! To use this project, go here: https://colab.research.google.com/github/Yangeric96888/PhillyVotingProject/blob/master/main.ipynb

I created a project that aims to map the various polls for Philadelphia's voting polls for the 2022 election.
Besides just physically listing every spot, every poll contains information on its building accessibility and parking, if you hover over the map marker.

# Why Make This?
I created this project because there was not really one good map that has all the voting stations that also contained information on the poll's accessibility. 
I really want to contribute to my community, and I thought this project was a cool way to combine my civic engagement with my programming skills!

# How Does It Work?
Nobody is really sure... just kidding! Initially, I got all of the polling station data + locations in a spreadsheet. Then I used an online program to convert locations into coordinates (setting up the data was a bit hard!).
Using Pandas, I brought the spreadsheet info into Python. Then, I used the Python package Folium to map the polling stations using markers. For each marker, I created a popup to list the poll's accessibility/parking info using HTML!
Et voila, it finally works!

# Credit
Office of Philadelphia City Commission (https://www.philadelphiavotes.com/home/item/2111-polling-place-list-2022-primary-election.html), for providing the poll station data <br>
Geocodio, for converting locations into coordinates <br>
Folium, for providing map code <br>
Glyphicons and Bootstrap, for providing the icon used in this project <br>
You, for reading this! <br>
