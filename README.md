# Accessibility Testing: CDP vs Lighthouse Comparison

This project provides a comparison between Chrome DevTools Protocol (CDP) Audits and Lighthouse accessibility detection capabilities. It's meant to understand the differences and coverage gaps between these two important 

## Project Structure

```
├── README.md
├── index.html           # Interactive demo landing page
└── a11y-test-sites/           # Test cases for different accessibility issues
```

### Usage

**Start with the Demo Landing Page**:
   ```bash
   # Open in your browser
   index.html
   ```

**Explore Individual Test Cases**:
   Navigate to any HTML file in the `a11y-test-sites/` directory to see specific accessibility issues in action.

### Manual Testing Steps

1. **Open Test Files**: Load any HTML file from `a11y-test-sites/` in Chrome
2. **Enable DevTools**: Press `F12` or right-click → Inspect
3. **Check Issues Panel**: Look for accessibility issues in the Issues tab
4. **Run Lighthouse**: Go to Lighthouse tab → Run accessibility audit
5. **Compare Results**: Note which issues are detected by each tool

