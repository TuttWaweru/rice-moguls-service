# Rice Moguls LLC - Website & App Blueprint

## Project Goals

*   Market and sell premium pure Basmati (Pishori) rice in Kenya and the USA[^3].
*   Offer localized pricing and payment (M-Pesa for Kenya, USD/Credit Cards for US)[^3].
*   Showcase the rice journey - from field to table - via media-rich content[^3].
*   Build trust and engagement through customer reviews and transparent sourcing[^3].

## Website Structure (Responsive, SEO-Optimized)

### 1. Homepage

*   **Hero banner:** Scenic rice fields at sunrise with tagline: “Pure Basmati. Farm to Table. Kenya to the World."[^3,^4]
*   **Quick Shop CTA:** "Shop Now →" [^3,^4]
*   **Dual currency toggle:** KES/USD (auto-detected by IP or manual switch)[^3,^4]
*   **Featured Products:** Best-selling rice packs (1kg, 5kg, 25lb, etc.)[^3,^4]
*   **Trust Badges:** "100% Pure Pishori", "Ethically Sourced", "M-Pesa & Card Accepted" [^4]

### 2. About Us

*   Story of Rice Moguls LLC: Founding, mission, commitment to quality[^4].
*   Farmer partnerships in Kenya[^4].
*   Sustainability and ethical sourcing practices[^4].
*   Team photos + short bios[^4].

### 3. Products

*   **Filter by:** Weight (kg/lb), Type (Basmati / Pishori), Pack Size[^5].
*   **Each product card includes:**
    *   High-res image[^5]
    *   Price in KES & USD (e.g., KSh 350/kg - $2.80/lb)[^5]
    *   "Add to Cart" button[^5]
    *   "Origin: Mwea, Kenya" badge[^5]
    *   Nutritional info & cooking tips toggle[^5]
*   Auto-convert prices based on visitor location or selected currency[^5].

### 4. Gallery & Media

*   **Photo Gallery**[^5,^6]
    *   Sections:
        *   Field Preparation - Plowing, flooding, planting seedlings[^5,^6]
        *   Growing Season - Lush green fields, drone shots[^6]
        *   Harvesting - Manual & mechanical harvest, workers in fields[^6]
        *   Processing - Threshing, drying, milling, quality control[^6]
        *   Packaging - Sealing, labeling, boxing for export/local[^6]
        *   Final Product - Beautiful bowls of cooked rice, packaging close-ups[^6]
*   **Video Gallery**[^6]
    *   2-3min documentary: "The Journey of a Grain - From Kenyan Soil to Your Table"[^6]
    *   Behind-the-scenes: Packaging facility tour[^6]
    *   Customer testimonials (video clips)[^6]
    *   Cooking tutorials using Rice Moguls Basmati[^6]

### 5. Reviews & Testimonials

*   Star ratings + written reviews (with photo/video option)[^7].
*   Filter by: Kenya/US/All[^7]
*   Verified buyer badges[^7]
*   "Submit Your Review" form (with photo/video upload)[^7]
*   Featured reviews on homepage carousel[^7]

### 6. How to Buy / Order

*   **For Kenya:**[^7]
    *   M-Pesa Integration (Lipa Na M-Pesa via Till Number or Paybill)[^7]
    *   Delivery via G4S, Sendy, or pickup points in Nairobi, Mombasa, Kisumu[^7]
    *   SMS order confirmation + tracking[^7]
*   **For USA:**[^7,^8]
    *   Stripe/PayPal/ApplePay/Google Pay[^8]
    *   Shipping via FedEx/USPS (2-5 business days)[^8]
    *   Free shipping over $50[^8]
*   **Cart shows:**[^8]
    *   Subtotal in local currency[^8]
    *   Delivery estimate[^8]
    *   Payment method selector[^8]

### 7. Blog / Recipes

