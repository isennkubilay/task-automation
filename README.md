## Taskfile

Taskfile is a task runner or build tool. A task runner is a tool that automates repetitive tasks in software development. A build tool, on the other hand, is a programming utility that automates the creation of executable applications from source code.

Taskfile aims to be simpler and easier to use than other similar tools, such as GNU Make. GNU Make is a widely used tool for controlling the generation of executables and other non-source files of a program from the program's source files.

In summary, Taskfile is a tool that helps developers automate tasks and build applications more efficiently. 

[taskfile](https://taskfile.dev/)


In the context of Taskfile, a `Taskfile.yml` is used to define tasks that can be run. Each task can have a series of commands that are run when the task is called. I seperated task files for devops process for examples docker for **DockerTasks.yml**, helm for **HelmTasks.yml**, System services for **SystemdTasks.yml** and Taskfile.yml for all include tasks. You can create an .env file in the application's root directory that contains key/value pairs defining the project's required environment variables.