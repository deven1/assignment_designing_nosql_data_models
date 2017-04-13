Your eCommerce business needs to keep track of products and their prices. The products each belong to a department. The business needs to keep track of revenue as product prices change over time. The business also needs to keep track of receipts of transactions and the number of units each product has in stock.

* transaction
------------
		date: DateTime,
		products: [
  		{productID, quantity: INT, price: Num},
    	{productID, quantity: INT, price: Num}
    ]

* department
------------
		products: [
			{productID, stock: INT, price: Num},
			{productID, stock: INT, price: Num}
		]


You're building an activity feed for a social media site. The feed must display a chronological list of activities for the current user's friends. These activities could potentially be any action performed on the site including uploading a photo, changing their profile, friending another user, commenting, liking etc... Further, you only want to display activities for users that the current user interacts with frequently.

	* activity - DOCUMENT
		-------------------
		{
			"activityID": INT,
			"authorID": INT,
			"date": DateTime
			"activityDetails": {
				"body": TEXT,
				"mediaURL" : TEXT,
			}
		}

	* user -- DOCUMENT
		-----------------
		{
		  "id": INT,
		  "username": STRING REQUIRED,
		  "email": STRING REQUIRED,
		  "friendIds": [friendID_1, friendID_2, ....]
			"frequentFriendIds": [friendID_2, friendID_6, ....]
		}
