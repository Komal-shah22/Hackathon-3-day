"# Hackathon-3-day" 
# 🌟 Hackathon Day 3 Completed! 🌟

Hello everyone! I am Komal shah, a Fullstack Developer.

## 🚀 Hackathon Day 3: Template 1 Task Completed! 🚀

I'm excited to share that I've successfully completed the Day 3 task for Template 1 in the hackathon! Here's what I achieved:

### ✅ Achievements
- **API Integration**: Integrated and displayed data dynamically using Sanity CMS for Template 1.
- **Dynamic Routing**: Implemented seamless navigation to individual product pages with dynamic content.
- **Sorting Functionality**: Added sorting by price (Low to High & High to Low) for a better user experience.
- **Responsive Design**: Ensured the layout is clean and user-friendly across all devices.

This task allowed me to sharpen my skills in:
- 🔗 API Integration and Migration
- 🔗 Frontend Development with Next.js
- 🔗 Schema Validation and Error Handling

Grateful for the opportunity to work on Template 1 and learn more about integrating headless CMS and dynamic routing in real-world scenarios. On to the next milestone! 🎉

---

## Project Title: **E-Commerce Marketplace with Sanity CMS and API Integration**

### Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Setup Instructions](#setup-instructions)
5. [API Integration](#api-integration)
6. [Dynamic Routing](#dynamic-routing)
7. [Sorting Functionality](#sorting-functionality)
8. [Screenshots](#screenshots)
9. [Best Practices Followed](#best-practices-followed)

---

### Introduction
This project demonstrates the integration of APIs with Sanity CMS to build a dynamic e-commerce marketplace. Products are fetched from the CMS and displayed on the frontend with dynamic routing for detail pages. Sorting functionality is included to display products based on price (low to high or high to low).

---

### Features
- **Dynamic Product Listings**: Display products dynamically using Sanity CMS.
- **Sorting Options**: Sort products by price (low to high, high to low).
- **Dynamic Routing**: Navigate seamlessly to individual product pages.
- **Responsive Design**: Works across all device sizes and screen orientations.
- **Error Handling**: Displays user-friendly error messages and logs issues for debugging.

---

### Technologies Used
- **Frontend**: Next.js, Tailwind CSS
- **Backend**: Sanity CMS, REST APIs

---

### Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/projectname.git
   cd projectname
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Add environment variables**:
   - Create a `.env.local` file in the root directory.
   - Add the following keys:
     ```env
     NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id
     NEXT_PUBLIC_SANITY_DATASET=production
     SANITY_API_TOKEN=your_api_token
     ```

4. **Start the development server**:
   ```bash
   npm run dev
   ```

---

### API Integration
- **Sanity CMS**: All product data is fetched from Sanity.
- **Endpoints**:
  - `/api/products`: Fetch all products.
- **Error Handling**:
  - Logs API errors for debugging.
  - Displays fallback UI on errors.

---

### Dynamic Routing
Each product is linked to a detail page using dynamic routing. When a user clicks on a product, they are taken to `/product/[id]` with dynamically rendered data.

---

### Sorting Functionality
- **Low to High Price**: Products are sorted in ascending order of their prices.
- **High to Low Price**: Products are sorted in descending order of their prices.

---

### Screenshots
- **Shop Page**: Displays product listings with sorting options.
  *(Add a screenshot here)*

- **Product Detail Page**: Shows detailed information for a specific product.
  *(Add a screenshot here)*

---

### Best Practices Followed
- Sensitive data stored in `.env.local`.
- Modular and reusable code.
- Thorough error handling.
- Consistent commit messages and version control.

---


