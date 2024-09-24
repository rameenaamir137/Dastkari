# Dastkari Website

The Dastkari website is a platform dedicated to empowering village women by providing them with an online marketplace to showcase and sell their handcrafted products. The website bridges the gap between artisans and customers, especially those from rural areas, by leveraging web engineering concepts and language support.

## Problem Statement

In rural areas, village women possess exceptional artistic skills and create beautiful handicrafts. However, they often face challenges in accessing markets and finding customers who appreciate their work. Language barriers further limit their reach and prevent them from expanding their customer base. The Dastkari website aims to address these issues by creating a dedicated online platform where village women can display and sell their products. The inclusion of search functionality in both Urdu and English allows users to find items and enables the artisans to connect with potential customers who may not be proficient in English.
## Video Introduction

<iframe width="560" height="315" src="https://drive.google.com/file/d/1zv3lXf4igJ_LbdBQm9DxCtdqkj1efe_f/preview" frameborder="0" allowfullscreen></iframe>


## Key Features

- **User Roles and Authentication:** The website supports three user roles - middle admin, sellers, and customers. The middle admin has administrative privileges, while sellers can add and manage their products. Customers need to register and log in to make purchases.
- **Product Categories and Inventory Management:** The middle admin can create and delete product categories, and sellers can add their products to these categories. Sellers have control over their inventory, including adding new products and managing existing ones.
- **Product Display and Search Functionality:** The website displays products to both registered and non-registered users. Customers can browse products by category and view detailed information such as images, descriptions, prices, and stock availability. The search functionality supports searching in both Urdu and English, providing an inclusive experience for users.

## Implementation Methodology

The Dastkari website follows a structured implementation methodology:

- **Planning and Design:** Thorough analysis of requirements is conducted, and a detailed project plan is created. The website's user interface and overall structure are designed to ensure an intuitive and visually appealing layout.
- **Development:**
  1. **User Authentication System:** Laravel and Jetstream are utilized for pre-built authentication functionality, including user registration, login, and password reset features. These features ensure secure access control for the website.<br>
  2. **Middle Admin Functionalities:** Laravel's MVC architecture is leveraged to develop middle admin functionalities. Controllers handle category management, product viewing, and order management logic. Blades (Views) generate dynamic HTML content for the admin interface. MySQL is used for database interaction.<br>
  3. **Seller Functionalities:** Controllers and Blades are implemented to handle seller-specific operations, such as adding and viewing products. Laravel's ORM facilitates seamless interaction with the MySQL database.<br>
  4. **Customer-Facing Features:** Blades are used to create customer-facing features like category browsing, product details display, and cart management. Controllers handle user actions, validate inputs, and interact with the database to provide requested data or perform operations.<br>
  5. **Search Functionality:** The search functionality, built using Python, is integrated with the website's frontend. It enables users to search for products using keywords in both Urdu and English, enhancing inclusivity and expanding the reach of the village women's handicrafts.



## Conclusion

The Dastkari website provides a crucial platform for village women to showcase their talents, sell their handcrafted products, and gain economic independence. By leveraging web engineering concepts and incorporating features like user authentication, product categories, inventory management, and search functionality, the website offers an inclusive and seamless experience for users. Through Dastkari, village women can connect with a wider customer base, expand their market reach, and create a path towards financial empowerment and prosperity.
