## Admin Side

#### Admin Sign-In:
- [x] Create admin sign-in page.
- [x] Implement authentication mechanism (JWT, Session-based, etc.).

#### User Management:
- List Users:
  - [x] Fetch and display list of users.
  - [ ] Implement pagination if user base is large.
- Block/Unblock User:
  - [ ] Add toggle to block/unblock users.
  - [ ] Implement confirmation dialog before blocking/unblocking.
  - [ ] Ensure blocked users cannot log in.

#### Category Management:
- Add Category:
  - [ ] Create form to add new categories.
  - [ ] Validate category data (e.g., unique name).
- Edit Category:
  - [ ] Load category details for editing.
  - [ ] Implement saving of changes with validation.
- Delete Category (Soft Delete):
  - [ ] Implement soft delete mechanism.
  - [ ] Show only active categories by default.

#### Product Management:
- Add Product:
  - [x] Create form to add products with fields for name, description, price, etc.
  - [ ] Implement image upload (minimum 3 images required).
  - [ ] Ensure images are cropped and resized before upload.
- Edit Product:
  - [ ] Load product details for editing.
  - [ ] Allow updating images with cropping/resizing before upload.
- Delete Product (Soft Delete):
  - [ ] Implement soft delete for products.
  - [ ] Show only active products by default.

#### Image Handling:
- [ ] Implement image cropping and resizing on the client side or server side.
- [ ] Ensure images are stored efficiently (e.g., in optimized formats like JPEG/WEBP).

### User Side

#### Home Page:
- [ ] Design and implement a responsive home page layout.
- [ ] Add sections like featured products, top categories, and promotions.

#### User Authentication:
- Sign-Up with Validation:
  - [x] Create sign-up form with fields for user details.
  - [ ] Implement client-side and server-side validation.
- Sign-Up using OTP with Timer & Resend OTP:
  - [ ] Integrate OTP generation and validation.
  - [ ] Implement OTP timer and resend functionality.
- Login/Sign-Up with Single Sign-On (SSO):
  - [ ] Integrate Google, Facebook, etc., for SSO.
  - [ ] Ensure secure authentication flow.

#### Product Listing:
- [ ] Fetch and display list of products with pagination.
- [ ] Implement filters (e.g., by category, price, rating).

#### Product Details View:
- [ ] Create a detailed product page layout.
- [ ] Add image zoom functionality for product images.
- [ ] Implement breadcrumbs for easy navigation.
- [ ] Display ratings, price, discounts, and coupons.
- [ ] Integrate product reviews with pagination.
- [ ] Show stock status (in stock, out of stock, sold out).
- [ ] Highlight product specs.
- [ ] Recommend related products based on category, views, or purchases.

#### Error Handling:
- [ ] Implement user-friendly error messages for out-of-stock or unavailable products.
- [ ] Ensure proper redirection or alerts when products are not available.