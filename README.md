# 2025 Benefits Benchmarking Dashboard

An interactive dashboard showcasing the latest benefits benchmarking data from the 2025 Sequoia report for SMB companies.

## 🚀 Live Demo

The dashboard is now live at: [https://therealjmum.github.io/benefitsbenchmarking/](https://therealjmum.github.io/benefitsbenchmarking/)

## 📊 Features

- **Interactive Charts**: Visual representation of benefits distribution using Chart.js
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Real-time Data**: Based on 2025 Sequoia Benefits Benchmarking Report
- **Modern UI**: Clean, professional design with smooth animations
- **Comprehensive Coverage**: Health, Financial, and Work-Life Balance benefits

## 🛠️ Deployment Options

### Option 1: GitHub Pages (Recommended - Free)

1. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

2. **Your site will be live at**: `https://yourusername.github.io/benefitsbenchmarking/`

### Option 2: Netlify (Free)

1. **Deploy via Netlify**:
   - Go to [netlify.com](https://netlify.com)
   - Drag and drop the `index.html` file
   - Your site will be live instantly

2. **Or connect your GitHub repo**:
   - Connect your GitHub account
   - Select this repository
   - Deploy automatically

### Option 3: Vercel (Free)

1. **Deploy via Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Import your GitHub repository
   - Deploy automatically

### Option 4: Local Development

1. **Simple HTTP Server**:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js
   npx serve .
   ```

2. **Open in browser**: `http://localhost:8000`

## 📁 File Structure

```
benefitsbenchmarking/
├── index.html              # Main dashboard file
├── benefits_dashboard.html  # Original file
└── README.md              # This file
```

## 🎨 Customization

### Adding New Data

1. **Update the HTML**: Modify the benefits lists in the cards
2. **Update the Chart**: Modify the Chart.js configuration
3. **Update Styling**: Customize the CSS in the `<style>` section

### Changing Colors

The dashboard uses a purple gradient theme. To change colors:

1. **Background**: Modify the `background` property in the `body` selector
2. **Accent Colors**: Update the `#667eea` color values throughout the CSS
3. **Chart Colors**: Modify the `backgroundColor` array in the Chart.js configuration

## 📈 Data Sources

- **Primary Source**: 2025 Sequoia Benefits Benchmarking Report - SMB Edition
- **Survey Size**: 1,479 companies
- **Focus**: Small to Medium Business (SMB) companies
- **Sector**: 54% Technology companies

## 🔧 Technical Details

- **Framework**: Vanilla HTML, CSS, JavaScript
- **Charts**: Chart.js (CDN)
- **Responsive**: CSS Grid and Flexbox
- **Animations**: CSS transitions and Intersection Observer API
- **No Dependencies**: Pure frontend solution

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

For questions or issues:
- Create an issue on GitHub
- Contact: [your-email@example.com]

---

**Last Updated**: January 2025
**Version**: 1.0.0 