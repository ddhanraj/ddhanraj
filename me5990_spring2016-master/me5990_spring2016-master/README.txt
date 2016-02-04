This repository contains the materials for ME5990
"Getting Data in the Lab." The repository is organized as 
shown in the tree below.

The "slides" folder contains the power point slides used
in this course for your reference. The "documents" folder
contains any additional course documentation not directly
related to regular homework such as the syllabus.

Homework will be assigned and submitted through the "homework"
folder. Each assignment will reside in its own folder, labelled 
"hw##" where ## is a two digit number corresponding to the assignment 
number. The assignment pdf or text file will be placed in each folder,
along with any VIs or other files needed for the assignment.

Typically, you will place your top-level VI or VIs in the
hw## folder, and, if necessary, place subVIs in a folder
labelled "subVIs." As the class progresses, you may find it 
helpful to create a  "vilib" library folder at the same 
level as hw. Place VIs that you commonly reuse in this folder.

<repo>/
|- slides/
|- documents/
|- hw/
|  |- hw01/
|  |    |- hw01.pdf
|  |    |- hw01.vi
|  |	   |- subVIs/
|  |	          |- <your subVIs here>
|  |- hw02/
|       ...
|- vilib/
      |- <your library>/
	  |             |- <your library VIs>
      |- <your second library>/
	        ...
	