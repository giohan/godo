# Godo

Godo is a simplistic Go webapp to manage your tasks.

How to use?
==================

1. `go get github.com/giohan/godo`
1. `cd $GOPATH/src/github.com/giohan/godo`
1. `cat schema.sql | sqlite3 tasks.db`
1. run `go build`
1. `./godo`
1. open [localhost:8081](http://localhost:8081)

You can change the port in the [config](https://github.com/thewhitetulip/Tasks/blob/master/config.json) file

## Features

1. Add, update, delete task.
2. Search tasks, the query is highlighted in the search results page.
3. Github flavoured markdown, which enables us for using a task list, advanced syntax highlighting and much more.
4. Supports file upload, randomizes the file name, stores the user given filename in a db and works on the randomized file name for security reasons.
5. Priorities are assigned, High = 3, medium = 2 and low = 1, sorting is done on priority descending and created date ascending.
6. Categories are supported, you can add tasks to different categories. 
1. Ability to hide a task from the timeline.
1. For a task list, shows 6 out of 8 tasks completed.
1. Single click install, just run the install.sh file.
