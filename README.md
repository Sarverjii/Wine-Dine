# Wine & Dine Restaurant Website

A modern, responsive website for a fine dining restaurant featuring menu management, customer reviews, and an admin panel.

## 🌟 Features

### Public Features

- **Home Page**: Elegant landing page showcasing the restaurant's ambiance and key features
- **Menu Page**:
  - Interactive menu with categorized items
  - Search functionality to find specific dishes
  - Category filters for easy navigation
  - Beautiful image display for each menu item
  - Responsive grid layout
- **Reviews Section**:
  - Customer testimonials and ratings
  - Public review submission form
- **Contact Page**:
  - Contact form for customer inquiries
  - Location and contact information

### Admin Features

- **Secure Admin Panel**:
  - Protected login system
  - Dashboard for managing all aspects of the restaurant
- **Menu Management**:
  - Add, edit, and delete menu items
  - Categorize items (Salads, Sandwiches, Burgers, etc.)
  - Upload and manage item images
  - Set prices and descriptions
- **Review Management**:
  - Approve or reject customer reviews
  - Monitor customer feedback
- **Contact Management**:
  - View and respond to customer inquiries
  - Mark messages as read
  - Delete messages

## 🛠️ Technology Stack

- **Frontend**:

  - React.js
  - Material-UI (MUI) for UI components
  - React Router for navigation
  - Firebase for authentication and database
  - Cloudinary for image management

- **Styling**:
  - Material-UI theming
  - Custom CSS
  - Responsive design for all devices

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Firebase account
- Cloudinary account

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Sarverjii/Wine-Dine.git
cd WineAndDine
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file in the root directory with the following variables:

```env
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
VITE_FIREBASE_APP_ID=your_firebase_app_id
VITE_CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
VITE_CLOUDINARY_API_KEY=your_cloudinary_api_key
VITE_CLOUDINARY_API_SECRET=your_cloudinary_api_secret
VITE_CLOUDINARY_UPLOAD_PRESET=your_cloudinary_upload_preset
```

4. Start the development server:

```bash
npm run dev
```

## 📱 Responsive Design

The website is fully responsive and optimized for:

- Desktop computers
- Tablets
- Mobile phones

## 🔒 Security Features

- Protected admin routes
- Secure authentication
- Image upload validation
- Form validation
- XSS protection

## 🎨 Design Features

- Modern and elegant UI
- Consistent color scheme
- Playfair Display font for headings
- Smooth animations and transitions
- Intuitive navigation
- Clear typography hierarchy

## 📝 Menu Categories

The website supports the following menu categories:

- Salads
- Sandwiches
- Fries
- Burgers
- Sliders
- Pizza
- Pasta
- Garlic Bread
- Wraps
- Dumpling
- Chinese
- Deserts
- CheeseCake

## 🔄 Future Enhancements

Planned features for future updates:

- Online reservation system
- Online ordering system
- Special events calendar
- Newsletter subscription
- Social media integration
- Customer loyalty program

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- Your Name - Initial work

## 🙏 Acknowledgments

- Material-UI for the component library
- Firebase for backend services
- Cloudinary for image management
- All contributors who have helped shape this project
