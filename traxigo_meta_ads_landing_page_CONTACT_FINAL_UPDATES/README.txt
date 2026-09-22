TraxiGo Meta Ads Landing Page
================================

Files:
- index.html
- assets/ (logo, product images and product-demo.mp4)

Features:
- Responsive desktop/mobile landing page
- Product video is the first media item and is muted autoplay + loop + playsinline
- Product images follow the video in the gallery
- Video/image media is centered with contain-fit so the supplied visuals stay aligned
- Sticky WhatsApp icon / Show Cart / Add to Cart / Buy Now bar across the page
- Cart drawer with quantity controls and ₹790 subtotal
- No online payment gateway is connected yet; cart continues to the order/enquiry form
- Contact/order form configured for support@traxigo.in via FormSubmit
- TraxiGo logo is included in assets/traxigo-logo.png

IMPORTANT EMAIL SETUP:
The form posts to FormSubmit (https://formsubmit.co/) because a static HTML page cannot securely send email directly by itself.
On the first submission, FormSubmit may require the mailbox owner to confirm/activate the recipient address. After activation, subsequent submissions are delivered to support@traxigo.in.
For production, a first-party backend/API endpoint is preferable.

WHATSAPP:
+91 99141 66744

Deploy:
Upload index.html and the entire assets folder together to your hosting. Keep the relative paths unchanged.
