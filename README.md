# Recipe sharing website.


Abstract— FoodE is a food recipe website whose sole purpose is to provide food recipes. It also includes many features like search based on ingredients and recipe names, a forum to share recipes, festival based recipe suggestions, different diet plans. FoodE is integrated with alexa which reads you out a recipe from our collection of recipes.
I. INTRODUCTION
FoodE is a food recipe website. It allows a user to search for a recipe based on the the name of the recipe. It also has ingredient based search which makes user to enter the ingredients he had and it searches and displays all the possible recipes with that combination of ingredients. Recommender systems are also implemented in the app to give suggestion according to user’s interest,festivals. FoodE also provides different predetermined diet plans which on sincere following can give appreciable results.
A. Recommender Systems
This is a machine learning algorithm that we have imple- mented in our project, to recommend recipes to users based on their interests and frequently viewed. The recommendor systems finds users across the website with similar taste according to the recipes they have viewed and tags them together and recommends their future predictions according to that. Trending lists, most famous lists and across the forums lists of recipes are also recommended to the users based on the statistics of usage and basic calculus. Similar recipes for festivals are also recommended based on the pre- defined recipes for pre-defined festivals. Festivals are seen as coming through the lambda functions on the AWS service which would replace the functionality of serialisers in SQL .
B. Ingredient based search
Ingredient based search is the most important feature that differentiates our project with similar recipe websites. In this feature we can give the ingredients we have in our kitchen and find out the recipes we could cook with those specific ingredients. User can find and select the ingredients through the search bar built in the web page and then proceed to search option to get the recommendations.
C. Diet Plans
This is probably the most interesting feature of FoodE. There will be a webpage where you could see and select form the diet plans whether you like to follow a weight loss plan, a muscle building plan or a diabetic plans. Our internal systems calculates the calories and other requirements from the diet plan searches through the entire database to find the
recipes as breakfast, lunch and dinner on that particular plan. User can unsubscribe to a diet and start following another.
D. Forums
There is a forum in FoodE where one can upload there recipe so that all his followers can see. Based on the followers, chefs will be verified and given top chef tag. A user can see the recipes of the chefs he follows and only the latest once.
II. DATABASE
This web site uses DynamoDB by Amazon Web Services as its database management system. Initially, when we had tried to plan a database schema in SQL, we found that we need have very unstructured data which would be very dif- ficult for SQL to handle. The Normalization methods could not be followed because of the data. So the obvious option would be to use No-Sql database. Among No-Sql databases, DynamoDB offers some Key advantages as discussed below which made us to use this specific database.
