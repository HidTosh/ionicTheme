# ionicTheme

1- installation : bower install ionic-calendar

2- Load the necessary dependent files Add to index.html :
href="http://code.ionicframework.com/1.1.1/css/ionic.min.css"
href="lib/ionic-calendar/dist/css/calendar.min.css"

add after  ionic.bundle.js 
src="lib/ionic-calendar/dist/js/calendar-tpls.min.js"

3- Add the calendar module as a dependency to your application module: Add ui.rCalendar to line : 
angular.module('starter', ['ionic', 'ui.rCalendar'])

4- Add the directive in the html page
calendar calendar-mode="mode" event-source="eventSource"


For test mobile : 
cordova platform add android --save
Ionic build

ionic emulate android
