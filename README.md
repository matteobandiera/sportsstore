# sportsstore
AngularJs Example Application

This is a small application I am building to learn AngularJs. 
I am going throgh the book <a href="http://www.amazon.com/Pro-AngularJS-Experts-Voice-Development/dp/1430264489">Pro AngularJs</a> and following its very well documented example.

To get this example working you will need to create a <a href="http://deployd.com">Deployd</a> application on port 5500.

Download Deployd and follow the following steps.

1 - Create a new folder at the same level as the sportstore folder named deployd

2 - Change to the new directory and type the following at the command line

  <code>dpd create sportstore</code>
  
  #to start the new server <br />
  <code>dpd -p 5500 sportsstore\app.dpd</code>
  
3 - Open your browser ogf choice and navigate to <code>localhost:5500/dashboard</code>

4 - From the GUI ou will need to create 3 collections
  
  1 - /products
      
      name            string    required
      description     string    required
      category        string    required
      price           string    required
      
      
  2 - /orders
  
      name            string    required
      street          string    required
      city            string    required
      state           string    required
      zip             string    required
      country         string    required
      giftwrap        boolean
      products        array     required
      
  3 - /users

      create a new admin user.
