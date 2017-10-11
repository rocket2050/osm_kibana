1. Must check is Nginx is already installed or not.
2. Packages must be installed in a single task.
3. Use handlers to start/stop service.
4. Messages must be proper for each task.
5. Copying the template will replace the already existing file so there is no need of removing the file.
6. Task messages in the handler file must be separated, currently having same message so it won't work.
7. README.md must to more elaborated to run the role.
