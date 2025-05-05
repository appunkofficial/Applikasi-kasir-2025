# Applikasi-kasir-2025
Sistem Kasir Professional
Overview
Sistem Kasir Professional is a web-based point-of-sale (POS) application designed to streamline retail operations. It provides features for product management, inventory tracking, sales analytics, and transaction processing with a modern, responsive user interface. The application supports light and dark themes, product export to PDF and Excel, and receipt printing, making it suitable for small to medium-sized retail businesses.
Features

POS System: Add products to a cart, process transactions, and print receipts.
Product Management: Add, view, and delete products with details like name, price, and stock.
Inventory Tracking: Monitor available stock and inventory value.
Sales Analytics: View weekly, monthly, and yearly sales data.
Export Options: Export product lists to PDF or Excel formats.
Theme Toggle: Switch between light and dark themes for user preference.
Responsive Design: Optimized for desktop, tablet, and mobile devices.

Technologies Used

HTML5: For structuring the application.
CSS3: For styling, including responsive design and dark theme support.
JavaScript: For interactivity and core functionality.
Font Awesome: For icons.
XLSX Library: For Excel export functionality.
LocalStorage: For persistent data storage of products and sales.

Installation

Clone or Download the Repository:
git clone <repository-url>

Alternatively, download the project files as a ZIP and extract them.

Host the Application:

Use a local web server (e.g., XAMPP, WAMP, or Node.js http-server) to serve the project files.
Example using http-server:npm install -g http-server
cd <project-directory>
http-server


Alternatively, open index.html directly in a browser (note that some features, like LocalStorage, may require a server).


Ensure Dependencies:

The application uses CDN-hosted libraries:
Font Awesome: https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css
XLSX: https://unpkg.com/xlsx/dist/xlsx.full.min.js


No additional installation is required for these dependencies.



Usage

Access the Application:

Open the application in a web browser by navigating to the hosted URL (e.g., http://localhost:8080) or opening index.html.


Navigate the Interface:

Use the sidebar to switch between sections: POS, Produk, Inventori, Analitik, and Penghasilan.
Toggle between light and dark themes using the "Mode Gelap" button.


Key Operations:

POS: Add products to the cart, view the total, and process transactions with the "Cetak Struk & Bayar" button.
Produk: Add new products via the form and delete existing ones from the table.
Inventori: View current stock and inventory value.
Analitik: Review sales performance for different time periods.
Penghasilan: Export product lists to PDF or Excel.


Data Persistence:

Products and sales data are stored in the browser's LocalStorage, ensuring persistence across sessions.



File Structure
sistem-kasir-professional/
├── index.html       # Main HTML file containing structure, styles, and scripts
├── style.css        # External CSS file (if used, currently embedded in index.html)
├── script.js        # External JavaScript file (if used, currently embedded in index.html)
└── README.md        # Project documentation

Notes

External File Dependencies: The current implementation embeds CSS and JavaScript within index.html. If style.css or script.js are referenced, ensure they exist in the project directory or update the <link> and <script> tags accordingly.
Browser Compatibility: Tested on modern browsers (Chrome, Firefox, Edge). Some features (e.g., printing) may behave differently in older browsers.
Limitations: The application uses LocalStorage, which has a storage limit (typically 5-10 MB). For large datasets, consider integrating a backend database.

Troubleshooting

Blank Page or Missing Styles: Ensure the CDN links for Font Awesome and XLSX are accessible. Check the browser console for errors.
LocalStorage Issues: If data doesn't persist, ensure the application is hosted via a server rather than opened directly as a file.
Printing Issues: Verify that the browser's print dialog is enabled and not blocked by extensions.

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a feature branch (git checkout -b feature-name).
Commit changes (git commit -m "Add feature-name").
Push to the branch (git push origin feature-name).
Open a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
For questions or feedback, please contact the project maintainer at [your-email@example.com].
