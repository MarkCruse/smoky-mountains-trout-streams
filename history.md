### History of Command Line Usage
Wednesday, October 17
* mkdir assignment-01
* cd assignment-01
* touch README.md
* open README.md
* mkdir data
* git init    -- inititalize the folder assignment-01
* git status
* git add README.md      
* git status
* git commit -m "add README file"
* git status
*  At this point open Github and add a repo with no README and no .git file
* git remote add origin https://github.com/MarkCruse/assignment-01.git
* git push -u origin master
* git add data
* git status
* git commit -m "add data folder and zipped shapefiles"
* git status
* git push -u origin master
* git status
* git add README.md
* git commit -m "update README file"
* git add data
* git status
* git commit -m "add parking data  and zipped shapefiles"
* git push -u origin master
* git status
* git add README.md
* git commit -m "updates 2 README file"
* git add history.md
* git commit -m "add history.md"

history 100 >>history.md | output last 100 to history.md

2017-10-20
*  cd GRSM_FISH_DISTRO
*  ogr2ogr -f "GeoJSON" grsm_fish.json -t_srs "EPSG:4326" GRSM_FISH_DISTRO.shp
