# Global Sales Dashboard

An interactive geographical sales visualization dashboard built with Power BI, providing comprehensive insights into global sales distribution across regions and countries.

## 📊 Overview

This dashboard presents a world map visualization of sales data, enabling users to explore sales performance across different geographical regions and countries. The interface features interactive filtering capabilities and detailed sales metrics for data-driven decision making.

## ✨ Features

- **Interactive World Map**: Visual representation of global sales data with color-coded regions
- **Regional Filtering**: Easy navigation through 16 distinct geographical regions including:
  - Central Asia, Eastern Africa, Eastern Europe, North Africa
  - Oceania, Southeastern Asia, Southern Asia, Southern US
  - Central US, Eastern Asia, Eastern US, Northern Europe
  - South America, Southern Africa, Southern Europe, Western Africa

- **Country-Level Analysis**: Detailed sales breakdown by individual countries
- **Dynamic Sales Metrics**: Real-time display of sales figures across multiple countries
- **Zoom Controls**: Interactive map navigation with zoom in/out functionality
- **Responsive Design**: Optimized viewing experience across different screen sizes

## 🎯 Key Metrics

The dashboard tracks and displays:
- Sales performance by region
- Country-specific sales data
- Comparative analysis across geographical areas
- Visual heat mapping for quick insight identification

## 🛠️ Technologies Used

- **Power BI Desktop**: Primary development platform
- **Microsoft Bing Maps**: Map visualization component
- **Data Source**: [Excel CSV file]

## 📸 Screenshot

[Dashboard Overview](https://ibb.co/nMFdVZgr)
*Main dashboard view showing global sales distribution*

## 🚀 Getting Started

### Prerequisites

- Power BI Desktop (Latest version recommended)
- Windows 10 or later
- Active internet connection for map rendering

### Installation

1. Clone this repository
   ```bash
   git clone https://github.com/Dannywhilz001/global-sales-dashboard.git
   ```

2. Open the `.pbix` file with Power BI Desktop

3. Refresh data connections if needed

### Data Setup

1. Ensure your data source is accessible
2. Update data source connections in Power BI
3. Refresh the dataset to load latest data

## 📁 Project Structure

```
global-sales-dashboard/
│
├── README.md
├── LICENSE
├── .gitignore
├── map_dashboard.PNG
├── GlobalSalesDashboard.pbix
├── data/
│   └── [My data files]
└── docs/
    └── [Additional documentation]
```

## 🔧 Configuration

### Customizing the Dashboard

1. **Regions**: Modify region filters in the filter pane
2. **Colors**: Adjust color schemes in the Format visual settings
3. **Metrics**: Add or modify sales KPIs in the Fields pane

### Data Refresh

- **Manual Refresh**: Click "Refresh" in Power BI Desktop
- **Scheduled Refresh**: Configure in Power BI Service after publishing

## 📊 Data Requirements

- Country/Region information
- Sales figures
- Date/time stamps (if time-based analysis needed)
- Additional dimensions as required

### Sample Data Structure

| Country | Region | Sales | Date |
|---------|--------|-------|------|
| USA | North America | 2832.96 | 2024-01-01 |
| India | Southern Asia | 2616.96 | 2024-01-01 |

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Oladotun Olawale**
 [GitHub](https://github.com/Dannywhilz001)
 [LinkedIn](https://www.linkedin.com/in/oladotun-olawale)

## 🙏 Acknowledgments

- Microsoft Power BI for the visualization platform
- Bing Maps for geographical mapping capabilities

## 📮 Contact

For questions or feedback, please open an issue or contact [oladotunolawale29@yahoo.com]

## 🔄 Version History

- **v1.0.0** (2026-01-28)
  - Initial release
  - Core map visualization
  - Regional filtering
  - Country-level sales metrics

## 🗺️ Roadmap

- [ ] Add time-based trend analysis
- [ ] Implement drill-through functionality
- [ ] Add export capabilities
- [ ] Create mobile-optimized version
- [ ] Integrate predictive analytics
