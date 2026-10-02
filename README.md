## **CarVault – Car Rental & Resale Marketplace**
**Full-Stack Web Application | Laravel MVC**

Developed and deployed a full-stack car rental and resale marketplace that connects vehicle owners (shops) with customers for renting, buying, and auctioning vehicles.

**Key Features:**
- **Multi-role system** with separate dashboards for Shop Owners and Customers, including secure authentication and session management
- **Vehicle Inventory Management** — owners can add, edit, and categorize vehicles with image uploads, pricing, and availability tracking
- **Rental System** — customers browse, add to cart, and pay for rentals using a points-based payment system, with automatic rental/return date handling
- **Resale Auction System** — owners list vehicles for auction with real-time bidding, force-buy pricing, and automated bidder tracking
- **Customer Sell Requests** — customers submit vehicles for resale; owners can accept/reject offers with automatic point transfers
- **Dynamic Cart & Checkout** — integrated with inventory, rental, and resale modules
- **Owner Analytics** — view customer details, rental history, and auction winners per item
- **Automated workflows** — items seamlessly transition between Inventory, Rental, and Resale states with data integrity maintained via database transactions

**Tech Stack:**
- **Backend:** Laravel (PHP), MVC architecture, Eloquent ORM
- **Database:** PostgreSQL (hosted on Supabase)
- **Frontend:** Blade templating, custom CSS
- **Deployment:** Dockerized and deployed on Render
- **Tools:** Git/GitHub, Composer, Apache
