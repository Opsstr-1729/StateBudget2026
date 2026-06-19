# 🎨 Kerala Budget 2026-27 Portal — Design & Features Guide

## ✨ **Modern Design System**

### **Color Palette (Teal-First Theme)**
Built entirely around your brand color **#0e5774** with sophisticated extensions:

```
Primary Teal Palette:
├── #051f2e (Teal-950) — Darkest background
├── #0a3447 (Teal-900) — Deep header backgrounds
├── #0e5774 (Teal-800) — Brand primary
├── #0f6b8f (Teal-700) — Accent shade
├── #1682b0 (Teal-600) — Interactive elements
└── #2a9fd2 (Teal-500) — Light hover states

Accent Colors:
├── #00e5ff (Cyan Bright) — Primary accent, highlights
├── #4df3ff (Cyan Soft) — Secondary accent
└── #a3f635 (Lime) — Tertiary accent for emphasis

Semantic Colors:
├── #10b981 (Success) — Positive indicators
├── #f59e0b (Warning) — Warnings, caution
└── #ef4444 (Error) — Negative, liabilities
```

### **Typography Stack**
3 modern font families for maximum impact:

```
1. Space Grotesk (Headers, numbers, labels)
   └─ Monospace-style, geometric, technical
   └─ Used for: Headlines, KPI values, nav labels

2. Inter (Body text, descriptions)
   └─ Contemporary sans-serif, highly readable
   └─ Used for: Paragraphs, sector names, descriptions

3. Syne (Accent headings)
   └─ Geometric, distinctive personality
   └─ Fallback for special callouts
```

### **Design Principles Applied**

✅ **Glassmorphism**: Frosted glass effect with backdrop blur
   - Cards: `backdrop-filter: blur(10px)`
   - Layered transparency: `rgba(..., 0.06-0.15)`

✅ **Gradient Excellence**: Smooth directional gradients
   - Primary: `linear-gradient(135deg, #0e5774, #1a7a9e)`
   - Text: `linear-gradient(135deg, #00e5ff, #4df3ff)`
   - Cards: Dual-layer gradients for depth

✅ **Modern Spacing**: 8px base grid
   - Comfortable padding: 2rem, 1.5rem, 1rem
   - Breathing room between elements
   - Consistent gap sizing in grids

✅ **Smooth Animations**:
   - Cubic-bezier easing: `cubic-bezier(0.4, 0, 0.2, 1)` (modern standard)
   - Duration: 0.3s-0.4s (perceptible, not sluggish)
   - Hover transforms: `translateY(-8px)` for elevation

✅ **Visual Hierarchy**:
   - KPI values: 2.4rem (Space Grotesk, bold)
   - Section titles: 1.25rem (Space Grotesk, 700)
   - Body text: 0.95rem (Inter, 400)
   - Labels: 0.8rem uppercase (Space Grotesk, 600)

---

## 🎯 **Core Features**

### **1. Overview Dashboard**
**6 KPI Cards** showing Kerala's fiscal health:
- Total Revenue Receipts: ₹1,69,646 Crore
- Revenue Expenditure: ₹2,05,002 Crore
- Total Plan Outlay: ₹30,370 Crore (revised)
- Revenue Deficit: ₹35,355 Crore
- Interest Payments: 20.9% of revenue
- Accumulated Liability: ₹87,012 Crore

*Design*: Gradient backgrounds with hover elevation, cyan value text, status indicators

### **2. Interactive Charts**
Four data visualizations using Chart.js:

**Budget Composition** (Doughnut)
- Revenue Expenditure dominance
- Color-coded segments
- Interactive legend

**Top 10 Sector Allocations** (Horizontal Bar)
- Public Works, Healthcare, Welfare leading
- Cyan gradient bars
- Smooth animations

**Category Distribution** (Pie)
- 8 major categories
- Rainbow palette based on teal theme
- Right-aligned legend

**Debt & Liabilities** (Bar)
- 6 liability categories
- Red emphasis for fiscal strain
- DA/DR/KIIFB/Pension breakdown

---

## 📊 **Sectors View**

### **Smart Data Table**
- **19 Major Sectors** with precise allocations
- **3-Column Grid**: Sector Name | Allocation | % of Plan
- **Search Filter**: Real-time query across sector names
- **Sort Options**:
  - Highest Allocation (default)
  - Lowest Allocation
  - Alphabetical (A-Z)

### **Visual Design**
- Header: Gradient background with cyan text
- Rows: Hover effect with subtle background shift
- Responsive padding animation on hover
- Allocation amounts in cyan for consistency

---

## 🚀 **Flagship Projects**

### **21 Major Projects** organized by category:

**Categories Included**:
- Maritime & Ports (Mission Samudra, Maritime Museum)
- Infrastructure (Aviation Hub, Light Metro, Renewable Energy)
- Education (Knowledge Valley, Tribal University, Research Park)
- Healthcare (Health & Life Sciences City)
- Tourism & Culture (Film City, Cultural Park, Football Stadium)
- Technology (MSME Scheme, Space Economy, Job Watch Tower)
- Social Welfare (Silver Economy, Care Giver Scheme)

### **Project Card Design**
- **Top border animation** on hover (gradient line)
- **Category badge** with teal border
- **Project name** in Space Grotesk (1.2rem)
- **Description** in Inter (0.9rem, muted)
- **Budget allocation** in cyan, monospace
- **Elevation effect** on interaction (`translateY(-10px)`)

