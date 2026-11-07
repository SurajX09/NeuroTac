# Lead Generation Website

A modern, responsive, single-page lead generation website designed to attract potential customers, showcase services, and generate enquiries directly through WhatsApp.

## 🚀 Project Overview

This project provides a clean and professional landing page where visitors can explore services, understand the process, get answers to common questions, and contact the business through WhatsApp.

The website focuses on simplicity, performance, accessibility, and conversion.

## ✨ Features

- **Single-Page Website:** All important sections on one page.
- **Multilingual Support:** English, Hindi, and Marathi.
- **Dark & Light Mode:** Theme switching with saved preference.
- **Responsive Design:** Optimized for desktop, tablet, and mobile.
- **WhatsApp Integration:** Contact form redirects users to WhatsApp with a pre-filled enquiry message.
- **Services Section:** Display available services and offerings.
- **Why Choose Us:** Highlight business advantages and customer benefits.
- **How It Works:** Explain the customer journey step by step.
- **FAQ Section:** Expandable frequently asked questions.
- **Smooth Scrolling:** Easy navigation between sections.
- **Scroll Animations:** Subtle animations for an engaging experience.

## 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- WhatsApp Click-to-Chat API

No frameworks or external JavaScript libraries are required.

## 📁 Project Structure

```text
lead-generation-website/
│
├── index.html
└── README.md
```

The current implementation keeps HTML, CSS, and JavaScript together in a single HTML file.

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Open the Project

```bash
cd lead-generation-website
```

### 3. Run the Website

Open `index.html` directly in your browser.

You can also use the Live Server extension in VS Code.

## 📲 Configure WhatsApp Integration

Open `index.html` and find:

```javascript
const WHATSAPP_NUMBER = "91XXXXXXXXXX";
```

Replace the placeholder with your WhatsApp number, including the country code.

Example:

```javascript
const WHATSAPP_NUMBER = "919876543210";
```

Do not include `+`, spaces, or hyphens.

When a visitor submits the contact form, WhatsApp opens with a pre-filled enquiry message.

## 🎨 Customization

You can customize the website by editing:

- **Branding:** Website name, logo, and business details.
- **Services:** Update service names and descriptions.
- **Content:** Modify hero text, FAQs, and contact information.
- **Languages:** Update English, Hindi, and Marathi translations.
- **Theme:** Customize dark and light theme colors.
- **WhatsApp:** Configure your business WhatsApp number.

## 📱 Responsive Design

The website is designed to work across:

- Desktop computers
- Laptops
- Tablets
- Smartphones

## 🔒 Important Note

This is a frontend-only project.

- No backend server is required.
- No database is connected.
- Customer enquiries are sent through WhatsApp.
- Form submissions are not automatically stored in a database.

## 🚀 Future Enhancements

- Backend API integration.
- Database storage for customer enquiries.
- Admin dashboard for lead management.
- Email and Telegram notifications.
- Lead tracking and analytics.
- SEO optimization.
- Additional language support.

## 📄 License

This project is currently intended for personal and business use. Add an appropriate open-source license if you decide to distribute it publicly.

---

**Built with ❤️ using HTML, CSS, and Vanilla JavaScript.**
