### Welcome to Eko Delivery Service Guide
###### Extract project-challenge
###### cd project-challenge
```
 npm install
 node index.js
```

##### Results of given paths will be on console of terminal // (Lowest cost) 
if any new path is being added to find the lowest cost calculation then follow the below given code

```
nano index.js
 // Add more routes in array of deliveryRoutes
  e.g:
	
       var deliveryRoutes = [
    	    route.shortestPath('A', 'E', { cost: true }),
            route.shortestPath('A', 'D', { cost: true }),
            route.shortestPath('E', 'F', { cost: true }),
            route.shortestPath('A', 'F', { cost: true }),
            route.shortestPath('E', 'D', { cost: true }), 
        
        // add comma before new path
        // add new route as above
	]

```
##### Finding path of cheapest cost
##### Note: E to E case would be Zero as algorithm finds the shortestpath form start to goal
##### Rest of the cases are with non-zero cost


##### Note: Unit Test Guide
##### Extract Project-Challenge 
##### cd Project-challenge

```
npm test
```
###### Sunjay-Kumar 
###### Email: sunjay.st116605@gmail.com
###### Contact #: +66 94 887 7955
