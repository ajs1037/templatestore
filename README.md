# Web Template Store

A simple web template sales app. Lists templates with their details including price and category. Has very simple PayPal buy button on the details page. 

•	Uses the Angular Seed boiler plate
•	Has custom routing using Angular-Route
•	Create controller and views
•	Uses the $http service to fetch template info from a .json file

1.	Download Git from https://git-scm.com 
2.	In projects folder(I put all my projects in projects folder): 
                     
       git clone --depth=1 https://github.com/angular/angular-seed.git templatestore

3.	cd into templatestore
4.	npm install
5.	bower install bootstrap
       
### Bootstrap used (copy page source into index.html): 

    http://getbootstrap.com/examples/starter-template/






BUG: Details buttons do not jump to details page when clicked. User has to type http://localhost:8000/#!/templates/1 in search bar to get to detail pages
