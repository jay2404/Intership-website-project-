# InternLearn - College Internship Platform 🎓

A modern, responsive website designed for college students to explore and apply for real-time project-based internships with live learning sessions and expert mentorship.

![InternLearn Banner](https://img.shields.io/badge/Status-Live-success) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🌟 Overview

InternLearn is a static website platform that connects college students with industry-level internship opportunities. Students can work on real projects while receiving live training and query support from experienced mentors.

## 🚀 Live Demo

Visit the live website: [Your GitHub Pages URL]

## ✨ Features

- **📱 Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **🎯 Three Internship Programs:**
  - Data Analyst (8 weeks)
  - Python Developer (10 weeks)
  - React Native Developer (10 weeks)
- **👨‍🏫 Instructor Profiles** - Meet our experienced mentors from top companies
- **📝 Google Form Integration** - Easy registration process with responses saved to Google Sheets
- **🎨 Modern UI/UX** - Gradient backgrounds, smooth animations, and interactive elements
- **⚡ Fast & Lightweight** - Pure HTML, CSS, and JavaScript (no frameworks required)
- **🔄 Smooth Scrolling** - Enhanced navigation experience
- **💬 Interactive Modals** - Detailed program information on click

## 📋 Programs Offered

### 1. Data Analyst Internship
- Excel & SQL Fundamentals
- Data Visualization (Power BI/Tableau)
- Statistical Analysis & Python
- Real Business Case Studies
- Live Project on Market Analysis

### 2. Python Developer Internship
- Python Core & Advanced Concepts
- Web Development (Django/Flask)
- API Development & Integration
- Database Management
- Live Web Application Project

### 3. React Native Developer Internship
- JavaScript & React Fundamentals
- Mobile App Development
- State Management & Navigation
- API Integration & Firebase
- Live Mobile App Project

## 🛠️ Technology Stack

- **HTML5** - Structure and content
- **CSS3** - Styling with gradients, animations, and flexbox/grid
- **JavaScript (Vanilla)** - Interactive functionality and modal handling
- **Google Forms** - Student registration and data collection
- **Google Sheets** - Automatic response storage

## 📦 Installation & Setup

### Option 1: Direct Download
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/internlearn.git
   ```
2. Open `index.html` in your web browser

### Option 2: GitHub Pages Deployment
1. Fork this repository
2. Go to **Settings** → **Pages**
3. Select **main** branch and **/ (root)** folder
4. Click **Save**
5. Your site will be live at `https://your-username.github.io/internlearn`

### Option 3: Netlify (Fastest)
1. Visit [netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop your `index.html` file
3. Your site goes live instantly!

## 🔧 Configuration

### Google Form Integration

1. Create a Google Form at [forms.google.com](https://forms.google.com)
2. Add fields:
   - Full Name
   - Email Address
   - Phone Number
   - College Name
   - Program Selection (Dropdown: Data Analyst, Python Developer, React Native)
   - Year of Study
   - Why do you want to join?

3. Link responses to Google Sheets
4. Click **Send** → Copy the form link
5. Update the JavaScript code in `index.html`:
   ```javascript
   // Line ~470 in the code
   const googleFormURL = 'YOUR_GOOGLE_FORM_LINK_HERE';
   ```
6. Uncomment line 479:
   ```javascript
   window.open(googleFormURL, '_blank');
   ```

### Adding Real Instructor Photos

1. Create an `images` folder in your repository
2. Add instructor photos (e.g., `rahul.jpg`, `priya.jpg`, etc.)
3. Update image sources in HTML:
   ```html
   <img src="images/rahul.jpg" alt="Rahul Sharma">
   ```

## 📁 Project Structure

```
internlearn/
├── index.html          # Main HTML file (contains CSS & JS)
├── README.md          # Project documentation
└── images/            # (Optional) Instructor photos folder
    ├── instructor1.jpg
    ├── instructor2.jpg
    └── ...
```

## 🎨 Customization

### Changing Colors
The website uses a purple gradient theme. To customize:

```css
/* Main gradient colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Change to your preferred colors */
background: linear-gradient(135deg, #YOUR_COLOR1 0%, #YOUR_COLOR2 100%);
```

### Updating Mentor Information
Edit the mentor cards in the HTML (around line 300):

```html
<div class="mentor-card">
    <div class="mentor-image">
        <img src="your-image-url" alt="Name">
    </div>
    <h3>Your Name</h3>
    <p class="designation">Your Title</p>
    <p class="company">Your Company</p>
    <p class="experience">X Years Experience</p>
    <p class="expertise">Expert in: Your Skills</p>
</div>
```

### Adding More Programs
Duplicate the program card structure and customize:

```html
<div class="program-card">
    <h3>🎯 Your Program</h3>
    <p><strong>Duration:</strong> X Weeks</p>
    <ul>
        <li>Feature 1</li>
        <li>Feature 2</li>
        <!-- Add more features -->
    </ul>
    <button class="apply-btn" onclick="openModal('your-program')">Apply Now</button>
</div>
```

## 📱 Responsive Breakpoints

- **Desktop:** 1200px and above
- **Tablet:** 768px - 1199px
- **Mobile:** Below 768px

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👥 Team

Created by **[Your Name/Organization]**

For inquiries: [your-email@example.com]

## 🐛 Bug Reports

Found a bug? Please open an issue with:
- Description of the bug
- Steps to reproduce
- Expected behavior
- Screenshots (if applicable)

## 📞 Support

Need help? Contact us:
- 📧 Email: support@internlearn.com
- 🌐 Website: [Your Website]
- 💬 Discord: [Your Discord Server]

## 🙏 Acknowledgments

- Design inspiration from modern landing pages
- Icons from emoji sets
- Avatar placeholders from [UI Avatars](https://ui-avatars.com/)

## 📈 Future Enhancements

- [ ] Add student testimonials section
- [ ] Implement FAQ accordion
- [ ] Add blog section for learning resources
- [ ] Create admin dashboard for managing applications
- [ ] Add email notifications for new registrations
- [ ] Integrate payment gateway for premium courses
- [ ] Add dark mode toggle

## 🔗 Useful Links

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Google Forms Guide](https://support.google.com/docs/answer/6281888)
- [Web Design Best Practices](https://www.w3.org/standards/webdesign/)

---

**⭐ If you find this project helpful, please give it a star!**

Made with ❤️ for college students aspiring to launch their tech careers
