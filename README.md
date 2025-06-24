# 🌿 Mangrove Forest Health Assessment Using NDVI & NDWI Indices

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

This project demonstrates a simulated approach to assessing **Mangrove Forest Health** using **NDVI (Normalized Difference Vegetation Index)** and **NDWI (Normalized Difference Water Index)**. It uses synthetic spectral reflectance data to compute vegetation and water indices and classify health status into categories like `Healthy`, `Moderate`, and `Unhealthy`.

---

## 📂 Project Structure

├── mangrove_health_assessment.py # Main script for data generation, index calculation, and visualization
├── mangrove_health_synthetic_data.xlsx # Excel output of 150 synthetic data points with NDVI, NDWI, and classification
├── README.md # Project documentation (you are here)

yaml
Copy
Edit

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/mangrove-health-ndvi-ndwi.git
cd mangrove-health-ndvi-ndwi
2. Install Requirements
bash
Copy
Edit
pip install pandas numpy matplotlib seaborn
3. Run the Script
bash
Copy
Edit
python mangrove_health_assessment.py
🧪 Methodology
🛰 Indices Calculated
NDVI (Normalized Difference Vegetation Index)
Measures greenness and photosynthetic activity:
NDVI = (NIR - Red) / (NIR + Red)

NDWI (Normalized Difference Water Index)
Measures water content in vegetation:
NDWI = (Green - NIR) / (Green + NIR)

🏥 Health Classification Rules
NDVI Range	NDWI Range	Health Status
NDVI > 0.6	NDWI > -0.1	Healthy
0.3 < NDVI ≤ 0.6	NDWI > -0.3	Moderate
Else		Unhealthy

📊 Output
mangrove_health_synthetic_data.xlsx: Contains synthetic NIR, Red, Green bands + computed NDVI, NDWI + Health classification

A scatter plot showing NDVI vs NDWI, color-coded by HealthStatus

🧠 Use Cases
Educational tool for teaching remote sensing & vegetation monitoring

Prototyping NDVI/NDWI-based classification systems

Environmental and ecosystem modeling (mangrove focus)

📘 Example Preview

Replace with actual plot or GIF when available

📄 License
This project is licensed under the MIT License.

🤝 Acknowledgements
Inspired by real-world applications of remote sensing in mangrove monitoring using Landsat/Sentinel data. This synthetic version is for training and prototyping only.

🔗 Related Projects
USGS EarthExplorer

Google Earth Engine NDVI tutorials

✍️ Author
Agbozu Ebingiye Nelvin
@nelvinebi
Email: nelvinebingiye@gmail.com
