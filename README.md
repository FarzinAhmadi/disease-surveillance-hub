# 🏥 Disease Surveillance Hub

A real-time disease surveillance dashboard tracking notifiable diseases across the United States, powered by CDC NNDSS (National Notifiable Diseases Surveillance System) data.

**[🔴 View Live Dashboard](https://farzinahmadi.github.io/disease-surveillance-hub/)**

## 📊 Overview

The Disease Surveillance Hub provides an interactive, data-driven view of disease patterns across the United States. This tool helps public health professionals, researchers, and the general public understand disease trends and geographical distributions in real-time.

## ✨ Features

- **Interactive Disease Tracking**: Monitor multiple notifiable diseases across all US states and territories
- **Real-Time Data Visualization**: Dynamic charts and maps displaying current disease trends
- **Historical Comparisons**: Compare current year data with previous year trends
- **Geographic Analysis**: State-by-state breakdown with population-adjusted metrics
- **Weekly Updates**: Data synchronized with CDC's MMWR (Morbidity and Mortality Weekly Report) schedule

## 📈 Data Sources

- **Primary Data**: CDC National Notifiable Diseases Surveillance System (NNDSS)
- **Geographic Data**: US Census Bureau state boundaries and population statistics
- **Update Frequency**: Weekly, following CDC MMWR reporting schedule

### Tracked Diseases Include:
The dashboard monitors diseases reported to the NNDSS, currently focusing on Measles, Pertussis, and Meningococcal disease.


## 🚀 Quick Start

### View the Dashboard
Simply visit the [live dashboard](https://farzinahmadi.github.io/disease-surveillance-hub/) to explore current disease surveillance data.


## 📁 Project Structure
```
disease-surveillance-hub/
├── index.html                          # Main dashboard page
├── NNDSS_Weekly_Data_20250703.csv     # CDC surveillance data
├── us_states.csv                       # US states geographic data
├── README.md                           # This file
└── assets/                             # Static assets (if any)
```

## 🔍 Data Fields

### NNDSS Weekly Data
- **Reporting Area**: State or territory name
- **MMWR WEEK**: CDC's standardized epidemiological week
- **Current week**: Case counts for the current reporting week
- **Previous 52 week Max**: Historical maximum for comparison
- **Cumulative YTD**: Year-to-date totals for trend analysis

### State Data
- **Population**: Current state population estimates
- **Geographic Coordinates**: Latitude/longitude for mapping

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Data Processing**: Client-side CSV parsing
- **Visualization**: Interactive charts and maps
- **Hosting**: GitHub Pages

## 📊 Use Cases

- **Public Health Officials**: Monitor disease outbreaks and trends
- **Researchers**: Analyze epidemiological patterns
- **Healthcare Providers**: Stay informed about regional disease activity
- **Educators**: Teaching tool for public health and epidemiology
- **General Public**: Understanding disease risks in their area

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Report Issues**: Found a bug? [Open an issue](https://github.com/FarzinAhmadi/disease-surveillance-hub/issues)
2. **Suggest Features**: Have ideas? Share them in the discussions
3. **Submit Pull Requests**: 
   - Fork the repository
   - Create a feature branch (`git checkout -b feature/AmazingFeature`)
   - Commit your changes (`git commit -m 'Add some AmazingFeature'`)
   - Push to the branch (`git push origin feature/AmazingFeature`)
   - Open a Pull Request

## 📝 Data Update Schedule

Data is updated weekly following the CDC's MMWR publication schedule, typically released every Thursday. The filename reflects the update date (YYYYMMDD format).

## ⚠️ Disclaimer

This dashboard is for informational and educational purposes only. For official public health guidance and up-to-the-minute data, please refer to:
- [CDC National Notifiable Diseases Surveillance System](https://www.cdc.gov/nndss/)
- Your local public health department
- [CDC MMWR](https://www.cdc.gov/mmwr/)

## 📄 License

This project is available under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- **CDC NNDSS**: For providing comprehensive disease surveillance data
- **US Census Bureau**: For population and geographic data
- The public health community for their continued efforts in disease surveillance

## 📧 Contact

Farzin Ahmadi - [@FarzinAhmadi](https://github.com/FarzinAhmadi)

Project Link: [https://github.com/FarzinAhmadi/disease-surveillance-hub](https://github.com/FarzinAhmadi/disease-surveillance-hub)

---

**⭐ If you find this project useful, please consider giving it a star!**

*Last Updated: Oct 2025*
