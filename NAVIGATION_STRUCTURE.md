# Muscat Bay OMS - Navigation Structure

## Main Sidebar Navigation

The application uses a hierarchical navigation structure with main sections and sub-sections for detailed functionality.

### Primary Navigation Sections

```javascript
const mainSections = [
  { 
    name: 'Electricity System', 
    icon: 'zap', 
    sectionId: 'ElectricitySystem',
    description: 'Power monitoring and consumption analysis',
    color: '#4E4456'
  },
  { 
    name: 'Water Analysis', 
    icon: 'droplets', 
    sectionId: 'WaterAnalysis',
    description: 'Water distribution and quality monitoring',
    color: '#3B82F6'
  },
  { 
    name: 'STP Plant', 
    icon: 'combine', 
    sectionId: 'STPPlant',
    description: 'Sewage treatment plant operations',
    color: '#10B981'
  },
  { 
    name: 'Contractor Tracker', 
    icon: 'user-check', 
    sectionId: 'ContractorTracker',
    description: 'Project management and contractor monitoring',
    color: '#6366F1'
  }
];
```

## Sub-Navigation Structure

### Electricity System Sub-Sections

```javascript
const electricitySubSections = [
  { 
    name: 'Dashboard', 
    id: 'Dashboard', 
    icon: 'layout-dashboard',
    description: 'Overview metrics, trends, and real-time monitoring'
  },
  { 
    name: 'Performance', 
    id: 'Performance', 
    icon: 'trending-up',
    description: 'Performance analytics and efficiency metrics'
  },
  { 
    name: 'Analytics', 
    id: 'Analytics', 
    icon: 'bar-chart-2',
    description: 'Deep dive analytics and consumption patterns'
  },
  { 
    name: 'Unit Details', 
    id: 'UnitDetails', 
    icon: 'list',
    description: 'Individual unit consumption and meter details'
  }
];
```

### Future Sub-Sections for Other Systems

```javascript
// Water Analysis Sub-Sections (Planned)
const waterSubSections = [
  { name: 'Dashboard', id: 'WaterDashboard', icon: 'layout-dashboard' },
  { name: 'Distribution', id: 'Distribution', icon: 'git-branch' },
  { name: 'Quality', id: 'Quality', icon: 'shield-check' },
  { name: 'Zones', id: 'Zones', icon: 'map-pin' }
];

// STP Plant Sub-Sections (Planned)
const stpSubSections = [
  { name: 'Operations', id: 'Operations', icon: 'settings' },
  { name: 'Monitoring', id: 'Monitoring', icon: 'monitor' },
  { name: 'Compliance', id: 'Compliance', icon: 'check-circle' },
  { name: 'Maintenance', id: 'Maintenance', icon: 'wrench' }
];

// Contractor Tracker Sub-Sections (Planned)
const contractorSubSections = [
  { name: 'Projects', id: 'Projects', icon: 'folder' },
  { name: 'Resources', id: 'Resources', icon: 'users' },
  { name: 'Timeline', id: 'Timeline', icon: 'calendar' },
  { name: 'Reports', id: 'Reports', icon: 'file-text' }
];
```

## Navigation Features

### Main Navigation Features
- **Active State Styling**: Current section highlighted with primary color
- **Hover Effects**: Interactive feedback with color transitions
- **Icon Integration**: Lucide icons for visual clarity
- **Responsive Design**: Collapsible on mobile devices

### Sub-Navigation Features
- **Tab-Style Interface**: Rounded pill navigation for sub-sections
- **Smooth Transitions**: Animated state changes
- **Context Awareness**: Shows relevant filters and tools per section
- **Breadcrumb Support**: Clear indication of current location

## File Structure Mapping

```
Navigation Section → Corresponding Files
├── Main Dashboard → index.html
├── Electricity System → electricity-advanced-dashboard.html
│   ├── Dashboard Tab → Default view with KPIs and charts
│   ├── Performance Tab → Performance analytics (placeholder)
│   ├── Analytics Tab → Advanced analytics (placeholder)
│   └── Unit Details Tab → Individual unit analysis (placeholder)
├── Water Analysis → water-dashboard.html
├── STP Plant → stp-dashboard.html
└── Contractor Tracker → contractor-dashboard.html
```

## Color Scheme for Navigation

```css
:root {
  --primary-color: #4E4456;      /* Main brand color */
  --primary-light: #7E708A;      /* Hover states */
  --primary-dark: #3B3241;       /* Active states */
  --electricity: #F59E0B;        /* Electricity system */
  --water: #3B82F6;              /* Water system */
  --stp: #10B981;                /* STP system */
  --contractor: #6366F1;         /* Contractor system */
}
```

## Implementation Notes

### Navigation State Management
- **activeMainSection**: Tracks current main section
- **activeSubSection**: Tracks current sub-section within main section
- **Persistent State**: Navigation state preserved across page transitions
- **URL Routing**: Each section maps to specific URLs

### Responsive Behavior
- **Desktop**: Full sidebar with text labels
- **Tablet**: Collapsed sidebar with icons only
- **Mobile**: Slide-out navigation drawer

### Accessibility Features
- **Keyboard Navigation**: Full keyboard accessibility
- **Screen Reader Support**: Proper ARIA labels and roles
- **Focus Management**: Clear focus indicators
- **High Contrast**: Meets WCAG accessibility standards

This navigation structure provides a scalable foundation for the Muscat Bay Operations Management Suite, allowing for easy expansion of functionality while maintaining consistent user experience across all modules.
