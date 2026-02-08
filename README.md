# CRUNCH - Home Services Marketplace

A modern, interactive marketplace platform connecting homeowners with trusted local service professionals.

## Features

✨ **Service Provider Listings** - Browse professionals by category with detailed profiles
📅 **Booking System** - Complete 3-step booking workflow
💳 **Payment Processing** - Integrated payment interface
⭐ **Reviews & Ratings** - Customer feedback system
🔧 **Admin Panel** - Full CRUD operations for managing service providers

## Quick Start - Deploy to Vercel

### Option 1: Deploy via Vercel CLI (Recommended)

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm install -g vercel
   ```

2. **Navigate to this folder** in your terminal

3. **Run the deploy command**:
   ```bash
   vercel
   ```

4. **Follow the prompts**:
   - Login to your Vercel account (or create one)
   - Confirm the project settings
   - Wait for deployment to complete

5. **Your site is live!** Vercel will provide you with a URL like:
   ```
   https://crunch-marketplace.vercel.app
   ```

### Option 2: Deploy via Vercel Dashboard

1. Go to [vercel.com](https://vercel.com) and sign up/login
2. Click "Add New..." → "Project"
3. Import this folder or drag-and-drop these files
4. Click "Deploy"
5. Done! Your site will be live in seconds

### Option 3: Deploy from GitHub

1. Create a new GitHub repository
2. Upload all files from this folder to the repo
3. Go to [vercel.com](https://vercel.com) and click "Import Project"
4. Connect your GitHub account and select your repo
5. Click "Deploy"

## Files Included

- `index.html` - Main application file (complete React app)
- `vercel.json` - Vercel configuration
- `package.json` - Project metadata
- `README.md` - This file

## Admin Access

Once deployed, click the "🔒 Admin" button in the top-right corner to:
- Add new service providers
- Edit existing providers
- Delete providers
- Manage all listings

## Technologies Used

- React 18
- Tailwind CSS
- Vanilla JavaScript
- HTML5

## Notes

- This is a frontend-only prototype
- Data is stored in browser memory (resets on refresh)
- To add real database persistence, you'll need to integrate a backend
- Payment processing is simulated (not real transactions)

## Custom Domain (Optional)

To use your own domain (e.g., crunch.com):
1. Purchase a domain from any registrar
2. In Vercel dashboard, go to your project settings
3. Add your custom domain
4. Update your DNS records as instructed by Vercel

## Support

For issues or questions about deployment:
- Vercel Docs: https://vercel.com/docs
- Vercel Support: https://vercel.com/support

---

Built with ❤️ for connecting homeowners with trusted professionals
