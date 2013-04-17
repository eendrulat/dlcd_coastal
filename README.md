#Coastal Zone Finder	

This is a simple application that geocodes addresses, Township/Range/Section identifiers, and GNIS Places, focuses on the found location, and visually informs the user whether the location is within the Coastal Zone Boundary.


[View it live](http://htmlpreview.github.io/?https://github.com/eendrulat/dlcd_coastal/blob/master/index.html)

![App](https://github.com/eendrulat/dlcd_coastal/blob/master/app.JPG)

## Features
* Includes two main pages: simple search page (leg-search.html) and main map interface (leg-districts.html)
* Simple search page contains a single line address search bar. Passes address to leg-districts.html
* Main legislative district page will focus on the appropriate legislative district by parameters passed through the URL: 1) from the leg-search page (?addr=), 2) for a specific district, e.g. Congressional district 5 (?dist=5&disttype=c), or 3) a latitude and longitude (?longitude=-123&latitude=45)
* Main legislative district page also allows searching by address, or interactively selecting districts from the map.

## Project Details

* ArcGIS Javascript API, v. 3.3
* Application was developed by Erik Endrulat (Oregon GEO)

## Resources


## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Anyone and everyone is welcome to contribute. 

## Licensing
Copyright 2013 State of Oregon

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt]( https://raw.github.com/eendrulat/repo-template/master/license.txt) file.

[](This is how you hide something in your README.md)
