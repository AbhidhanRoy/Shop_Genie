# 🛒 Smart Shop Assistant

An intelligent shopping assistant web app built with **Streamlit**, **MongoDB**, and **PIL**, designed to help users get smart product suggestions based on natural language input and visualize item locations on a store map.

---

## 🚀 Features

- 🧠 **Natural Language Understanding**: Extracts items, budget, quantity, and aisle preferences from user input.
- ✅ **Product Recommendation**: Suggests products dynamically based on database info and user constraints.
- 🗺️ **Visual Store Map**: Displays product locations using markers and line paths over a store layout image.
- 🧾 **Detailed PDF Summary**: Generates a downloadable PDF with selected items, costs, and mapped locations.
- 📱 **QR Code Generation**: Easily scan a QR code to access the PDF summary on mobile devices.
- 🎨 **Interactive Aisle Legend**: Toggle visibility of products per aisle using checkboxes.
- 🧮 **Smart Quantity Calculation**: Dynamically adjusts product quantity based on product type and use case.

---

## 🧰 Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io/)
- **Database**: MongoDB Atlas
- **PDF Generation**: [FPDF with Unicode Support](https://pyfpdf.readthedocs.io/)
- **Image Processing**: [Pillow (PIL)](https://pillow.readthedocs.io/)
- **QR Code**: [qrcode](https://pypi.org/project/qrcode/)

---

## 📂 Project Structure
📦 smart-shop-assistant/
├── app.py # Main Streamlit app
├── aisle_coords.json # Aisle-to-(x,y) coordinate mappings
├── store_map.png # Base image of the store layout
├── marker.png # Optional: custom marker icon
├── DejaVuSans.ttf # Unicode font for emojis in PDF
├── extractor.py # Text parsing for item, budget, etc.
├── item_mapper.py # MongoDB logic to fetch products
└── requirements.txt # Python dependencies


---


## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/smart-shop-assistant.git
   cd smart-shop-assistant

## 🧪 Example Output

🎯 Recommended products with optimal quantity and cost.

🗺️ Store map highlighting aisle paths and product positions.

📜 PDF download with all selected items and pricing.

📱 QR Code for mobile viewing.

## 🛠️ To Do (Possible Enhancements)
🔊 Voice input using speech-to-text

🛒 Real-time stock status

🔄 Smart substitutions for out-of-stock items

👤 User login and history tracking

🗺️ Map zoom/pan support

