# impactOS Dashboard - Business Design Centre

A beautiful, Apple-inspired liquid glass dashboard for the **instarinse®** system, designed for exhibition at the Business Design Centre.

## 🎨 Features

- **Real-time metrics** - Water usage, energy usage, paper cups saved, cost savings
- **Smart comparisons** - Auto-alternates between handwash and dishwash baselines every 10 seconds
- **Predictive maintenance** - AI-driven tank change predictions based on usage patterns
- **Live system status** - Water tank and filter monitoring
- **Elegant animations** - Waveform indicators, smooth transitions, liquid glass effects
- **Customer-facing** - Export reports, issue reporting, service information

## 📱 Deployment

### GitHub Pages (Recommended for Tablets)

1. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Source: Deploy from `main` branch
   - Save

2. **Access the dashboard:**
   ```
   https://salmon2706.github.io/BDC-Show-Dashboard/dashboard.html
   ```

3. **Configure tablets:**
   - Set kiosk mode to open the GitHub Pages URL
   - Enable auto-refresh if needed
   - All tablets will update automatically when you push changes

### Local Deployment

Simply open `dashboard.html` in any modern browser (Chrome, Safari, Edge).

## 🎯 Usage

- **Start simulator**: Click "Simulator: Off" in the Development panel
- **View predictions**: Scroll down to see AI-driven tank predictions
- **Export data**: Use customer-facing export options
- **Settings**: Double-tap the impactOS logo to access PIN-protected settings (default: 2468)

## 🛠 Configuration

Edit these constants in the code:
- `DEVICE.cycleTime` - Cycle duration (25 seconds)
- `DEVICE.waterUsage` - Water per cycle (50mL)
- `DEVICE.energyUsage` - Energy per cycle (0.009kWh)
- `BASELINES` - Handwash and dishwash comparison values
- `CUP_COST` - Cost per paper cup (£0.30)

Location title is customizable in the navbar: "Business Design Centre"

## 📊 Data

- Daily auto-reset
- CSV export available
- localStorage persistence
- Predictive analytics for maintenance

## 🎨 Design

- Liquid glass panels with backdrop blur
- White background with colorful bubble accents on right side
- Smooth waveform animations showing cycle status
- Green badges for new cycle notifications
- Responsive grid layout

---

**Built with:** Pure HTML/CSS/JavaScript (no dependencies)  
**Designed for:** Samsung Tab A9+ in kiosk mode  
**Location:** Business Design Centre  
**Powered by:** impactOS

