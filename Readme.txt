Hello, Reviewers!

You can run available unittests from VS terminal using command: python manage.py test tests/
Don't forget to activate vitruan env and cd into littlelemon directory before running unit-tests command.

You can use the following API paths for testing purposes using Insomnia or Postman clients.

# JDOSER endpoint, for example, to make POST request and create new user
/auth/users/ 

# to login and auth get token
/api-token-auth/ 
# to login using JDOSER endpoint
/auth/token/login 

# menu items
/restaurant/menu/
/restaurant/menu/{menuItemId}

# table booking 
/restaurant/booking/tables/
/restaurant/booking/tables/{bookingId}
