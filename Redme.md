🛒 Jazmin Professional POS System

A high-performance, responsive Point of Sale (POS) application built for efficiency. This single-page application (SPA) allows businesses to manage product catalogs, track pending orders, and communicate directly with customers via WhatsApp—all without requiring a backend server.

✨ Key Features

📦 Dynamic Catalog Management: Products are organized into sleek, navigable category tabs (Appetizers, Main Course, Drinks, etc.).

🛒 Real-time Shopping Cart: Instant subtotal and grand total calculations with intuitive quantity controls.

💾 Local Storage Persistence: Orders are saved locally in the browser's storage, ensuring data isn't lost on page refreshes.

📲 WhatsApp Order Integration: Automatically formats a professional order summary and sends it directly to the customer's phone number.

⚡ Rapid Entry Workflow: Optimized keyboard navigation (Enter key) allows users to jump between customer details and finalize orders in seconds.

📱 Responsive & Fluid: A mobile-first design that adapts beautifully to tablets, laptops, and desktop monitors.

🛠️ Technical Stack

Frontend: HTML5 & CSS3

Styling: Tailwind CSS (Atomic CSS framework for high-speed UI development)

Logic: Vanilla JavaScript (ES6+) — No heavy frameworks required.

Storage: Browser localStorage API.

Theming: Custom CSS Variables for a professional Teal & Gold brand identity.

📂 Project Structure

Component

Responsibility

Catalog Section

Displays product cards with prices, names, and category filtering.

Order Form

Captures Customer Name, Contact, Address, and Notes.

Cart Module

Live list of items, quantity adjustment, and total breakdown.

Persistence Engine

Handles save, edit, and delete operations for saved/pending orders.

Communication Layer

Formats and triggers the api.whatsapp.com link for order receipts.

🚀 How to Use

1. Adding Items

Simply browse the catalog and click any product card. The item will appear in your "Current Order" list instantly.

2. Filling Customer Details

Input the name and phone number.

Shortcut: Press Enter to cycle focus from Name → Contact → Address → Notes → Save.

3. Handling Orders

Save Order: Stores the order in the "Saved Orders" section below for later processing.

Send Order: Opens a WhatsApp chat with the customer containing the full itemized list and total.

Clear All: Resets the local database of saved orders.

🔧 Customization

To update the menu, edit the JSON block at the bottom of the HTML file:

{ 
  "id": 101, 
  "name": "Special Dish", 
  "rate": 45.50, 
  "category": "Main Course" 
}


🎨 Design System

Primary Teal (#004D40): Stability and professionalism.

Accent Gold (#FFC107): Highlights actions and attention areas.

Typography: Uses Inter sans-serif for high readability on small screens.

⚠️ Security & Persistence

This application operates entirely on the client side. Data is stored in your browser's Local Storage.

Note: Clearing browser data or using "Incognito Mode" will remove saved orders.

Privacy: Customer data never leaves your device unless you choose to send an order via WhatsApp.

📝 License

This project is open-source and free to use for small business operations.
