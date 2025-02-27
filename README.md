# GDP-By-Country
A dynamic way to visualize annual GDP% change for a given country from 1961 to 2023

This project focused on taking WorldBank GDP % Change data from 1961 to 2023 to visualize changes in a country's GDP across geography and time-frame.

# Execution
The first option is to download the files for this repository to your system and run locally.

Alternatively, you can leverage the following steps using your computer's terminal
```
git clone https://github.com/channan1/GDP-By-Country.git
````
Enter the folder with cd on your terminal
```
cd GDP-By-Country
```
If using Python, start a local server with the following:
```
python -m http.server 8000
```
Otherwise, use any other method to start your local server.

Type into your browser:
```
http://localhost:8000/GDP%20By%20Country.html
```

# Analysis

![VideoGif2](https://github.com/user-attachments/assets/ff5055ed-bb61-4271-8d14-10f2b785bdfc)

To update the map based on year, select the drop down option in the top left corner and select any year. The GDP map will update based on the GDP % change during that year. Note that some GDP's are so high or low, that they may appear as black since they exceed the color scale. A range of -30% to +30% is chosen to highlight magnitude of GDP % change on an absolute scale.
