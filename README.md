# Digital-Address-DPI-Innovation-Hackathon-India-Post-Digital-Governance-Summit-Shaastra

---

# DIGIPIN API by Department of Posts

![](https://indianewsdiary.com/wp-content/uploads/2022/08/Ministry-of-Communications.png)

Ministry of Communications India Post
# A Geospatial Addressing Solution by India Post
DIGIPIN (Digital PIN) is a 10-character alphanumeric geocode developed by the Department of Posts, India. It provides a precise, user-friendly way to encode geographic coordinates that can be easily shared and decoded back to latitude/longitude pairs.

This open-source Node.js project exposes a public API to generate and decode DIGIPINs, supporting geolocation services, postal logistics, and spatial analysis applications.

- **License:**  Apache 2.0
- **Node.js:** v14+
- **Express:** v4.x
  
---
  
# 🏛️ About DIGIPIN
The Department of Posts has undertaken an initiative to establish a Digital Public Infrastructure (DPI) for a standardized, geo-coded addressing system in India. DIGIPIN represents the foundation layer of this infrastructure.

Developed in collaboration with IIT Hyderabad and NRSC (National Remote Sensing Centre, ISRO), DIGIPIN is an open-source national-level addressing grid that serves as a key component of India's digital address ecosystem.

After extensive public consultation and expert review, the DIGIPIN Grid has been finalized to provide simplified addressing solutions for seamless delivery of public and private services, enabling "Address as a Service" (AaaS) across the country.

**Key Highlights**
- **Uniform Referencing Framework:** Provides logical, precise location identification both offline and online
- **GIS Integration:** Bridges the gap between physical and digital addresses
- **Cross-Sector Support:** Enhances service delivery across emergency response, e-commerce, logistics, BFSI, and governance
- **Policy Alignment:** Complies with the National Geospatial Policy 2022, enriching India's geospatial knowledge stack
DIGIPIN simplifies address management and enhances service delivery accuracy, promoting a thriving geospatial ecosystem for India's digital economy.

---

# ✨ Features
- **Encode:** Convert latitude and longitude into a compact 10-character DIGIPIN
- **Decode:** Transform a DIGIPIN back to its center-point coordinates
- **Lightweight:** Optimized for performance and minimal resource usage
- **RESTful API:** Clean, standard-compliant endpoints
- **Interactive Documentation:** Comprehensive Swagger UI for easy exploration
- **Production-Ready:** Built with Node.js and Express for reliability

---

# 📦 Installation
**Prerequisites**
- Node.js (v14 or higher)
- npm (v6 or higher)
**Getting Started**
1. **Clone the Repository**
 `git clone https://github.com/INDIAPOST-gov/digipin.git`
`cd digipin`
2. - **Install Dependencies**
 `npm install`
3. - **Environment Setup**
Create a `.env` file in the project root with the following variables:

`PORT=5000
NODE_ENV=development`

4. - **Start the Server**
`npm start`

For development with hot reloading:
`npm run dev`

The API will be available at `http://localhost:5000`.

---

# 🚀 API Usage
- **Encode Coordinates to DIGIPIN**
`GET /api/digipin/encode?latitude=12.9716&longitude=77.5946`

- **Response:**
`{"digipin":"4P3-JK8-52C9"}`
- **Decode DIGIPIN to Coordinates**
`GET /api/digipin/decode?digipin=4P3-JK8-52C9`
- **Response:**
`{"latitude":"12.971601","longitude":"77.594584"}`
- **Interactive API Documentation**
Access the Swagger UI documentation at:

`http://localhost:5000/api-docs`

---

# 🔧 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

Fork the repository
1. Create your feature branch (`git checkout -b feature/amazing-feature`)
2. Commit your changes (`git commit -m 'Add some amazing feature'`)
3. Push to the branch (`git push origin feature/amazing-feature`)
4. Open a Pull Request
5. Please ensure your code adheres to the existing style and passes all tests.

---

# 📜 License
This project is licensed under the Apache License, Version 2.0 - see the LICENSE file for details.

---

# 🙏 Acknowledgements
- Department of Posts, Government of India
- Indian Institute of Technology, Hyderabad
- National Remote Sensing Centre, ISRO
  
  ---
_Transforming addresses for Digital India_
