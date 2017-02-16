#JIRA Issue Collector#

The JIRA Issue Collector widget allows you to safely place the JIRA Issue Collector JavaScript in your Mendix project.

##Installation instructions##
Place only one widget in your main template for desktop / phone and tablet layouts.
The widget will check this for itself but its best practise to just do this yourself.

##What happens inside the widget?##
You need to enter a URL. This is the URL that is provided in the jQuery example you get if you start a new JIRA issue collector.
The jQuery example is setup in the widget with the provided URL at runtime. And will result in what ever JIRA does to a normal website to create the button on the page.
Because of the widgets best practises by checking if the widget is placed only once one your layout this will happen only once!

##Configuration##
Just provide the URL you get from the jQuery example you get if you start a new JIRA issue collector.