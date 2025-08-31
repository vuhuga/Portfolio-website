# Portfolio Website Deployment Guide

## 🚀 Deploy to Render

### Step 1: Prepare Your Repository
1. Create a new repository on GitHub
2. Push all your portfolio files to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio website"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-portfolio.git
   git push -u origin main
   ```

### Step 2: Deploy on Render
1. Go to [render.com](https://render.com) and sign up/login
2. Click "New +" and select "Web Service"
3. Connect your GitHub repository
4. Configure the deployment:
   - **Name**: your-portfolio (or any name you prefer)
   - **Environment**: Node
   - **Build Command**: `npm install`
   - **Start Command**: `npm start`
   - **Instance Type**: Free (for personal use)

### Step 3: Environment Variables (Optional)
If you plan to add contact form functionality later, you might need:
- `NODE_ENV=production`

### Step 4: Custom Domain (Optional)
1. In your Render dashboard, go to your service
2. Click on "Settings"
3. Scroll to "Custom Domains"
4. Add your domain and follow DNS configuration instructions

## 🔧 Local Development

### Prerequisites
- Node.js (version 14 or higher)
- npm or yarn

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-portfolio.git
   cd your-portfolio
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start development server:
   ```bash
   npm run dev
   ```

4. Open your browser and visit `http://localhost:3000`

## 📝 Customization Checklist

### Personal Information
- [ ] Replace "Your Name" with your actual name
- [ ] Update email address in contact section
- [ ] Update phone number and location
- [ ] Add your profile picture to `images/profile.jpg`

### Content Updates
- [ ] Update the hero section description
- [ ] Modify the about section with your experience
- [ ] Update skills based on your expertise
- [ ] Replace project examples with your actual projects
- [ ] Update social media links

### Projects Section
- [ ] Replace placeholder projects with your actual work
- [ ] Add real GitHub repository links
- [ ] Add live demo links
- [ ] Update project descriptions and technologies used

### Styling (Optional)
- [ ] Customize color scheme in `styles.css`
- [ ] Modify fonts if desired
- [ ] Adjust layout spacing
- [ ] Add your personal branding

## 🌟 Features Included

- ✅ Responsive design (mobile-friendly)
- ✅ Modern CSS with animations
- ✅ Interactive navigation
- ✅ Contact form (frontend only)
- ✅ Smooth scrolling
- ✅ Professional layout
- ✅ SEO-friendly structure
- ✅ Fast loading times

## 🔮 Future Enhancements

Consider adding these features later:
- Contact form backend integration
- Blog section
- Dark mode toggle
- Analytics integration
- Performance optimizations
- Progressive Web App (PWA) features

## 📞 Support

If you encounter any issues during deployment:
1. Check Render's build logs for errors
2. Ensure all files are committed to your repository
3. Verify package.json dependencies
4. Check that your Node.js version is compatible

Happy coding! 🎉