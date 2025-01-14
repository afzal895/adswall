# Ads.Wall - Your Trusted Platform for Displaying Ads

Ads.Wall is an online platform that allows businesses and individuals to display ads on a trusted, high-traffic website. The platform offers various ad slots that can be purchased through easy-to-use features and seamless payment methods.

## Features

- **Homepage**: A welcoming page introducing the platform and offering easy navigation to different sections.
- **Buy Ad Slot Page**: Users can view different ad packages and buy ad slots with an integrated payment gateway.
- **Payment Page**: Includes payment information through UPI (Unified Payments Interface) and an optional QR code for easy payments.
- **Ads Display Page**: A dedicated page showcasing featured advertisements.
- **Contact Page**: A simple contact form to reach out to Ads.Wall for inquiries.

## How It Works

1. **Browse Ads**: Users can browse featured ads on the homepage and explore available ad packages.
2. **Buy Ad Slot**: Users can choose from different ad packages and make payments to purchase an ad slot.
3. **Payment**: Payment can be done via UPI or through a Razorpay integration (for future use).
4. **Get Confirmation**: After payment, users will receive an email confirmation and the ad will be displayed as per the chosen package.

## Pages

1. **Home** (`index.html`): Main landing page showcasing Ads.Wall features.
2. **About** (`about.html`): Details about Ads.Wall and how it helps businesses.
3. **Ads** (`ads.html`): Display of featured advertisements on the website.
4. **Contact** (`contact.html`): A contact page to get in touch with Ads.Wall.
5. **Payment** (`payment.html`): Payment instructions using UPI ID and QR code.
6. **Buy Slot** (`buy-slot.html`): Page to purchase ad slots with integrated payment gateway.
7. **Style Sheet** (`styles.css`): Contains the styling for all pages.

## Payment Integration

For seamless payments, Ads.Wall integrates **Razorpay** for purchasing ad slots. In addition, UPI details are available for direct payments. Once payment is successful, users will receive an email notification confirming their ad slot purchase.

### Razorpay Integration

The `buy-slot.html` page includes the integration of Razorpay, where users can select ad packages and proceed with payments. The payment handler function is defined to capture the response after the transaction.

### UPI Payment

Users can also pay through UPI by using the provided UPI ID `afzalismayel459-2@okhdfcbank` and scan the QR code.

## Technologies Used

- **HTML5**: Structure of the website.
- **CSS3**: Styling of the website.
- **JavaScript**: For Razorpay integration and payment handling.
- **Razorpay**: Payment gateway integration.
- **UPI**: Payment system integration for direct transfers.
- **GitHub Pages**: For hosting the website.

## How to Run Locally

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/<your-github-username>/adswall.git
