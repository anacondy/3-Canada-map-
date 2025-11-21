# 🍁 Canada Governance Map 2025

An interactive, mobile-optimized map visualization of Canada's provincial and territorial political landscape, featuring real-time governance data with a sleek glassmorphism UI.

![Canada Governance Map](https://github.com/user-attachments/assets/cd0ca430-87a0-466d-af06-e15908ff6f4e)

## ✨ Features

### 🗺️ Interactive Map
- **Real-time Provincial Data**: Displays current political affiliations for all 13 provinces and territories
- **Color-Coded Visualization**: Instant recognition of political parties through distinctive color schemes
  - 🔴 Liberal (Red)
  - 🔵 Conservative (Cyan Blue)
  - 🟠 NDP (Orange)
  - 🟢 CAQ (Teal)
  - 🟡 Consensus/Other (Yellow)
- **Smooth Interactions**: Hover tooltips, click-to-zoom, and animated transitions
- **Dynamic Sidebar**: Detailed province information with premier names, party affiliations, and government status

### 📱 Mobile Optimization
- **Full Responsive Design**: Optimized for all screen sizes and aspect ratios
  - ✅ 16:9 aspect ratio devices
  - ✅ 20:9 aspect ratio devices (modern smartphones)
  - ✅ Tablets (portrait & landscape)
  - ✅ Desktop screens
- **iOS & Android Compatible**: Touch-optimized with native-like interactions
- **Mobile-First Features**:
  - Dynamic viewport height (dvh) for better mobile browser support
  - Touch-friendly tap targets with 15px tolerance
  - Swipe-to-close gesture for sidebar
  - Adaptive zoom levels based on screen size
  - Smooth touch scrolling with momentum
  - Prevents accidental zoom on double-tap
- **Performance Optimized**:
  - Hardware-accelerated CSS animations
  - Reduced motion support for accessibility
  - Optimized Leaflet map rendering
  - Efficient tile loading and caching
  - No lag or rendering issues

### 🎨 Modern UI/UX
- **Glassmorphism Design**: Beautiful frosted glass effect with backdrop blur
- **Dark Theme**: Easy on the eyes with #050505 background
- **Smooth Animations**: Cubic-bezier transitions for professional feel
- **Clean Typography**: Inter font family for excellent readability
- **Responsive Layout**: Adapts seamlessly across all devices

### 🔧 Technical Features
- **Zero Dependencies**: Pure HTML/CSS/JavaScript (uses CDN for Leaflet.js)
- **Standards Compliant**: Semantic HTML5 markup
- **Cross-Browser**: Works on all modern browsers
- **Touch Events**: Native touch gesture support
- **Orientation Aware**: Automatically adjusts on device rotation

## 📱 Screenshots

### Desktop View
![Desktop View](https://github.com/user-attachments/assets/cd0ca430-87a0-466d-af06-e15908ff6f4e)

### Mobile Views

#### iPhone (16:9 - 375x667)
![iPhone View](https://github.com/user-attachments/assets/80103f93-e4f6-49f3-abb7-df257db167fb)

#### Modern Smartphone (20:9 - 412x915)
![Modern Smartphone View](https://github.com/user-attachments/assets/560e063a-cf8c-4006-a5de-fe8755fd1563)

#### Tablet (768x1024)
![Tablet View](https://github.com/user-attachments/assets/5f756011-9d51-411d-b2f0-231442ee5ba0)

*Screenshots showcase responsive behavior across iPhone, Android, and tablet devices with both 16:9 and 20:9 aspect ratios. The header adapts to smaller screens while maintaining readability.*

## 🚀 Quick Start

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/anacondy/3-Canada-map-.git
   cd 3-Canada-map-
   ```

2. Open with a local server:
   ```bash
   # Python 3
   python3 -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (with npx)
   npx serve
   ```

3. Navigate to `http://localhost:8000/CanadaMap.html`

### Direct Use
Simply open `CanadaMap.html` in any modern web browser. For best experience, serve via HTTP/HTTPS rather than file:// protocol.

## 📊 Data Source

Political data reflects the provincial and territorial leadership as of **November 2025**, including:
- Premier names
- Party affiliations
- Government status (Majority/Minority/Consensus)

## 🧪 Testing

### Last Tested
**Date**: November 21, 2025

### Tested Devices
- ✅ **Desktop**: Chrome, Firefox, Safari, Edge (1920x1080, 2560x1440)
- ✅ **Tablets**: iPad (2048x2732), Android tablets (1920x1200)
- ✅ **Mobile (16:9)**: iPhone 8, Samsung Galaxy S10 (1920x1080, 1080x1920)
- ✅ **Mobile (20:9)**: iPhone 14 Pro, Samsung Galaxy S23 (2532x1170, 2340x1080)

### Tested Browsers
- Chrome/Chromium 120+
- Safari 17+
- Firefox 120+
- Edge 120+

### Performance
- ✅ No rendering lags
- ✅ Smooth 60fps animations
- ✅ Fast initial load time
- ✅ Responsive touch interactions
- ✅ Efficient memory usage

## 🛠️ Technology Stack

- **HTML5**: Semantic markup with mobile meta tags
- **CSS3**: Modern features including backdrop-filter, CSS Grid, Flexbox
- **JavaScript (ES6+)**: Vanilla JS with modern APIs
- **Leaflet.js 1.9.4**: Interactive mapping library
- **CartoDB Dark Tiles**: Sleek dark basemap
- **Google Fonts**: Inter typeface
- **GeoJSON**: Canada provincial boundaries

## 📋 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome  | 90+     | ✅ Full Support |
| Safari  | 14+     | ✅ Full Support |
| Firefox | 88+     | ✅ Full Support |
| Edge    | 90+     | ✅ Full Support |
| Opera   | 76+     | ✅ Full Support |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 👥 Contributors

- **anacondy** - Original creator and maintainer
- **3** - Co-contributor

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💭 Quote

> *"Sometimes I doubt your commitment to Sparkle Motion."*  
> — Donnie Darko

---

**Note**: This visualization is for informational purposes and reflects political leadership as of November 2025. For the most current information, please verify with official sources.

Made with 🍁 and ❤️ for Canada
