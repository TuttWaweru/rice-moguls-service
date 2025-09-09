# Rice Moguls LLC - Website & App Blueprint

## Project Goals

*   Market and sell premium pure Basmati (Pishori) rice in Kenya and the USA.
*   Offer localized pricing and payment (M-Pesa for Kenya, USD/Credit Cards for US).
*   Showcase the rice journey - from field to table - via media-rich content.
*   Build trust and engagement through customer reviews and transparent sourcing.

## Website Structure (Responsive, SEO-Optimized)

### 1. Homepage

*   **Hero banner:** Scenic rice fields at sunrise with tagline: “Pure Basmati. Farm to Table. Kenya to the World."
*   **Quick Shop CTA:** "Shop Now →" 
*   **Dual currency toggle:** KES/USD (auto-detected by IP or manual switch)
*   **Featured Products:** Best-selling rice packs (1kg, 5kg, 25lb, etc.)
*   **Trust Badges:** "100% Pure Pishori", "Ethically Sourced", "M-Pesa & Card Accepted"

### 2. About Us

*   Story of Rice Moguls LLC: Founding, mission, commitment to quality.
*   Farmer partnerships in Kenya.
*   Sustainability and ethical sourcing practices.
*   Team photos + short bios.

### 3. Products

*   **Filter by:** Weight (kg/lb), Type (Basmati / Pishori), Pack Size.
*   **Each product card includes:**
    *   High-res image
    *   Price in KES & USD (e.g., KSh 350/kg - $2.80/lb)
    *   "Add to Cart" button
    *   "Origin: Mwea, Kenya" badge
    *   Nutritional info & cooking tips toggle
*   Auto-convert prices based on visitor location or selected currency.

### 4. Gallery & Media

*   **Photo Gallery**
    *   Sections:
        *   Field Preparation - Plowing, flooding, planting seedlings
        *   Growing Season - Lush green fields, drone shots
        *   Harvesting - Manual & mechanical harvest, workers in fields
        *   Processing - Threshing, drying, milling, quality control
        *   Packaging - Sealing, labeling, boxing for export/local
        *   Final Product - Beautiful bowls of cooked rice, packaging close-ups
*   **Video Gallery**
    *   2-3min documentary: "The Journey of a Grain - From Kenyan Soil to Your Table"
    *   Behind-the-scenes: Packaging facility tour
    *   Customer testimonials (video clips)
    *   Cooking tutorials using Rice Moguls Basmati

### 5. Reviews & Testimonials

*   Star ratings + written reviews (with photo/video option).
*   Filter by: Kenya/US/All
*   Verified buyer badges
*   "Submit Your Review" form (with photo/video upload)
*   Featured reviews on homepage carousel

### 6. How to Buy / Order

*   **For Kenya:**
    *   M-Pesa Integration (Lipa Na M-Pesa via Till Number or Paybill)
    *   Delivery via G4S, Sendy, or pickup points in Nairobi, Mombasa, Kisumu
    *   SMS order confirmation + tracking
*   **For USA:**
    *   Stripe/PayPal/ApplePay/Google Pay
    *   Shipping via FedEx/USPS (2-5 business days)
    *   Free shipping over $50
*   **Cart shows:**
    *   Subtotal in local currency
    *   Delivery estimate
    *   Payment method selector

### 7. Blog / Recipes

*   "Perfect Basmati Every Time” guide
*   Kenyan Pilau Recipe
*   American Fried Rice Twist
*   Health Benefits of Basmati Rice

### 8. Contact & Support

*   WhatsApp Chat (Kenya)
*   Email & Contact Form (Global)
*   FAQ Section
*   Return & Refund Policy
*   Business Inquiries (Wholesale, Partnerships)

## Mobile App (iOS & Android)

### Features:

*   Push Notifications: New harvest alerts, promo codes, restocks
*   Currency Auto-Detect: Based on device region or manual override
*   M-Pesa SDK Integration (Kenya only) - Seamless in-app payments
*   Wishlist & Order History
*   Offline Mode: Browse products and gallery without internet
*   AR Feature: Point camera at rice bag to see origin story + farmer video
*   Loyalty Program: Earn “Grain Points" for reviews/referrals → redeem discounts
*   Secure login via Google, Apple, or Phone (OTP for Kenya)

## Pricing Strategy

| WEIGHT | KENYA(KES) | USA(USD) |
| :----- | :--------- | :------- |
| 1kg    | KSh350     | $2.80    |
| 2kg    | KSh650     | $5.20    |
| 5kg    | KSh1,500   | $12.00   |
| 10kg   | KSh2,800   | $22.40   |
| 1lb    |            | $1.27    |
| 5lb    |            | $6.00    |
| 25lb   |            | $28.00   |

*Bulk/wholesale discounts available on request.*

## Technology Stack

### Website:

*   **Frontend:** React.js + Tailwind CSS
*   **Backend:** Node.js + Express
*   **CMS:** Strapi (for blogs, media, reviews)
*   **Payments:** M-Pesa API (Daraja) + Stripe
*   **Hosting:** Vercel + AWS S3 (for media)
*   **Analytics:** Google Analytics + Hotjar

### Mobile App:

*   **Framework:** React Native
*   **State Management:** ReduxToolkit
*   **M-Pesa:** Daraja API (STKPush)
*   **Push Notifications:** Firebase Cloud Messaging
*   **Database:** Firebase Firestore + PostgreSQL (orders/users)

## SEO & Marketing

*   **Keywords:** “Buy Basmati rice Kenya”, “Pishori rice USA”, “Authentic Kenyan rice online”
*   Google Shopping Ads + Facebook/Instagram targeting foodies, Kenyan diaspora
*   Influencer collabs: Kenyan chefs, US food bloggers
*   Email Newsletter: Recipes, harvest updates, exclusive discounts

## Launch Roadmap

| PHASE   | TIMELINE | TASKS                                                                 |
| :------ | :------- | :-------------------------------------------------------------------- |
| Month 1 |          | Design UX, setup infrastructure, M-Pesa & Stripe integration    |
| Month 2 |          | Populate gallery/media, onboard farmers for content             |
| Month 3 |          | Beta test with 100 users in Kenya & US                         |
| Month 4 |          | Launch website + app, run promo campaign                        |
| Month 5 | Ongoing  | Collect reviews, optimize SEO, add seasonal products           |

## Legal & Compliance

*   **Kenya:** KEBS Certification, KRA Tax Compliance
*   **USA:** FDA Registration, USDA Organic (if applicable), Import Permits
*   Privacy Policy + Terms of Service (GDPR & CCPA compliant)
*   Secure payment gateways with PCI-DSS compliance

## Bonus Ideas

*   "Adopt-a-Row" Program: Sponsor a rice row in Kenya → get updates + free bag
*   Subscription Box: Monthly rice delivery + recipe cards + spice packs
*   QR Code on Packaging: Scan to see which farm your rice came from + farmer message

## Final Touch

At Rice Moguls LLC, every grain tells a story—of sun-renched Kenyan fields, of generations of farming wisdom, and of your table, waiting to be filled with the aroma of pure, perfect Basmati.
