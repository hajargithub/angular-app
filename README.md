
# 🛍️ Angular Product Management Frontend

This is a simple Angular frontend project that displays and manages a list of products using a Spring Boot backend.

## 📦 Features

- View product list with ID, name, price, and selection status
- Delete a product with confirmation
- Dynamic product list update after delete
- Backend consumed via REST API
- Clean Bootstrap icons for UI feedback

## 🧠 Tech Stack

- Angular 16+
- TypeScript
- Bootstrap Icons
- RxJS & HttpClient
- RESTful backend from Spring Boot

## 🚀 Run This App Locally

### 1. Clone and install dependencies


```bash
git clone https://github.com/hajargithub/angular-app.git'/angular-app
cd angular-app
npm install
```

### 2. Run the development server

```bash
ng serve
```

[http://localhost:4200/products](http://localhost:4200/products)

## 🧭 App Structure

```
src/
├── app/
│   ├── products/
│   │   ├── products.ts        # Component logic
│   │   ├── products.html      # View template
│   │   └── products.css       # Component styling
│   ├── services/
│   │   └── products.ts        # ProductService (API calls)
│   └── app.routes.ts          # App routing
```

