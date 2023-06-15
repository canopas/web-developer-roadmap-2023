# E-commerce App backend using NodeJS

### Application will have two types of users :

- Admin - Should have Read/Write access.
- User - Should have Read access only.

**Note:** Admin is also a user. Admin should have all access same as the user. Additionally, they can modify the content(categories, subcategories, products).

## Description

- This E-commerce app contains products with categories and subcategories.
  - Example:
    - category: food
    - subcategory: Chinese, Italian, Mexican
    - product: Manchurian, pasta, pizza
- Admin panel,
  - It is used to add and manage data by admins
  - admins can perform CRUD operations of products, categories, and subcategories
  - Admin should require to SignUp/SignIn to access the admin panel
- On the Website,
  - It should be accessible to all users and provide an interactive UI for users to use our e-commerce app.
  - Users can see all products and filter them by categories and subcategories
  - Allow users to favorite/unfavourite products if they have logged-in otherwise redirect to the login page on click on favorite/unfavourite

