# WORK IN PROGRESS

## Android Unlock Pattern Demo using Vanilla Javascript

There are other examples of implementing the pattern unlock using Javascript, but I did not like the other techniques. The objective is to allow the user to set a pattern and use it to unlock features on the page.

![Android Unlock Pattern Image](http://playingwithmodels.files.wordpress.com/2010/04/unlock_pattern.png "Android Unlock Pattern Image")

### Objective

 - [ ] Create an unlock pattern on the grid.

 - [ ] Try and use Canvas to show lines between the circles

 - [ ] Create circles out of pure CSS

 - [ ] Try and not use images at all

 - [ ] Do this only using Vanilla JS

 - [ ] Use localstorage shims to fallback to a database / cookie based storage solution

 - [ ] Make it cross browser compatible IE7 onwards.

 - [ ] Allow configuration changes on the page itself. 

 - [ ] Have different themes

### Why

Right now all the implementations I have seen, create divs for vertical and horizontal lines and show/hide DOM elements based on mouse movements. The problem I have with this approach is that there are too many moving parts. There are atleast 8 DOM elements I change the state of when I drag my mouse across and I feel there has to be a better solution. Also, I failed doing this once with canvas and am an adamant asshole.

### How