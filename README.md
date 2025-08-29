# ColorStack WashU Chapter Website

A modern, responsive website for the ColorStack chapter at Washington University in St. Louis.

## 🚀 Features

- **Responsive Design** - Works perfectly on all devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Smooth Scrolling** - Elegant navigation between sections
- **Contact Form** - Easy way for students to get in touch
- **Event Showcase** - Display upcoming events and activities
- **Resource Hub** - Central location for study materials and career resources

## 📁 File Structure

```
colorstack-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Color Scheme

The website uses a professional color palette:
- **Primary Purple**: #6b46c1 (ColorStack brand color)
- **Dark Grey**: #2d3748 (Text and headings)
- **Medium Grey**: #4a5568 (Secondary text)
- **Light Grey**: #f7fafc (Backgrounds)
- **White**: #ffffff (Content areas)

## 🛠️ How to Use

### 1. Open the Website
Simply open `index.html` in any modern web browser. The website will work immediately without any server setup.

### 2. Customize Content
Edit the `index.html` file to update:
- Chapter information and statistics
- Event details and dates
- Contact information
- Resource links
- Social media handles

### 3. Modify Styling
Edit `styles.css` to change:
- Colors and fonts
- Layout and spacing
- Animations and effects
- Responsive breakpoints

### 4. Add Functionality
Edit `script.js` to add:
- Form submission handling
- Additional animations
- Interactive features
- Analytics tracking

## 📱 Responsive Design

The website automatically adapts to different screen sizes:
- **Desktop**: Full layout with side-by-side content
- **Tablet**: Adjusted grid layouts
- **Mobile**: Single-column layout with mobile navigation

## 🔧 Customization Guide

### Updating Events
Find the events section in `index.html` and modify the event cards:

```html
<div class="event-card">
    <div class="event-date">
        <span class="month">JAN</span>
        <span class="day">25</span>
    </div>
    <div class="event-content">
        <h3>Your Event Title</h3>
        <p>Event description goes here.</p>
        <div class="event-meta">
            <span><i class="fas fa-clock"></i> 6:00 PM</span>
            <span><i class="fas fa-map-marker-alt"></i> Location</span>
        </div>
    </div>
</div>
```

### Changing Colors
Update the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6b46c1;
    --secondary-color: #4a5568;
    --accent-color: #2d3748;
}
```

### Adding New Sections
Create new sections by following the existing pattern:

```html
<section id="new-section" class="new-section">
    <div class="container">
        <h2 class="section-title">Section Title</h2>
        <!-- Your content here -->
    </div>
</section>
```

## 🚀 Deployment Options

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload your website files
3. Enable GitHub Pages in repository settings
4. Your site will be available at `username.github.io/repository-name`

### Option 2: Netlify (Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your website folder
3. Get a free subdomain (e.g., `your-site.netlify.app`)

### Option 3: Vercel (Free)
1. Go to [vercel.com](https://vercel.com)
2. Connect your GitHub repository
3. Deploy automatically with every update

## 📧 Contact Form Setup

The contact form currently shows a success message. To make it functional:

1. **Use a form service** like Formspree, Netlify Forms, or Google Forms
2. **Set up a backend** with Node.js, Python, or PHP
3. **Use email services** like SendGrid or AWS SES

Example with Formspree:
```html
<form action="https://formspree.io/f/your-form-id" method="POST">
    <!-- form fields -->
</form>
```

## 🎯 Next Steps

1. **Add Real Content** - Replace placeholder text with your chapter's information
2. **Upload Images** - Add photos of your members and events
3. **Connect Social Media** - Update links to your actual social accounts
4. **Set Up Analytics** - Add Google Analytics or similar tracking
5. **Domain Name** - Purchase a custom domain (e.g., `colorstackwustl.com`)

## 🤝 Contributing

This website is designed to be easily customizable. Feel free to:
- Modify the design to match your chapter's branding
- Add new sections for specific needs
- Improve the mobile experience
- Add more interactive features

## 📞 Support

If you need help customizing your website:
- Check the HTML comments for guidance
- Review the CSS structure for styling changes
- Test changes in your browser's developer tools
- Use browser developer tools to inspect elements

## 🌟 Features You Can Add

- **Member Directory** - Showcase your chapter members
- **Photo Gallery** - Display event photos and memories
- **Blog/News** - Share updates and announcements
- **Calendar Integration** - Sync with Google Calendar
- **Social Media Feed** - Display recent posts
- **Donation/Support** - Accept contributions
- **Application Forms** - For new member applications

---

**Built with ❤️ for the ColorStack WashU Chapter**

*Empowering underrepresented students in tech through community, mentorship, and professional development.*


