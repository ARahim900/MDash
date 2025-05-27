# MDash - Muscat Bay Integrated Systems Dashboard

A comprehensive web-based dashboard system for monitoring and managing integrated systems at Muscat Bay, including water management, electricity distribution, sewage treatment plant operations, and contractor tracking.

## 🌟 Features

### Main Dashboard (`index.html`)
- **Centralized Navigation Hub**: Clean, modern interface providing access to all system dashboards
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Color-coded System Cards**: Each system has distinct color coding for easy identification
- **Hover Effects**: Interactive card animations for better user experience

### System Dashboards

#### 🚰 Water Management Dashboard (`water-dashboard.html`)
- **Real-time Metrics**: Monitor total supply, consumption, water loss, and active zones
- **Zone Distribution**: Track water usage across residential, commercial, industrial, and marina areas
- **System Status**: Monitor main reservoir, distribution pumps, pressure, and quality sensors
- **Activity Log**: Real-time updates on system operations and maintenance

#### ⚡ Electricity System Dashboard (`electricity-dashboard.html`)
- **Power Generation Monitoring**: Track total generation, load demand, and grid efficiency
- **Renewable Energy Tracking**: Monitor solar, wind, and backup power sources
- **Load Distribution**: View consumption across different zones
- **Component Status**: Monitor transformers, UPS systems, circuit breakers, and smart meters
- **Fault Detection**: Real-time alerts and maintenance notifications

#### 🏭 STP Plant Dashboard (`stp-dashboard.html`)
- **Treatment Process Monitoring**: Track all treatment stages from primary to tertiary
- **Water Quality Parameters**: Monitor pH, BOD, COD, TSS, and turbidity levels
- **Equipment Status**: Monitor aeration blowers, clarifiers, pumps, and control systems
- **Environmental Compliance**: Track treatment efficiency and regulatory compliance
- **Flow Distribution**: Monitor input sources and output distribution

#### 👷 Contractor Tracker Dashboard (`contractor-dashboard.html`)
- **Project Management**: Track active projects, timelines, and progress
- **Contractor Performance**: Monitor performance scores and certifications
- **Resource Allocation**: Track workforce, equipment, and material inventory
- **Compliance Monitoring**: Safety certifications, insurance, and permit tracking
- **Budget Management**: Monitor budget utilization and project costs

## 🎨 Design Features

### Color Scheme
- **Primary Color**: `#4E4456` (Header background)
- **Secondary Color**: `#A0D2DB` (Dromedary/accent color)
- **System Colors**:
  - 🔵 **Water**: Blue (`#3B82F6`)
  - 🟡 **Electricity**: Amber (`#F59E0B`)
  - 🟢 **STP**: Emerald (`#10B981`)
  - 🟣 **Contractor**: Indigo (`#6366F1`)

### Visual Elements
- **Modern Typography**: Apple system fonts for clean readability
- **Gradient Logo**: Custom MB logo with gradient background
- **Interactive Cards**: Hover effects with shadow animations
- **Status Indicators**: Color-coded status badges and progress bars
- **Responsive Grid**: Adaptive layouts for all screen sizes

## 🛠️ Technical Stack

- **HTML5**: Semantic markup for accessibility
- **CSS3**: Custom styles with Flexbox and Grid layouts
- **Tailwind CSS**: Utility-first CSS framework via CDN
- **JavaScript**: Dynamic content updates and interactions
- **SVG Icons**: Scalable vector icons for system representations

## 📱 Responsive Design

The dashboard system is fully responsive and optimized for:
- **Desktop**: Full feature set with multi-column layouts
- **Tablet**: Adapted grid layouts with touch-friendly interfaces
- **Mobile**: Single-column stacked layouts with large touch targets

## 🚀 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ARahim900/MDash.git
   cd MDash
   ```

2. **Open in Browser**:
   - Open `index.html` in any modern web browser
   - No server setup required - works with static hosting

3. **Live Demo**:
   - Visit the live version at: `https://arahim900.github.io/MDash/`

## 📂 File Structure

```
MDash/
├── index.html                  # Main dashboard hub
├── water-dashboard.html        # Water management system
├── electricity-dashboard.html  # Electricity monitoring system
├── stp-dashboard.html         # STP plant operations
├── contractor-dashboard.html  # Contractor tracking system
└── README.md                  # Project documentation
```

## 🔗 Navigation

Each dashboard includes:
- **Header Navigation**: Return to main dashboard
- **System Branding**: Consistent MB logo and branding
- **Breadcrumb Navigation**: Clear location indicators

## 📊 Data Visualization

- **Real-time Metrics**: Key performance indicators with trend arrows
- **Progress Bars**: Visual progress tracking for projects and processes
- **Status Cards**: Color-coded system status indicators
- **Activity Feeds**: Chronological activity logs with timestamps
- **Grid Layouts**: Organized data presentation in card formats

## 🔧 Customization

### Adding New Systems
1. Create new HTML file following the existing structure
2. Add navigation card to `index.html`
3. Update color scheme in CSS custom properties
4. Add corresponding SVG icons

### Styling Modifications
- All custom styles are in `<style>` tags within each HTML file
- Tailwind CSS classes can be modified or extended
- Color scheme is centralized in CSS custom properties

## 🌐 Browser Support

- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Mobile Browsers**: iOS Safari, Chrome Mobile, Samsung Internet
- **Features Used**: CSS Grid, Flexbox, SVG, ES6 JavaScript

## 📈 Future Enhancements

- **Real-time Data Integration**: Connect to actual system APIs
- **User Authentication**: Role-based access control
- **Data Export**: PDF/Excel report generation
- **Mobile App**: Native mobile application
- **Advanced Analytics**: Historical data analysis and predictive insights
- **Notification System**: Push notifications for critical alerts

## 👥 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏢 About Muscat Bay

Muscat Bay Integrated Systems Dashboard is designed for comprehensive infrastructure management, providing real-time monitoring and control capabilities for:

- **Water Distribution Networks**
- **Electrical Power Systems** 
- **Wastewater Treatment Operations**
- **Contractor and Project Management**

---

**Built with ❤️ for Muscat Bay Integrated Systems**

*Powered by MB Technology Division*
