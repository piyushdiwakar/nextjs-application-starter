# 🛍️ FashionStore - FashionStore-like E-commerce App

A modern, responsive e-commerce application built with Next.js, TypeScript, and Tailwind CSS. This project replicates the core functionality and design patterns of popular fashion e-commerce platforms like FashionStore.

![FashionStore Preview](https://via.placeholder.com/800x400/000000/FFFFFF?text=FashionStore+E-commerce+App)

## ✨ Features

### 🏠 **Homepage**
- Hero section with gradient overlay and call-to-action buttons
- Feature highlights (Free Shipping, Easy Returns, Secure Payment)
- Category showcase with hover effects
- Featured products grid
- Newsletter subscription

### 🛒 **Product Management**
- **Product Listing Page** with advanced filtering and sorting
- **Product Detail Pages** with image galleries and variant selection
- **Shopping Cart** with quantity management and price calculations
- **Checkout Process** with multi-step form validation

### 🎨 **Design & UX**
- Modern, clean design inspired by FashionStore
- Fully responsive layout for all devices
- Professional typography and spacing
- Smooth animations and hover effects
- Black and white color scheme with strategic accent colors

### 🔧 **Technical Features**
- Built with Next.js 15 and TypeScript
- Styled with Tailwind CSS and Shadcn/ui components
- Dynamic routing for product pages
- Client-side state management
- Form validation and error handling
- SEO-friendly structure

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed on your machine:
- **Node.js** (version 18.0 or higher)
- **npm**, **yarn**, **pnpm**, or **bun** package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd fashion-store
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

4. **Open your browser**
   
   Navigate to [http://localhost:8000](http://localhost:8000) to see the application.

   > **Note:** This app runs on port 8000 by default (configured in package.json)

## 📁 Project Structure

```
fashion-store/
├── public/                 # Static assets
├── src/
│   ├── app/               # Next.js App Router pages
│   │   ├── page.tsx       # Homepage
│   │   ├── layout.tsx     # Root layout
│   │   ├── globals.css    # Global styles
│   │   ├── products/      # Product pages
│   │   ├── cart/          # Shopping cart
│   │   └── checkout/      # Checkout process
│   ├── components/        # Reusable components
│   │   └── ui/           # UI components
│   ├── lib/              # Utilities and data
│   │   ├── utils.ts      # Helper functions
│   │   └── data/         # Mock data
│   └── hooks/            # Custom React hooks
├── components.json        # Shadcn/ui configuration
├── tailwind.config.js     # Tailwind CSS configuration
├── next.config.ts         # Next.js configuration
└── package.json          # Dependencies and scripts
```

## 🛠️ Available Scripts

- `npm run dev` - Start development server on port 8000
- `npm run build` - Build the application for production
- `npm run start` - Start the production server
- `npm run lint` - Run ESLint for code quality

## 📱 Pages & Features

### 🏠 **Homepage** (`/`)
- Hero banner with promotional content
- Category navigation
- Featured products showcase
- Company features and newsletter signup

### 🛍️ **Products** (`/products`)
- Product grid with filtering options
- Sort by price, rating, newest, etc.
- Category and brand filters
- Price range slider
- Responsive product cards with hover effects

### 📄 **Product Details** (`/products/[id]`)
- High-quality product images with gallery
- Product information and specifications
- Size and color selection
- Quantity selector
- Add to cart and buy now options
- Related products suggestions

### 🛒 **Shopping Cart** (`/cart`)
- Cart items management
- Quantity adjustment
- Price calculations (subtotal, shipping, tax)
- Proceed to checkout
- Continue shopping option

### 💳 **Checkout** (`/checkout`)
- Multi-step checkout process
- Contact information form
- Shipping address collection
- Payment information (demo)
- Order summary
- SSL security indicators

## 🎨 Styling & Design

This project uses:
- **Tailwind CSS** for utility-first styling
- **Shadcn/ui** for pre-built accessible components
- **Inter Font** for modern typography
- **Custom CSS variables** for consistent theming
- **Responsive design** principles for all screen sizes

## 📊 Mock Data

The application uses mock data for demonstration purposes:
- 8 sample products with realistic details
- Product categories (T-Shirts, Dresses, Jeans, Footwear, etc.)
- Brand information and pricing
- Customer reviews and ratings

## 🔧 Customization

### Adding New Products
Edit `src/lib/data/products.ts` to add or modify product data:

```typescript
{
  id: 9,
  name: "Your Product Name",
  price: 49.99,
  originalPrice: 69.99,
  imageUrl: "https://your-image-url.com",
  description: "Product description",
  category: "Category",
  brand: "Brand Name",
  rating: 4.5,
  reviews: 100,
  sizes: ["S", "M", "L"],
  colors: ["Red", "Blue", "Green"]
}
```

### Styling Modifications
- Update `src/app/globals.css` for global styles
- Modify Tailwind classes in components for design changes
- Customize the color scheme in `tailwind.config.js`

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to [Vercel](https://vercel.com)
3. Deploy with default settings

### Other Platforms
The app can be deployed to any platform that supports Next.js:
- Netlify
- Railway
- DigitalOcean App Platform
- AWS Amplify

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Design inspiration from [FashionStore](https://FashionStore.com)
- Built with [Next.js](https://nextjs.org)
- UI components from [Shadcn/ui](https://ui.shadcn.com)
- Styled with [Tailwind CSS](https://tailwindcss.com)
- Images from [Pexels](https://pexels.com)

## 📞 Support

If you have any questions or need help with setup, please:
1. Check the existing issues on GitHub
2. Create a new issue with detailed information
3. Provide steps to reproduce any problems

---

**Happy Shopping! 🛍️**

Made with ❤️ using Next.js and TypeScript