### **Interactive Features**
- **Text Search**: Query project names/descriptions
- **Category Filter**: Drill down by project type
- **Real-time Results**: Instant filtering with "No results" state
- **Card Grid**: 3-column on desktop, 1-column on mobile

---

## 🔍 **Analysis Tab**

**Advanced Insights Dashboard**:
- **Sector-wise Trend Chart**: Line graph with point interactivity
- **SOTR Decline Analysis**: State Own Tax Revenue metrics
- **Committed Expenditure**: 77% of revenue receipts
- **Capital Expenditure**: 1.3% of GSDP (lowest nationally)

---

## 📱 **Responsive Design**

### **Breakpoints**:
```
Desktop (1200px+):
├─ Sectors: 2-column grid
├─ Charts: 2-column layout
└─ Projects: 3-column grid

Tablet (768px - 1023px):
├─ Sectors: 1-column
├─ Charts: 1-column
└─ Projects: 1-column

Mobile (<768px):
├─ Header: Stacked logo + nav
├─ KPIs: Single column
├─ All grids: 1-column
└─ Touch-friendly buttons (48px minimum)
```

### **Mobile Optimizations**:
- Horizontal scrolling for long sector names
- Tap-friendly filter buttons
- Full-width search inputs
- Smaller font sizes (0.8-0.85rem)
- Reduced padding on mobile cards

---

## 🎨 **Color Usage Guide**

| Component | Color | Hex |
|-----------|-------|-----|
| Primary Header | Teal-900 gradient | #0a3447 → #0e5774 |
| KPI Values | Cyan → Teal gradient | #00e5ff → #4df3ff |
| Card Borders | Cyan light | rgba(74, 184, 230, 0.2) |
| Sector Allocations | Cyan bright | #00e5ff |
| Category Badges | Teal border | rgba(74, 184, 230, 0.3) |
| Success indicators | Green | #10b981 |
| Warning/Negative | Orange/Red | #f59e0b / #ef4444 |
| Hover states | Cyan light | rgba(74, 184, 230, 0.1-0.15) |

---

## ⚡ **Performance Features**

✅ **Single-File HTML** — No external dependencies except Chart.js
✅ **CSS Animations** — GPU-accelerated transforms
✅ **Lazy Loading** — Charts render on demand
✅ **Responsive Images** — SVG icons, no bitmap waste
✅ **Fast Search** — Client-side filtering
✅ **Modern Scrollbar** — Styled with teal gradient

---

## 🔧 **Customization Guide**

### **Change Primary Color**
Edit CSS variables in `:root`:
```css
--teal-800: #0e5774;      /* Change brand primary */
--teal-900: #0a3447;      /* Change header */
--cyan-bright: #00e5ff;   /* Change accent */
```

### **Modify KPI Cards**
```javascript
// Update the KPI grid in HTML overview tab
<div class="kpi-card">
    <div class="kpi-label">YOUR LABEL</div>
    <div class="kpi-value">YOUR NUMBER</div>
    <div class="kpi-unit">UNIT</div>
</div>
```

### **Add New Sectors**
```javascript
// In budgetData.sectors array:
{ 
    name: 'Your Sector Name', 
    allocation: 1000,  // ₹ Crore
    category: 'Infrastructure' 
}
```

### **Add New Projects**
```javascript
// In budgetData.projects array:
{ 
    name: 'Project Name', 
    allocation: 500,
    category: 'Infrastructure',
    description: 'Project description here'
}
```

---

## 📲 **Browser Support**

✅ Chrome 90+
✅ Firefox 88+
✅ Safari 14+
✅ Edge 90+
✅ Mobile browsers (iOS Safari, Chrome Android)

*Note: Requires CSS Grid, Flexbox, backdrop-filter support*

---

## 🎯 **Key Metrics Displayed**

### **Fiscal Summary**:
- Revenue Receipts: ₹1,69,646 Cr
- Revenue Expenditure: ₹2,05,002 Cr
- Plan Outlay: ₹30,370 Cr
- Revenue Deficit: -₹35,355 Cr
- Interest burden: 20.9% of revenue
- Accumulated debt: ₹87,012 Cr

### **Top Allocations**:
1. Public Works: ₹5,952 Cr
2. Medical Care & Health: ₹2,076 Cr
3. SC Welfare: ₹2,979 Cr
4. Rural Development: ₹2,139 Cr
5. Transport: ₹1,579 Cr

### **Major Projects**:
- Mission Samudra: ₹400 Cr
- Aviation Hub: ₹200 Cr
- Health & Life Sciences City: ₹100 Cr
- Knowledge Valley: ₹100 Cr
- Film City: ₹100 Cr

---

## 🚀 **Future Enhancement Ideas**

- [ ] Export to PDF/CSV
- [ ] Year-over-year comparison charts
- [ ] Department head detail pages
- [ ] Real-time data integration via Google Sheets API
- [ ] Dark/Light theme toggle
- [ ] Print-optimized layouts
- [ ] Mobile app wrapper
- [ ] Accessibility (WCAG AA compliance)
- [ ] Multi-language support (Malayalam/English)
- [ ] Interactive budget allocation simulator

---

## 📞 **Support & Notes**

This portal is built with modern web standards and requires no build tools. Simply open the HTML file in a browser.

**Design Approach**: Modern 2026-compliant aesthetic with teal-first color psychology, glassmorphism effects, and subtle animations for professional government applications.

**Data Source**: Kerala Budget Speech 2026-27 (Chief Minister V.D. Satheesan)

---

**Last Updated**: 19 June 2026
**Version**: 1.0 Modern Edition
**Status**: Production Ready ✅
