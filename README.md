
![inventory](https://res.cloudinary.com/dnr14t7ka/image/upload/v1676099361/all-devices-black_wvbz6r.png)

#  Build and Deploy a React Admin Dashboard
## [Demo Live  🎯](https://genuine-panda-f8ff78.netlify.app/)
##  [Backend Loink   🎯](https://github.com/kamrulcoder/inventory-backend)

## Features

- Build authentication with JSON Web  Token including User Registration, Login and Password Reset
- Upload image with multer and save to Cloudinary
- Protect routes to only be accessed by logged-in users-
- Manage state with Redux Toolkit
- Build a dashboard for product management
- Build a user profile page
- Edit user profile from the frontend

## Tech

Inventory Project  uses a number of open source projects to work properly:

 - MongoDB
 - Express.js
 - React.js 
 - Node.js 
 - node-sass
 - mongoose
 - redux toolkit
 - cloudinary
 - cookie-parser


Project Structure 

```
📦 Inventory management system - frontend 
├─ .env
├─ .gitignore
├─ README.md
├─ package-lock.json
├─ package.json
├─ public
│  ├─ favicon.ico
│  ├─ index.html
│  ├─ logo192.png
│  ├─ logo512.png
│  ├─ manifest.json
│  └─ robots.txt
├─ src
│  ├─ App.js
│  ├─ assets
│  │  ├─ inv-img.png
│  │  └─ loader.gif
│  ├─ components
│  │  ├─ card
│  │  │  ├─ Card.js
│  │  │  └─ Card.module.scss
│  │  ├─ changePassword
│  │  │  ├─ ChangePassword.js
│  │  │  └─ ChangePassword.scss
│  │  ├─ footer
│  │  │  └─ Footer.js
│  │  ├─ header
│  │  │  └─ Header.js
│  │  ├─ infoBox
│  │  │  ├─ InfoBox.js
│  │  │  └─ InfoBox.scss
│  │  ├─ layout
│  │  │  └─ Layout.js
│  │  ├─ loader
│  │  │  ├─ Loader.js
│  │  │  └─ Loader.scss
│  │  ├─ product
│  │  │  ├─ productDetail
│  │  │  │  ├─ ProductDetail.js
│  │  │  │  └─ ProductDetail.scss
│  │  │  ├─ productForm
│  │  │  │  ├─ ProductForm.js
│  │  │  │  └─ ProductForm.scss
│  │  │  ├─ productList
│  │  │  │  ├─ ProductList.js
│  │  │  │  └─ productList.scss
│  │  │  └─ productSummary
│  │  │     ├─ ProductSummary.js
│  │  │     └─ ProductSummary.scss
│  │  ├─ protect
│  │  │  └─ HiddenLink.js
│  │  ├─ search
│  │  │  ├─ Search.js
│  │  │  └─ Search.module.scss
│  │  └─ sidebar
│  │     ├─ Sidebar.js
│  │     ├─ Sidebar.scss
│  │     └─ SidebarItem.js
│  ├─ customHook
│  │  └─ useRedirectLoggedOutUser.js
│  ├─ data
│  │  └─ sidebar.js
│  ├─ index.css
│  ├─ index.js
│  ├─ pages
│  │  ├─ Home
│  │  │  ├─ Home.js
│  │  │  └─ Home.scss
│  │  ├─ addProduct
│  │  │  └─ AddProduct.js
│  │  ├─ auth
│  │  │  ├─ Forgot.js
│  │  │  ├─ Login.js
│  │  │  ├─ Register.js
│  │  │  ├─ Reset.js
│  │  │  └─ auth.module.scss
│  │  ├─ contact
│  │  │  ├─ Contact.js
│  │  │  └─ Contact.scss
│  │  ├─ dashboard
│  │  │  └─ Dashboard.js
│  │  ├─ editProduct
│  │  │  └─ EditProduct.js
│  │  └─ profile
│  │     ├─ EditProfile.js
│  │     ├─ Profile.js
│  │     └─ Profile.scss
│  ├─ redux
│  │  ├─ features
│  │  │  ├─ auth
│  │  │  │  └─ authSlice.js
│  │  │  └─ product
│  │  │     ├─ filterSlice.js
│  │  │     ├─ productService.js
│  │  │     └─ productSlice.js
│  │  └─ store.js
│  └─ services
│     └─ authService.js
└─ yarn.lock
```
#### Author 
[GITHUB](https://github.com/kamrulcoder)



