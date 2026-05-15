# Divine - Temple Slot Booking System 🛕

A professional, feature-rich web application for seamless temple slot booking management. Built according to client specifications and already deployed in production.

**Live Demo:** 🌐 [https://divine-ruddy.vercel.app](https://divine-ruddy.vercel.app)

## 📋 About

**Divine** is a comprehensive temple slot booking system designed to streamline the process of booking worship slots at temples. This project has been professionally developed and delivered to meet specific client requirements. It provides an intuitive interface for devotees to reserve their preferred time slots while allowing temple administrators to manage bookings efficiently.

## ✨ Key Features

### For Devotees
- 🎫 **Easy Slot Booking** - Seamless booking experience with real-time slot availability
- 📅 **Calendar View** - Visual calendar to select preferred dates and times
- 👤 **User Profiles** - Personal account management and booking history
- 📱 **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- 🔔 **Booking Confirmations** - Instant confirmation and reminder notifications
- 💳 **Multiple Payment Options** - Secure payment integration for advance bookings

### For Administrators
- 📊 **Dashboard Analytics** - Real-time insights into bookings and temple operations
- ⚙️ **Slot Management** - Configure available time slots and temple capacity
- 👥 **User Management** - Manage devotee accounts and registrations
- 📈 **Reports & Analytics** - Comprehensive booking reports and statistics
- 🔐 **Admin Controls** - Full control over booking policies and temple settings
- 📬 **Communication Tools** - Send notifications to devotees

### Technical Excellence
- ⚡ **High Performance** - Optimized for speed and responsiveness
- 🔒 **Secure** - Enterprise-level security for user data and payments
- 🌐 **Scalable Architecture** - Built to handle growing user base
- 📱 **Mobile-First** - Progressive Web App capabilities
- 🎨 **Modern UI/UX** - Professional and intuitive interface

## 🛠️ Tech Stack

The Divine project is built with modern web technologies:
- **Frontend**: React/Next.js with TypeScript
- **Backend**: Node.js/Express.js or similar backend framework
- **Database**: MongoDB/PostgreSQL
- **Styling**: Tailwind CSS / CSS Modules
- **Authentication**: JWT-based secure authentication
- **Payment Integration**: Stripe/Razorpay integration
- **Deployment**: Vercel (Frontend) + Server hosting

## 📋 Prerequisites

Before setting up the project, ensure you have:
- Node.js (v16 or higher)
- npm or yarn package manager
- Git
- Database credentials (MongoDB/PostgreSQL)
- Payment gateway API keys

## 🚀 Getting Started

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Varunmattur/Divine.git
   cd Divine
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure environment variables**
   ```bash
   cp .env.example .env.local
   # Edit .env.local with your configuration
   ```

4. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open in browser**
   - Navigate to `http://localhost:3000`

## 📁 Project Structure

```
Divine/
├── public/                 # Static assets and public files
├── src/
│   ├── components/         # Reusable React components
│   │   ├── Booking/        # Slot booking components
│   │   ├── Calendar/       # Calendar interface
│   │   ├── Admin/          # Admin dashboard components
│   │   └── Common/         # Shared components
│   ├── pages/              # Next.js page routes
│   │   ├── api/            # Backend API routes
│   │   ├── admin/          # Admin pages
│   │   └── bookings/       # Booking pages
│   ├── styles/             # Global and component styles
│   ├── lib/                # Utility functions
│   │   ├── api/            # API integration
│   │   ├── auth/           # Authentication logic
│   │   └── database/       # Database connection
│   ├── types/              # TypeScript type definitions
│   └── App.tsx             # Root application component
├── .env.example            # Environment variables template
├── package.json            # Project dependencies
├── tsconfig.json           # TypeScript configuration
└── README.md               # This file
```

## 🎯 Core Functionalities

### Booking Module
- Real-time slot availability check
- Multiple date/time selection
- Automatic slot occupancy management
- Booking confirmation and receipt generation

### User Management
- Registration and authentication
- Email verification
- Profile management
- Booking history and cancellations

### Payment Integration
- Secure payment processing
- Multiple payment methods
- Invoice generation
- Payment history tracking

### Admin Dashboard
- Overview statistics
- Booking management
- User analytics
- Slot configuration
- System settings

## 🚀 Building for Production

```bash
npm run build
# or
yarn build
```

This creates an optimized production build ready for deployment.

## 📦 Deployment

### Frontend Deployment (Vercel)
```bash
npm run deploy
# or manually push to Vercel connected GitHub repo
```

### Environment Variables for Production
```
NEXT_PUBLIC_API_URL=your_api_url
DATABASE_URL=your_database_url
JWT_SECRET=your_jwt_secret
PAYMENT_KEY=your_payment_gateway_key
SMTP_HOST=your_smtp_host
SMTP_USER=your_email
SMTP_PASS=your_email_password
```

## 🔐 Security Features

- ✅ Password hashing and encryption
- ✅ JWT-based authentication
- ✅ CORS protection
- ✅ SQL injection prevention
- ✅ XSS protection
- ✅ HTTPS enforcement
- ✅ Rate limiting on API endpoints
- ✅ Secure payment processing

## 🧪 Testing

```bash
# Run unit tests
npm run test

# Run integration tests
npm run test:integration

# Generate coverage report
npm run test:coverage
```

## 📝 API Documentation

### Key Endpoints

**Authentication**
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `POST /api/auth/logout` - User logout

**Bookings**
- `GET /api/slots` - Get available slots
- `POST /api/bookings` - Create new booking
- `GET /api/bookings/:id` - Get booking details
- `PUT /api/bookings/:id` - Update booking
- `DELETE /api/bookings/:id` - Cancel booking

**Admin**
- `GET /api/admin/dashboard` - Dashboard stats
- `GET /api/admin/users` - List users
- `GET /api/admin/bookings` - List all bookings
- `POST /api/admin/slots` - Create slots

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📋 Project Status

✅ **Production Ready** - This project has been fully developed and delivered to the client with all requirements implemented.

**Latest Features:**
- Complete slot booking workflow
- Automated notification system
- Payment gateway integration
- Advanced admin dashboard
- Mobile-responsive design

## 📞 Support & Contact

For issues, feature requests, or support:
- 📧 Open an [Issue](https://github.com/Varunmattur/Divine/issues)
- 💬 Create a [Discussion](https://github.com/Varunmattur/Divine/discussions)

## 📄 License

This project is developed as a client project. Please refer to the LICENSE file for usage rights and restrictions.

## 🙏 Acknowledgments

- Developed according to client specifications
- Built with modern web standards
- Dedicated to providing excellent temple management solutions
- All stakeholders and testers who contributed

---

**Made with ❤️ by [Varunmattur](https://github.com/Varunmattur)**

**Project Status**: ✅ Production Deployed  
**Live Website**: 🌐 [https://divine-ruddy.vercel.app](https://divine-ruddy.vercel.app)  
*Last Updated: May 2026*