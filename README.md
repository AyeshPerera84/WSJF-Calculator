# 🎯 WSJF Prioritization Tool

A modern, intuitive React-based application that helps product owners and agile teams prioritize their backlog using the **Weighted Shortest Job First (WSJF)** methodology from SAFe (Scaled Agile Framework).

![WSJF Tool Screenshot](https://img.shields.io/badge/React-18.2.0-blue?logo=react) ![License](https://img.shields.io/badge/license-MIT-green) ![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.3.0-blue?logo=tailwindcss)


## ✨ Features

### 🎛️ Interactive WSJF Scoring
- **Slider-based scoring** for all four WSJF dimensions (1-5 scale)
- **Real-time calculation** and preview of WSJF scores
- **Visual feedback** with color-coded priority indicators

### 📊 Dual View System
- **Manage Items View**: Add, edit, and configure backlog items with detailed scoring
- **Priority List View**: Clean, focused display of prioritized items for stakeholder meetings

### 🏆 Smart Prioritization
- **Automatic ranking** based on calculated WSJF scores
- **Priority badges** (HIGHEST, HIGH, MEDIUM, LOW) with visual distinction
- **Quick stats** showing total items, highest score, and averages

### 📱 Modern User Experience
- **Responsive design** that works on desktop, tablet, and mobile
- **Smooth animations** and hover effects
- **Intuitive navigation** between different views
- **Persistent data** during your session

## 📈 WSJF Formula

The tool implements the standard SAFe WSJF formula:

```
WSJF = (User-Business Value + Time Criticality + Risk Reduction) ÷ Job Size
```

### Scoring Dimensions

| Factor | Scale | Description |
|--------|-------|-------------|
| **User-Business Value** | 1-5 | How much business value will this deliver to users and the business? |
| **Time Criticality** | 1-5 | How time-sensitive is this item? Will delay cause significant impact? |
| **Risk Reduction** | 1-5 | How much risk does this mitigate or opportunity does it enable? |
| **Job Size** | 1-5 | How much effort, complexity, and resources are required? |

### Scoring Guide

| Score | Business Value | Time Criticality | Risk Reduction | Job Size |
|-------|---------------|------------------|----------------|----------|
| **5** | 🔴 Critical business impact | 🚨 Must deliver now | ⚡ Major risk mitigation | 🏗️ Very large effort |
| **4** | 🟠 High business impact | ⏰ Soon, important timing | 🛡️ Significant risk reduction | 📦 Large effort |
| **3** | 🟡 Important business value | 📅 Important but flexible | 🔄 Moderate opportunity | ⚖️ Medium effort |
| **2** | 🔵 Some business value | 📋 Low time pressure | 🎯 Small opportunity | 🧩 Small effort |
| **1** | ⚪ Nice to have | 🕐 No time pressure | 💡 Minimal impact | ✨ Very small effort |

## 🛠️ Technology Stack

- **React 18.2** - Modern React with hooks
- **Tailwind CSS 3.3** - Utility-first CSS framework
- **Lucide React** - Beautiful, customizable icons
- **JavaScript ES6+** - Modern JavaScript features

## 📦 Installation

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/wsjf-prioritization-tool.git
   cd wsjf-prioritization-tool
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start development server**
   ```bash
   npm start
   # or
   yarn start
   ```

4. **Open in browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Build for Production

```bash
npm run build
# or
yarn build
```

## 🎯 How to Use

### Step 1: Add Backlog Items
1. Start in the **"Manage Items"** view
2. Click **"Add Item"** button
3. Enter your backlog item title and description
4. Use the sliders to score each WSJF dimension

### Step 2: Score Your Items
- **Business Value**: What's the impact to users/business?
- **Time Criticality**: How urgent is this item?
- **Risk Reduction**: What risks does this address?
- **Job Size**: How much effort is required?

### Step 3: Review Prioritization
1. Switch to **"Priority List"** view
2. Items are automatically ranked by WSJF score
3. Review the prioritized order for your next sprint planning

### Step 4: Make Decisions
- Use the ranked list in sprint planning meetings
- Share with stakeholders for alignment
- Edit items directly from the priority list

## 📊 Example Use Cases

### 🏢 Product Management
- **Sprint Planning**: Determine which features to build next
- **Roadmap Planning**: Align team on long-term priorities
- **Stakeholder Communication**: Show data-driven prioritization

### 👥 Agile Teams
- **Backlog Refinement**: Score user stories systematically
- **PI Planning**: Prioritize features for upcoming program increments
- **Risk Management**: Factor risk reduction into prioritization

### 🎯 Project Management
- **Resource Allocation**: Focus on highest-value items
- **Timeline Planning**: Balance value delivery with capacity
- **Executive Reporting**: Present objective prioritization rationale


### 🐛 Report Issues
- Found a bug? [Open an issue](https://github.com/yourusername/wsjf-prioritization-tool/issues)
- Have a feature request? We'd love to hear it!

### 🔧 Development
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### 💡 Ideas for Contributions
- Export functionality (PDF, CSV)
- Data persistence (localStorage, cloud sync)
- Team collaboration features
- Additional scoring methodologies
- Mobile app version
- Integration with project management tools

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🔗 Resources

- **SAFe WSJF**: [Learn more about WSJF methodology](https://scaledagileframework.com/wsjf/)
- **Agile Prioritization**: [Best practices for backlog prioritization](https://www.scrum.org/resources/blog/product-backlog-prioritization)
- **React Documentation**: [Official React docs](https://react.dev/)
- **Tailwind CSS**: [Utility-first CSS framework](https://tailwindcss.com/)

## 👨‍💻 Author

**[Your Name]**
- 🐙 GitHub: [@yAyesh84](https://github.com/AyeshPerera84)
- 💼 LinkedIn: [Ayesh Perera](https://www.linkedin.com/in/ayeshperera/)


## 🙏 Acknowledgments

- Inspired by the **Scaled Agile Framework (SAFe)** methodology
- Built with ❤️ for the agile community
- Icons by **Lucide React**
- Styling powered by **Tailwind CSS**

---

### ⭐ Star this repository if you found it helpful!

*Made with ❤️ for product owners, scrum masters, and agile teams everywhere.*

## 📈 Project Status

- ✅ Core WSJF functionality
- ✅ Dual view system  
- ✅ Responsive design
- ✅ Interactive scoring
- 🔄 Export functionality (coming soon)
- 🔄 Data persistence (planned)
- 🔄 Team collaboration (roadmap)

**Version**: 1.0.0  
**Last Updated**: August 2025