*   "Perfect Basmati Every Time” guide[^8]
*   Kenyan Pilau Recipe[^8]
*   American Fried Rice Twist[^8]
*   Health Benefits of Basmati Rice[^8]

### 8. Contact & Support

*   WhatsApp Chat (Kenya)[^9]
*   Email & Contact Form (Global)[^9]
*   FAQ Section[^9]
*   Return & Refund Policy[^9]
*   Business Inquiries (Wholesale, Partnerships)[^9]

## Mobile App (iOS & Android)

### Features:

*   Push Notifications: New harvest alerts, promo codes, restocks[^9,^10]
*   Currency Auto-Detect: Based on device region or manual override[^9,^10]
*   M-Pesa SDK Integration (Kenya only) - Seamless in-app payments[^9,^10]
*   Wishlist & Order History[^9,^10]
*   Offline Mode: Browse products and gallery without internet[^9,^10]
*   AR Feature: Point camera at rice bag to see origin story + farmer video[^10]
*   Loyalty Program: Earn “Grain Points" for reviews/referrals → redeem discounts[^10]
*   Secure login via Google, Apple, or Phone (OTP for Kenya)[^10,^11]

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

*Bulk/wholesale discounts available on request.*[^11]

## Technology Stack

### Website:

*   **Frontend:** React.js + Tailwind CSS[^12]
*   **Backend:** Node.js + Express[^12]
*   **CMS:** Strapi (for blogs, media, reviews)[^12]
*   **Payments:** M-Pesa API (Daraja) + Stripe[^12]
*   **Hosting:** Vercel + AWS S3 (for media)[^12]
*   **Analytics:** Google Analytics + Hotjar[^12]

### Mobile App:

*   **Framework:** React Native[^12,^13]
*   **State Management:** ReduxToolkit[^12,^13]
*   **M-Pesa:** Daraja API (STKPush)[^12,^13]
*   **Push Notifications:** Firebase Cloud Messaging[^12,^13]
*   **Database:** Firebase Firestore + PostgreSQL (orders/users)[^13]

## SEO & Marketing

*   **Keywords:** “Buy Basmati rice Kenya”, “Pishori rice USA”, “Authentic Kenyan rice online”[^13]
*   Google Shopping Ads + Facebook/Instagram targeting foodies, Kenyan diaspora[^13]
*   Influencer collabs: Kenyan chefs, US food bloggers[^13]
*   Email Newsletter: Recipes, harvest updates, exclusive discounts[^13]

## Launch Roadmap

| PHASE   | TIMELINE | TASKS                                                                 |
| :------ | :------- | :-------------------------------------------------------------------- |
| Month 1 |          | Design UX, setup infrastructure, M-Pesa & Stripe integration[^14]    |
| Month 2 |          | Populate gallery/media, onboard farmers for content[^14]             |
| Month 3 |          | Beta test with 100 users in Kenya & US[^14]                         |
| Month 4 |          | Launch website + app, run promo campaign[^14]                        |
| Month 5 | Ongoing  | Collect reviews, optimize SEO, add seasonal products[^14]           |

## Legal & Compliance

*   **Kenya:** KEBS Certification, KRA Tax Compliance[^14,^15]
*   **USA:** FDA Registration, USDA Organic (if applicable), Import Permits[^14,^15]
*   Privacy Policy + Terms of Service (GDPR & CCPA compliant)[^15]
*   Secure payment gateways with PCI-DSS compliance[^15]

## Bonus Ideas

*   "Adopt-a-Row" Program: Sponsor a rice row in Kenya → get updates + free bag[^15]
*   Subscription Box: Monthly rice delivery + recipe cards + spice packs[^15]
*   QR Code on Packaging: Scan to see which farm your rice came from + farmer message[^15]

## Final Touch

At Rice Moguls LLC, every grain tells a story—of sun-renched Kenyan fields, of generations of farming wisdom, and of your table, waiting to be filled with the aroma of pure, perfect Basmati[^15,^16].
