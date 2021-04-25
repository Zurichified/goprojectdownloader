downloadProjects.py

This is the downloader script for the Go projects.
Usage:

1-You need a "project;commit" structured .csv file for this tool. Create yours using ";" as delimiter, listing projects with their commits line by line. This repo has an example file with 228 entries.
  
2-run downloader and specify a path to download projects (this will automatically create GOPATH while downloading)
	$ python downloadProjects "place_to_download"
	you can use ./ if you want to download projects in the same folder

3-it will download projects and will give an output as "project_commit_place.csv" for Prophunt to iterate projects and extract source code features.