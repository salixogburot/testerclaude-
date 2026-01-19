# CICERO Projects Dashboard

An interactive web dashboard visualizing CICERO climate research projects data.

## View the Dashboard

### Option 1: Local Viewing
Simply open `dashboard.html` or `index.html` in your web browser.

### Option 2: GitHub Pages (Public URL)
To make the dashboard publicly accessible:

1. Go to your repository settings: https://github.com/salixogburot/testerclaude-/settings/pages
2. Under "Build and deployment":
   - Source: Select "Deploy from a branch"
   - Branch: Select `claude/create-cicero-dashboard-kWIg8` and `/ (root)`
   - Click "Save"
3. Wait a few minutes for deployment
4. Your dashboard will be available at: **https://salixogburot.github.io/testerclaude-/**

## Dashboard Features

- **Key Metrics**: Overview of total, ongoing, and completed projects
- **Interactive Charts**:
  - Project status distribution
  - Research groups breakdown
  - Projects timeline by year
  - Match type distribution
- **Searchable Table**: Filter projects by name, status, and research group
- **Direct Links**: Access to Norwegian and English project pages

## Data Source

The dashboard visualizes data from `data/cicero_projects_overview_v5.xlsx`, which contains 152 CICERO research projects spanning from 2012 to 2031.

## Technical Stack

- Pure HTML/CSS/JavaScript
- Chart.js for visualizations
- Responsive design
- No build process required
