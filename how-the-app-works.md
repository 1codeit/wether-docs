# How the app works

Ever wonder how this all works but have no idea what the python means?

***

![image](https://user-images.githubusercontent.com/75509373/218847310-cdefae06-0683-42d6-be90-b9f9e2f19db0.png)

Above is the very start of the code this will import all the librays I need and then it sets all the variables for the Azure Key Vault to function this makes it so it "Just works" and means you dont need to have a api key but also makes it secure so I dont expose my keys publicly.

***

![image](https://user-images.githubusercontent.com/75509373/218847678-79c219af-4635-4b0e-97e6-29bb34180b56.png)

This part of the code sets and retrieves all the data from the openwether api as openwether returns a .json file the code needs to parse it then it puts all the weather info into a dictionary for the next part of the code

***

![image](https://user-images.githubusercontent.com/75509373/218848274-2b1645f5-0651-4bf6-8083-4c8119c1118a.png)

Next we set all the routs for flask there are 3 .html files that we use home.html get\_weather.html and 404.html Home.html is a form that gets the city and country code the get\_weather.html returns all the data of the response

***

This is the Home.html

![image](https://user-images.githubusercontent.com/75509373/218848960-a0e4a24f-e376-4090-b878-cfa58b3a688d.png)

***

This is get\_weather.html

![image](https://user-images.githubusercontent.com/75509373/218849142-7a9300fa-5f4a-49d7-8a15-15e19fa10668.png)

***

404 is not used yet so will be left out
