# The Bicycle Hub - Full Stack E-Commerce Platform Developed Using Django and Core Web Technologies

**The Bicycle Hub** is a fully functional e-commerce platform for buying and selling bicycles and accessories. This platform is developed using Django and core web technologies, offering a seamless user experience for both customers and administrators.

## Key Features
- **User Authentication**: Secure registration, login, and profile management.
- **Product Listings**: Detailed pages for bicycles and accessories with images, descriptions, and pricing.
- **Search**: Intuitive search for easy product discovery.
- **Shopping Cart**: Add, update the quantities of products, and remove products from the cart before checkout.
- **Order Management**: Place and track orders with a smooth checkout process.
- **Admin Dashboard**: Manage products, orders, and users through a user-friendly admin interface.
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices.

---

## E-Commerce Application: Detailed Features Overview

 **Admins** and **Users**. 

---

## Admin Features

### 1. Product Management
Admins have full control over the product catalog, allowing them to manage products in the store effectively.
- **Add Products**: Admins can add new products by providing essential details such as name, description, price, stock, and category.
- **Edit Products**: Admins can modify existing products to update their details such as price, stock quantity, and other attributes.
- **Delete Products**: Admins can remove products from the catalog that are no longer available or relevant.
- **View Product List**: Admins can view all products listed on the platform with a quick overview of product details, including availability and pricing.

### 2. Order Management
Admins can oversee the entire order process, from order placement to shipment.
- **View Orders**: Admins can view all customer orders, including detailed information such as customer data, ordered products, quantity, shipping address, and total cost.
- **Update Order Status**: Admins can change the status of orders to track their progress (Pending, Shipped, Delivered, or Canceled).
- **Track Shipments**: Admins can track orders in transit and ensure they are delivered to customers promptly.

### 3. Customer Management
Admins have access to customer profiles, allowing them to view or modify customer information.
- **View Customer Profiles**: Admins can access customer profiles to view personal information, purchase history, and shipping details.
- **Update Customer Information**: Admins can edit or update customer details in case of errors or requests.
- **Delete Customer Accounts**: Admins have the authority to delete customer accounts if necessary, ensuring data integrity and compliance.

### 4. Analytics & Dashboard
Admins can access real-time data to monitor platform performance and make informed business decisions.
- **Sales Analytics**: Admins can view sales trends, including total revenue, daily/weekly/monthly sales, and popular products.
- **Customer Insights**: Admins can analyze customer behavior, track order frequency, and identify loyal customers.
- **Product Performance**: Admins can check which products are performing well and which need adjustments in terms of pricing or promotion.
- **Visual Reports**: Graphs and charts are available for easier analysis of key business metrics such as total sales, active orders, and revenue growth.

### 5. Authentication & Security
Admin access is secured to ensure only authorized personnel can manage platform operations.
- **Secure Admin Panel**: Admin access is protected by login credentials and role-based permissions. Only users with admin rights can access the admin panel.
- **User Permissions**: Admins can define roles and permissions for different admin users to control access to sensitive operations.
- **Password Protection**: Admins must use strong passwords to protect their accounts and the system from unauthorized access.

---

## User Features

### 1. User Registration & Login
Customers can easily sign up and log in to the platform for a personalized shopping experience.
- **Sign Up**: New users can create accounts by providing basic details like name, email, password, and mobile number.
- **Secure Login**: Registered users can log in using their email and password. Login is protected by Django's authentication system.
  

### 2. Product Browsing
Customers can explore the product catalog and find items of interest.
- 
- **Product Details**: Each product page provides detailed information including product name, description, price, product image.
- **Search Functionality**: Users can search for products based on keywords like name or price range.

### 3. Shopping Cart
The shopping cart enables users to manage their selected products before making a purchase.
- **Add Products to Cart**: Users can add products to the cart with just one click.
- **View Cart**: Users can view the items in their cart, see the total price, and can update quantities or remove items
- **Proceed to Checkout**: Once the cart is finalized, users can proceed to checkout to complete the order.

### 4. Order Placement
Users can place orders for the products in their cart.
- **Order Summary**: After selecting items in the cart, users are shown an order summary, including product details, quantities, and total cost.
- **Shipping Information**: Users must enter shipping details such as email, mobile number, and shipping address.
- **Payment Integration**: (Sample Payment methods), allowing users to pay securely via online payment methods (credit/debit card,cod,giftcard etc.).
- **Order Confirmation**: Once payment is successful, users are redirected to a confirmation page showing the Buttons view order details and Continue Shooping.

### 5. Order Tracking
Customers can track the status of their orders and view past purchases.
- **View Orders**: Users can view a list of all their past orders, including order status and details.
- **Track Order Status**: The status of orders (Pending, Shipped, Delivered) is visible in real-time.

### 6. Profile Management
Users can view and update their profile to maintain accurate information.
- **Profile Details**: Users can view their personal details such as username,firstname,lastname, email, mobile.
- **Update Information**: Users can edit their personal information and save changes directly.
- **Profile Picture**: Users can upload or change their profile picture. During Signup ,a default Profile pic is taken customers can change as per his wish

### 7. Change Password
Users can update their account password for better security.
- **Password Update**: Users can securely change their password through the 'Change Password' feature.
- **Password Validation**: The system ensures that users set strong passwords that meet security standards.

### 8. ABOUT ECOMMERCE WEBISTE
- **About US Information**: Users can access an "About Us" page to get information about the platform .
-

### Prerequisites

- **Python**: 3.8 or higher
- **pip**: Python package installer
- **MySQL**: For database management  Install the MySQL client library: pip install mysqlclient
- **Django**:Install Django Run the following command: pip install django

### Steps to Install

#### 1. Install Python

Make sure Python is installed on your system. You can download it from the official website:

### Make Migrations

Now, let's set up the database tables by running migrations:

python manage.py makemigrations
python manage.py migrate

###Create Superuser (Admin)
Create a superuser to access the Django admin dashboard:

python manage.py createsuperuser

Run the Development Server
Now, you can run the Django development server:



python manage.py runserver
This will start the server, and you can access the platform in your browser at:
http://127.0.0.1:8000/


 Access Django Admin Dashboard
To access the Django admin dashboard, visit:


http://127.0.0.1:8000/admin/


