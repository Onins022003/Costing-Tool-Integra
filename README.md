# UAS Integra — Costing Suite 2024

Professional implementation costing and project management calculator for Integra UAS technical teams.

**Status:** ✅ Production Ready  
**Version:** 2024  
**License:** MIT

---

## 🎯 Overview

UAS Integra Costing Suite is a comprehensive web-based tool designed to help technical teams:

- **Estimate** implementation costs for various project types
- **Track** resource allocation across multiple scenarios
- **Calculate** pricing based on team expertise levels
- **Manage** project repositories and historical costs
- **Export** data for reports and documentation

---

## 📦 Features

### 🛠️ Implementation Tool
- Multiple cost scenarios for different project locations
- Dynamic engineering level pricing
- PPE (Personal Protective Equipment) selection and costing
- Real-time calculation and updates
- Support inclusions tracking
- Gross profit margin analysis
- Professional cost breakdowns

### 📊 Support Tool
- Flexible support package configurations
- Detailed inclusions matrix
- Scenario-based pricing
- Cost tier management
- Customizable billing rates

### 📚 Repository
- Complete project history
- Filter by category and status
- Cost tracking and analytics
- Edit and delete functionality
- Detailed project view

### 💾 Data Management
- Save estimates locally
- Export comprehensive reports
- Multi-scenario comparison
- Persistent storage

---

## 🚀 Getting Started

### Option 1: GitHub Pages (Recommended)

1. **Fork or Clone Repository**
   ```bash
   git clone https://github.com/yourusername/uas-integra-costing-suite.git
   cd uas-integra-costing-suite
   ```

2. **Enable GitHub Pages**
   - Go to Repository Settings → Pages
   - Select "main" branch as source
   - Choose "/" (root) folder
   - Save

3. **Access Your Tool**
   ```
   https://yourusername.github.io/uas-integra-costing-suite
   ```

### Option 2: Local Usage

Simply open `index.html` in your browser:

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

---

## 📋 How to Use

### Implementation Tool

1. **Select Scenario**
   - Choose location-based pricing (Metro Manila, nearby provinces, or far provinces)
   
2. **Enter Project Details**
   - Set number of engineers by expertise level
   - Input allocated days
   - Add optional costs (travel, equipment, etc.)

3. **Select PPE Items** (if required)
   - Check boxes for required personal protective equipment
   - Costs calculate automatically

4. **Review Summary**
   - See total cost breakdown
   - View gross profit margin
   - Export or save estimate

### Support Tool

1. **Choose Support Level**
   - Select support package tier
   
2. **Configure Details**
   - Customize support duration
   - Adjust billing rates if needed
   
3. **Review Inclusions**
   - Check what's included in the package
   - Verify coverage details

4. **Save or Export**
   - Store estimate locally
   - Export for client proposals

### Repository

1. **View Project History**
   - See all saved estimates
   - Filter by type or status

2. **Manage Entries**
   - View detailed project information
   - Edit existing estimates
   - Delete archived projects

---

## 🔧 Customization

### Update Billing Rates

Open `index.html` and locate the rates configuration section to modify:
- Associate Engineer monthly rates
- Professional Engineer monthly rates  
- Senior Engineer monthly rates
- Daily and hourly rates are calculated automatically

### Add New Scenarios

Modify the scenario data structure to add new location-based pricing tiers with custom cost matrices.

### Customize PPE Options

Update the PPE items list with your organization's requirements and costs.

---

## 💾 Data Storage

- **Local Storage:** Estimates are saved to browser's local storage
- **Export:** Download complete project data as JSON or CSV
- **Persistence:** Data persists across browser sessions until cleared

---

## 🎨 Design System

### Color Palette
- **Primary (Gold):** `#B07C0A` - Implementation tool accent
- **Secondary (Teal):** `#0D7A6B` - Support tool accent
- **Neutral:** Professional grays for accessibility
- **Status Colors:** Green (✓), Red (✗), Amber (⚠)

### Typography
- **Primary Font:** Plus Jakarta Sans
- **Mono Font:** JetBrains Mono (for numbers and codes)

### Components
- Reusable form cards
- Summary cards with sticky positioning
- Responsive data tables
- Modal dialogs
- Filter buttons

---

## 📱 Browser Support

| Browser | Desktop | Mobile |
|---------|---------|--------|
| Chrome  | ✅ 90+  | ✅ 90+ |
| Firefox | ✅ 88+  | ✅ 88+ |
| Safari  | ✅ 14+  | ✅ 14+ |
| Edge    | ✅ 90+  | ✅ 90+ |

---

## 🔒 Security & Privacy

- ✅ **No Server Transmission:** All calculations happen locally
- ✅ **No Tracking:** No analytics or user tracking
- ✅ **No Authentication Required:** Works offline
- ✅ **Data Control:** You control when data is saved/exported
- ✅ **Browser Storage Only:** Uses localStorage API

---

## 🐛 Troubleshooting

### Data Not Saving?
- Check if localStorage is enabled in browser settings
- Clear browser cache and reload
- Try a different browser

### Calculations Not Updating?
- Refresh the page (Ctrl+R or Cmd+R)
- Verify all input fields contain valid numbers
- Check browser console for errors (F12)

### Export Issues?
- Ensure pop-ups are not blocked
- Try a different browser
- Check available disk space

---

## 📈 Version History

### v2024.1 (Current)
- Professional UI with Plus Jakarta Sans typography
- Dual-tool system (Implementation + Support)
- Repository and history management
- Enhanced calculations and validations
- Responsive mobile design
- Local storage persistence

---

## 🤝 Contributing

To contribute improvements:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/improvement`
3. Make your changes
4. Commit: `git commit -am 'Add improvement'`
5. Push: `git push origin feature/improvement`
6. Open a Pull Request

---

## 📧 Support

For issues or questions:

- **GitHub Issues:** Open an issue on the repository
- **Integra UAS:** technical@integrauas.com
- **Documentation:** See DEPLOYMENT_GUIDE.md for setup help

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🙏 Acknowledgments

- Integra UAS Technical Team
- All contributors and users
- Modern web technologies: HTML5, CSS3, JavaScript ES6+

---

**Last Updated:** January 2024  
**Status:** ✅ Production Ready
