# IPC Multilateral Learning Dashboard

An elegant, interactive Quarto-based learning application for mastering IPC (International Price Comparison) multilateral price index methods.

## 🎯 Overview

This static website provides a comprehensive 4-week learning path covering fundamental to advanced price index calculation methods, with practical implementations in both R and Python.

## 📚 Course Content

### Week 1: Elementary Indices
- Jevons Index (geometric mean of price relatives)
- Dutot Index (ratio of arithmetic means)
- Carli Index (arithmetic mean of price relatives)
- Mathematical formulations and properties
- R and Python implementations with visualizations

### Week 2: Fisher & Törnqvist Indices
- Laspeyres and Paasche indices
- Fisher Index (superlative index)
- Törnqvist Index (weighted geometric mean)
- Axiomatic properties and tests
- Bilateral index theory

### Week 3: GEKS & GEKS-T Methods
- GEKS (Gini-Éltető-Köves-Szulc) method
- GEKS-Törnqvist approach
- Transitivity in multilateral comparisons
- Rolling window strategies
- Window length considerations

### Week 4: Advanced Techniques
- CCDI (Coordinated Consumer Price Index)
- CPD (Country-Product-Dummy) regression method
- Rolling window implementation
- Linking strategies (movement, window, half splice)
- Extension methods for long time series

## 🚀 Getting Started

### Prerequisites

- [Quarto](https://quarto.org/) (v1.4+)
- R (v4.0+) with packages: `ggplot2`, `dplyr`, `tidyverse`
- Python (v3.8+) with packages: `numpy`, `pandas`, `matplotlib`, `statsmodels`, `scikit-learn`

### Building the Site

```bash
# Clone the repository
git clone https://github.com/MaryleneH/ipc-multilateral-quarto.git
cd ipc-multilateral-quarto

# Preview the site (with live reload)
quarto preview

# Render the site
quarto render
```

The rendered site will be in the `_site/` directory.

## 🎨 Design Features

- **Elegant UX**: Modern dashboard with rounded cards, gradients, and smooth animations
- **Soft Blue Palette**: Professional color scheme (#2563eb primary, #60a5fa secondary)
- **Inter Font**: Clean, readable typography
- **Bootstrap Icons**: Visual indicators throughout
- **Responsive Design**: Mobile-first approach with breakpoints
- **Interactive Elements**: Progress bars, KPI cards, skill badges, timeline

## 📊 Features

- **Dashboard**: Overview of learning path with progress tracking
- **KPI Cards**: Visual metrics for weeks completed, exercises, and time estimates
- **Skill Badges**: Interactive badges for key competencies
- **Progress Bars**: Visual tracking of weekly completion
- **Timeline**: Step-by-step learning path visualization
- **Code Examples**: Working R and Python implementations
- **Exercises**: Guided practical exercises with hints
- **Mathematical Formulas**: LaTeX-rendered equations
- **Visualizations**: ggplot2 and matplotlib charts

## 📁 Project Structure

```
ipc-multilateral-quarto/
├── _quarto.yml          # Quarto configuration
├── custom.scss          # Custom SCSS theme
├── styles.css           # Main stylesheet
├── index.qmd            # Dashboard page
├── week1.qmd            # Week 1 content
├── week2.qmd            # Week 2 content
├── week3.qmd            # Week 3 content
├── week4.qmd            # Week 4 content
└── _site/               # Generated site (gitignored)
```

## 🎓 Learning Outcomes

By completing this course, you will:

- ✅ Understand elementary price indices and their properties
- ✅ Implement bilateral superlative indices (Fisher, Törnqvist)
- ✅ Master multilateral comparison methods (GEKS, GEKS-T)
- ✅ Apply advanced techniques (CCDI, CPD, linking)
- ✅ Code price indices in R and Python
- ✅ Visualize price index data effectively
- ✅ Handle real-world implementation challenges

## 📖 References

- ILO, IMF, OECD, Eurostat, UN, World Bank (2020). *Consumer Price Index Manual: Concepts and Methods*
- Diewert, W.E. (1976). "Exact and Superlative Index Numbers"
- Hill, R.J. (2004). "Constructing Price Indexes Across Space and Time"
- Ivancic, L., Diewert, W.E., & Fox, K.J. (2011). "Scanner Data, Time Aggregation and the Construction of Price Indexes"

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## 📄 License

This project is open source and available for educational purposes.

## 🌟 Acknowledgments

Built with [Quarto](https://quarto.org/), designed following Lovable UX principles.