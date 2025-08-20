# WSJF Prioritization Tool

A React-based application for product owners to prioritize their backlog using the **Weighted Shortest Job First (WSJF)** methodology. This tool helps teams make data-driven prioritization decisions based on economic impact.

![WSJF Tool Preview](https://via.placeholder.com/800x400/2563eb/ffffff?text=WSJF+Prioritization+Tool)

## 🚀 Features

- **Interactive WSJF Scoring**: Use sliders to score items across four dimensions
- **Automatic Prioritization**: Items are automatically sorted by WSJF score
- **Two View Modes**:
  - **Manage View**: Add, edit, and configure backlog items
  - **Priority List View**: Clean, focused view of prioritized items
- **Real-time Calculations**: See WSJF scores update as you adjust values
- **Visual Priority Indicators**: Color-coded priority badges and scores
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## 📊 WSJF Formula

**WSJF = (User-Business Value + Time Criticality + Risk Reduction) ÷ Job Size**

### Scoring Dimensions

- **User-Business Value** (1-5): How much business value will this deliver?
- **Time Criticality** (1-5): How time-sensitive is this item?
- **Risk Reduction** (1-5): How much risk does this mitigate?
- **Job Size** (1-5): How much effort/complexity is required?

## 🛠️ Technology Stack

- **React** - Frontend framework
- **Tailwind CSS** - Styling
- **Lucide React** - Icons
- **JavaScript** - Core functionality

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/wsjf-prioritization-tool.git
cd wsjf-prioritization-tool
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## 📁 Project Structure

```
wsjf-prioritization-tool/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   └── WSJFApp.js
│   ├── App.js
│   ├── index.js
│   └── index.css
├── package.json
├── README.md
└── ...
```

## 🎯 How to Use

### Adding Backlog Items

1. Click "Add Item" in the Manage View
2. Enter the item title and description
3. Use the sliders to score each WSJF dimension:
   - **1 = Low impact/effort**
   - **3 = Medium impact/effort** 
   - **5 = High impact/effort**
4. Click "Add Item" to save

### Viewing Prioritized List

1. Switch to "Priority List" tab
2. Items are automatically sorted by WSJF score (highest first)
3. View priority rankings, scores, and component breakdowns
4. Edit items directly from the list view

## 📈 WSJF Scoring Guide

| Score | Business Value | Time Criticality | Risk Reduction | Job Size |
|-------|---------------|------------------|----------------|----------|
| **5** | Critical business impact | Must deliver now | Major risk mitigation | Large effort |
| **3** | Important business value | Important timing | Moderate opportunity | Medium effort |
| **1** | Nice to have | No time pressure | Low risk/opportunity | Small effort |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎨 Screenshots

### Manage Items View
*Add and configure backlog items with interactive WSJF scoring*

### Priority List View  
*Clean, focused view of your prioritized backlog*

## 🔗 Links

- **Demo**: [Live Demo](https://your-demo-link.com)
- **Issues**: [Report a Bug](https://github.com/yourusername/wsjf-prioritization-tool/issues)
- **SAFe WSJF**: [Learn more about WSJF](https://scaledagileframework.com/wsjf/)

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)

---

⭐ Star this repository if you found it helpful!