# RoseTECH Consulting Static Site

A simple one-page website with a contact form for RoseTECH Consulting, Inc.

## Deploying to GitHub Pages

1. **Create a new GitHub repository**
   - Go to GitHub and create a new repository
   - Name it something like `rostetech-static` or `<your-username>.github.io`

2. **Push your code**

   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be available at `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## Setting Up the Contact Form

The current form logs submissions to the console. To actually receive emails, you'll need to integrate with a form service:

### Option 1: Formspree (Recommended)

1. Sign up at [Formspree.io](https://formspree.io)
2. Create a new form and get your form ID
3. In `index.html`, uncomment the Formspree code section and replace `YOUR_FORM_ID`

### Option 2: EmailJS

1. Sign up at [EmailJS.com](https://www.emailjs.com)
2. Follow their setup guide
3. Add EmailJS SDK and configure

### Option 3: Netlify Forms

If you deploy to Netlify instead of GitHub Pages, you can use Netlify Forms for free.

## Local Testing

Simply open `index.html` in your browser to test locally.

## Features

- ✅ Responsive design
- ✅ Clean, modern UI
- ✅ Form validation
- ✅ Accessible (skip to content, proper labels)
- ✅ Mobile-friendly
- ✅ Ready for GitHub Pages

## Customization

- Edit colors in the CSS section
- Modify form fields as needed
- Update company name and tagline
- Add your logo by inserting an `<img>` tag in the header
