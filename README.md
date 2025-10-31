# Join Rise & Reclaim - Official Website

**You've Survived the Fire. Now It's Time to Reclaim Your Life.**

A battle-tested survival path for those who've been knocked down, burned out, and are finally ready to rise with clarity, courage, and purpose.

## 🎯 Overview

Rise & Reclaim is the community membership division of Beacon Momentum, founded by Bob Burr (Digital Grandpa). This site serves as the marketing and signup page for the Rise & Reclaim community, offering $247/year membership with weekly live sessions, comprehensive resources, peer support, and accountability partnerships.

## 🔥 Features

- **Hero Section**: Powerful messaging for those who've survived their own fire
- **Pricing**: Clear $247/year membership with all features listed
- **Bob's Story**: Authentic credibility from someone who's lived the struggle
- **Community Features**: 6 core offerings (peer support, resources, skills, safe spaces, workshops, mentorship)
- **Mobile Mission 2026**: $70K raised toward $1M goal for mobile RV community center
- **Testimonials**: 3 diverse member stories (formerly incarcerated, veteran, recovery)
- **FAQ**: 5 common questions answered
- **Beacon v3.1 Design**: Professional branding matching ecosystem
- **Multiple CTAs**: Strategic join buttons throughout the page

## 🎨 Design System

### Colors
- **Primary Teal**: #0F766E (trust, stability, community)
- **Accent Gold**: #D97706 (hope, transformation, value)
- **Text Dark**: #1F2937
- **Text Light**: #6B7280
- **Background**: #FFFFFF, #F3F4F6

### Typography
- **Headings**: Playfair Display (serif, elegant, authoritative)
- **Body**: Inter (sans-serif, clean, readable)

### Brand Voice
- Battle-tested, not theory-based
- Authentic struggle and survival
- No shallow self-help or performative positivity
- Focus on community and belonging
- Phoenix/fire metaphor throughout

## 📁 Project Structure

```
joinriseandreclaim-v3/
├── index.html              # Main landing page
├── bob-profile-photo.jpg   # Bob Burr professional photo
├── README.md              # This file
└── DEPLOYMENT.md          # Deployment instructions (to be added)
```

## 🚀 Deployment

### Prerequisites
- Web hosting with HTML support
- Domain: joinriseandreclaim.com
- Stripe account (for payment processing)
- GoHighLevel account (for lead capture and follow-up)
- GitHub account (for version control)

### Quick Deploy
1. Upload all files to web root directory
2. Configure Stripe payment integration
3. Configure GoHighLevel forms
4. Test complete signup flow
5. Verify cross-links to Beacon ecosystem

### Automated Deployment
This site uses GitHub-based deployment with automatic sync to production server.

See `DEPLOYMENT.md` for detailed instructions.

## 🔗 Ecosystem Links

- **Beacon Momentum Hub**: https://beaconmomentum.com
- **Digital Grandpa**: https://digitalgrandpa.org
- **Beacon Labs Platform**: https://beaconmomentum.com/labs.html
- **Member Community**: https://riseandreclaim.community (to be migrated to beaconmomentum.community)

## 💳 Payment Integration

### Stripe Setup
The site has three join buttons ready for Stripe integration:
1. Navigation "JOIN THE COMMUNITY" button
2. Pricing section "JOIN RISE & RECLAIM - $247/YEAR" button
3. Final CTA "JOIN RISE & RECLAIM - $247/YEAR" button

All buttons currently show placeholder alerts. Replace with Stripe Checkout or Payment Links.

### Recommended Flow
1. User clicks join button
2. Stripe Checkout modal opens
3. User completes payment ($247/year)
4. Stripe webhook triggers
5. GoHighLevel creates contact
6. User receives welcome email with member portal access
7. User redirected to riseandreclaim.community

## 📝 Content Updates

### To Update Pricing
Edit the pricing section in `index.html` (search for "pricing-amount")

### To Update Community Features
Edit the features grid in `index.html` (search for "feature-card")

### To Update Mobile Mission Progress
Edit the mission section in `index.html` (search for "mission-stat-number")

### To Add/Update Testimonials
Edit the testimonials section in `index.html` (search for "testimonial-card")

### To Update FAQ
Edit the FAQ section in `index.html` (search for "faq-item")

## 🔌 Integrations

### Stripe (Payment Processing)
- Product: Rise & Reclaim Annual Membership
- Price: $247/year (recurring)
- Success URL: https://riseandreclaim.community/welcome
- Cancel URL: https://joinriseandreclaim.com#join

### GoHighLevel (CRM & Follow-up)
- Lead capture on page visit
- Contact creation on payment
- Welcome email sequence
- Weekly live session reminders
- Community engagement campaigns

### Member Platform
- riseandreclaim.community (current)
- beaconmomentum.community (future unified platform)

## 🛠️ Technical Details

- **Framework**: Pure HTML/CSS/JavaScript (no dependencies)
- **Responsive**: Mobile-first design, works on all devices
- **Performance**: Optimized images, minimal JavaScript
- **SEO**: Semantic HTML, meta tags, Open Graph
- **Accessibility**: ARIA labels, keyboard navigation
- **Stripe**: v3 JavaScript SDK loaded

## 📊 Performance

- **Page Size**: ~1MB (including Bob's photo)
- **Load Time**: <2 seconds on 3G
- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **Conversion Optimized**: Multiple CTAs, social proof, guarantee

## 🔒 Security

- HTTPS required for Stripe integration
- No sensitive data stored on frontend
- Payment processing handled by Stripe
- User data managed by GoHighLevel
- Member authentication handled by community platform

## 📊 Analytics & Tracking

### Recommended Events to Track
- Page views
- Join button clicks
- Scroll depth (engagement)
- Time on page
- Stripe checkout initiated
- Payment completed
- Member portal access

### Conversion Funnel
1. Landing page visit
2. Scroll to pricing
3. Click join button
4. Complete Stripe checkout
5. Access member portal
6. Attend first live session

## 📞 Support

- **Technical Issues**: GitHub Issues
- **Content Questions**: admin@beaconmomentum.com
- **Bob Burr**: bob@digitalgrandpa.org
- **Membership Support**: support@beaconmomentum.com

## 📜 License

© 2025 Rise & Reclaim | Part of Beacon Momentum | All rights reserved

## 🎯 Roadmap

- [ ] Integrate Stripe payment processing
- [ ] Connect GoHighLevel CRM
- [ ] Add email capture for non-buyers
- [ ] Create retargeting pixel integration
- [ ] Build testimonial video section
- [ ] Add live member count
- [ ] Create scholarship application form
- [ ] Build payment plan option

## 🎁 Special Offers

### Current Offer
- **Price**: $247/year
- **Guarantee**: 30-day satisfaction guarantee
- **Payment Plans**: Available (contact for details)
- **Scholarships**: Available for those in genuine need

### Future Offers
- Founding member pricing (if reintroduced)
- Quarterly payment option
- Lifetime membership tier
- Group/organization pricing

---

**Built with ❤️ by the Beacon Momentum team**

*Where Phoenix Moments Begin* 🔥

