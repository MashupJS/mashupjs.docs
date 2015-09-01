#Workflow
Here you'll find tips on how your workflow might work.

## Creating a new Mashup implementation



## Single Application Workflow (Team approach)
The Mashup can be used to build multiple applications into a single composite application or can be used to build a single application.

###To build a single application:
1 Download the zip file of the MashupJS from the following page, and unzip it.
- https://github.com/MashupJS/MashupJS

2 Copy the `app1` and `app2` folders from `Mashup.UI.App1` and `Mashup.UI.App2` to the `[root]Mashup.UI.Core/Mashup.UI.Core/src/apps/`

3 Execute your normal "new project" commands to get NPM and Bower set up.

    npm install

    bower install

4 Execute your Gulp command.  Be sure to remove the `copyFromApps` task from Gulp.  You won't need this task if your application is totally self-contained.

    Gulp

You're good to go.  Any changes made to app1 and app2 will be pulled into 

## Composite Application Workflow (Multi-team approach)
One of the benefits of using the MashupJS as a seed project is it's set up for multiple teams working in their own application and before deployment the applications are combined.

1 Download the zip file of the MashupJS from the following page, and unzip it.
- https://github.com/MashupJS/MashupJS

2 At this point you have 3 project.  One is your core and the others are sample applications.  Look at these sample applications as guides for creating your own.

The Core is configured to pull from each application so when executing the `Mashup.UI.Core` project you'll see `app1` and `app2` menu items.  Gulp executes tasks to build a single menu json and combines the routes.

3 Execute yourGo to the root of the `Mashup.UI.Core` project where the `gulpfile.js` exists and execute the `gulp` command.


## Adding an application



## Adding a new page/route



## Adding services and directives



## Keeping the Core up-to-date



## Managing custom code/styles



## Removing a Mashup appliation from your machine



## Using Gulp



## Using Source Control



## Configure and Publish



## Hybrid mobile applications



