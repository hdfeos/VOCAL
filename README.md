## Docs:

http://develop-larc-calipso.github.io/CALIPSO_Visualization/

## Alpha Release To-Do:

* [x] Database delete option
* [x] Do not re-store imported db objects
* [x] Attributes Class and Dialog window written
* [ ] Altitute Time coordinates
  * [x] Plot coordinates
* [ ] Installer
* [x] Filtering and searching of database objects
  * [x] Filtering
  * [x] Searching
* [ ] Create doc tutorial
* [ ] Maintain shape size in respect to the plot

## Misc To-Do:

* [ ] Rewrite documentation
* [ ] Fix plot move to have fluid move motion
* [ ] Add icon for window and taskbar 
* [ ] Move .png icons to .ico's
* [ ] Add `PolygonReader` exception handling
* [ ] In-code documentation written
* [ ] Refactor `Calipso` functions
* [x] Fix `About` window in `Calipso`
* [ ] Fix draw buttons attempting to draw when menu bar is accessed causing out of range error

## Notes: 

Database finite limit could be extended with pagination, splitting the database into 'pages' that the user would need to go through. But this also introduces the fact that searching would need to pull all pages for an ample search

Py2exe can be used for building an executable, but research will need to be done into developing a setup file.
