//Zomato Appilication API Links

//Page 1

# List of city

http://localhost:9092/location

# List of Restaurant

http://localhost:9092/resturantdata

# Restaurant wrt City

> http://localhost:9092/resturantdata?stateid=2

# List of QuickSearch

> http://localhost:9092/mealtype

//Page 2

# Restaurant wrt Meal

> http://localhost:9092/resturantdata?mealid=5

# Restaurant wrt Meal & cuisine

> http://localhost:9092/filter/1?cuisineid=2

# Restaurant wrt Meal & cost

> http://localhost:9092/filter/1?lcost=400&hcost=12000
> http://localhost:9092/filter/1?lcost=400&hcost=900&cuisineid=4

# Sort on basis of cost

> http://localhost:9092/filter/1?lcuisineid=4&sort=-1

//Page3

# Details of the Restaurants

//On The Basic Of Object Id

> http://localhost:9092/resturantdetails/62c726de1050b3aaad588b27
> //On The Basic Of resturant Id
> http://localhost:9092/resturantdetails/4

# Menu of the Restaurants

> http://localhost:9092/menu/3

//Page4

# Menu Details

> localhost:9870/menuItem (POST)
> {"id":[1,6,7]}

# Place Order

> (Post)http://localhost:9870/placeOrder
> {

    "orderId" : 1,
    "name" : "sachin",
    "email" : "sachin@gmail.com",
    "address" : "Hom 42",
    "phone" : 7833345457,
    "cost" : 365,
    "menuItem" : [
    	24,
    	13,
    	8
    ]

}

//Page5

# List of order place

# List of order place wrt to email

# update order details with payment

///////
Delete order
