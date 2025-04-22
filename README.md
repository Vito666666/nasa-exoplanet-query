# 🚀 NASA Exoplanet Query App

A sleek and efficient web application that allows users to explore over 4,000+ exoplanets discovered outside our solar system using data from [NASA's Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/).

## 🌌 Features

- 🔍 Filter exoplanets by:
  - Year of Discovery
  - Discovery Method
  - Host Name
  - Discovery Facility
- 📋 View results in a responsive, sortable table
- 🔗 Host name links to NASA’s Confirmed Planet Overview (opens in new tab)
- ⚠️ Error handling for invalid searches
- 🪑 Clear/reset filters and results easily

## 🎯 Bonus Features

- Sort results ascending/descending by any column
- Dynamic table headers with sorting icons

## 🧰 Technologies Used

**Frontend:**
- React.js (with Hooks)
- Tailwind CSS
- Shadcn/UI for elegant UI components
- React Table or TanStack Table for data rendering
- Framer Motion (optional animations)

**Backend / Data Handling:**
- Node.js (optional for preprocessing or hosting)
- CSV Parser (`papaparse` or backend conversion)
- Optimized JSON data structure for fast lookup

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/nasa-exoplanet-query.git
cd nasa-exoplanet-query
npm install
npm run dev
```

Then visit: `http://localhost:5173`

## 📂 Project Structure

```
src/
├── components/
│   └── QueryPanel.jsx
│   └── ResultsTable.jsx
├── data/
│   └── exoplanets.json
├── utils/
│   └── filterUtils.js
├── App.jsx
└── main.jsx
```

## 🌐 Live Demo

Coming soon!

## 📖 License

MIT

---

Built with ❤️ for the stars.
