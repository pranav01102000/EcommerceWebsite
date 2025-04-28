# E-Tech Store - Electronics eCommerce Platform

## 📋 Overview

E-Tech Store is a comprehensive eCommerce platform developed specifically for electronics retailers. This modern web application provides a seamless shopping experience with robust admin controls, secure payment processing, and responsive design across all devices.

Built with a modern full-stack architecture combining React/Next.js frontend with Spring Boot backend and MongoDB database, E-Tech Store delivers high performance, scalability, and developer-friendly code structure.

## 🚀 Technology Stack

### Frontend
- **Next.js** - React framework for server-side rendering, static site generation, and optimized performance
- **React.js** - UI component library for building interactive user interfaces
- **Redux Toolkit** - State management solution
- **Tailwind CSS** - Utility-first CSS framework for responsive design
- **Axios** - HTTP client for API requests
- **React Query** - Data fetching and caching library

### Backend
- **Spring Boot** - Java-based framework for building robust backend applications
- **Spring Security** - Authentication and authorization
- **Spring Data** - Data access and manipulation
- **Spring Web** - RESTful API development

### Database
- **MongoDB** - NoSQL database for flexible data storage


## ✨ Features

### Customer Features
- **User Authentication** - Secure signup/login with JWT, social login options
- **Product Browsing** - Advanced filtering, sorting, and search capabilities
- **Product Details** - High-quality images, specifications, reviews, and related items
- **Shopping Cart** - Add/remove items, adjust quantities, save for later
- **Checkout Process** - Multiple payment options, address management, order summary
- **Order Management** - Track orders, view history, and manage returns
- **Wishlist** - Save favorite products for future consideration
- **User Reviews** - Rate and review purchased products
- **Responsive Design** - Optimized for mobile, tablet, and desktop

### Admin Features
- **Dashboard** - Overview of sales, inventory, and customer metrics
- **Product Management** - Add, edit, and delete products with bulk operations
- **Inventory Control** - Track stock levels, set alerts for low inventory
- **Order Processing** - View, update, and manage order status
- **Customer Management** - View customer profiles and purchase history
- **Analytics & Reports** - Sales performance, product popularity, and customer behavior
- **Content Management** - Update banners, promotions, and category pages

### Technical Features
- **Performance Optimization** - Image optimization, code splitting, lazy loading
- **SEO Friendly** - Server-side rendering, metadata management, sitemap generation
- **Security Measures** - CSRF protection, input validation, secure authentication
- **API Documentation** - Swagger UI for backend API documentation
- **Responsive Design** - Optimized user experience across all devices
- **Error Handling** - Comprehensive client and server-side error management

## 🛠️ Installation & Setup

### Prerequisites
- Node.js (v16+)
- Java Development Kit (JDK) 17+
- MongoDB (v5+)
  

### Frontend Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/etech-store.git
cd etech-store/frontend

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Edit .env.local with your configuration

# Run development server
npm run dev
```

### Backend Setup
```bash
# Navigate to backend directory
cd ../backend

# Build the project
./mvnw clean install

# Run the application
./mvnw spring-boot:run
```


## 📚 API Documentation

API documentation is available at `/api/swagger-ui.html` when running the backend server.

## 🧪 Testing

### Frontend Tests
```bash
cd frontend
npm run test
```

### Backend Tests
```bash
cd backend
./mvnw test
```


## 📄 Project Structure

```
etech-store/
├── frontend/                # Next.js application
│   ├── public/              # Static assets
│   ├── src/
│   │   ├── components/      # React components
│   │   ├── pages/           # Next.js pages
│   │   ├── hooks/           # Custom React hooks
│   │   ├── store/           # Redux store configuration
│   │   ├── services/        # API services
│   │   ├── styles/          # Global styles
│   │   └── utils/           # Utility functions
│   ├── .env.example         # Environment variables example
│   └── package.json         # Frontend dependencies
│
├── backend/                 # Spring Boot application
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/        # Java source code
│   │   │   └── resources/   # Application properties and resources
│   │   └── test/            # Backend tests
│   └── pom.xml              # Backend dependencies
│

└── README.md                # Project documentation
```

## 🚀 Deployment

### Production Deployment
- Frontend is deployed on Vercel/Netlify

### Configuration
Ensure all environment variables are properly set for production deployment.

## 🔮 Future Enhancements

- **PWA Support** - Convert to Progressive Web App for offline capabilities
- **AI Product Recommendations** - Personalized product suggestions
- **Advanced Analytics** - Customer behavior tracking and insights
- **Multi-language Support** - Internationalization for global customers
- **Augmented Reality** - Product visualization in customer environments

## 👥 Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request
