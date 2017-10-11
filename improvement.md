# Improvements

Improvements needs to be done in osm_kibana role

* Must check is Nginx is already installed or not.
* Packages must be installed in a single task.
* Use handlers to start/stop service.
* Messages must be proper for each task.
* Copying the template will replace the already existing file so there is no need of removing the file.
* Task messages in the handler file must be separated, currently having same message so it won't work.
* README.md must to more elaborated to run the role.
