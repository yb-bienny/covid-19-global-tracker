# covid-19-global-tracker
# COVID-19 Global Data Dashboard

An interactive web application for visualizing and analyzing global COVID-19 data trends, featuring real-time statistics, country comparisons, and vaccination progress tracking.

## Features

- 📊 Real-time global statistics dashboard
- 📈 Interactive time-series visualizations
- 🌍 Country-by-country comparison tools
- 💉 Vaccination progress tracking
- 📱 Responsive design for all devices

## Data Source

This dashboard uses the Our World in Data COVID-19 dataset, which provides comprehensive, up-to-date information about:

- Total cases and deaths
- New cases and deaths
- Vaccination rates
- Population statistics

Data is automatically refreshed every 6 hours to ensure accuracy while maintaining performance.

## Technologies Used

- **matplotlib**
- **pandas**
- **anaconda-jupyter**

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open your browser to the provided local URL

## Project Structure

```
src/
├── api/          # API integration
├── components/   # React components
├── types/        # TypeScript definitions
└── App.tsx       # Main application
```

## Key Features

### Global Statistics
- Total cases worldwide
- Total deaths
- Vaccination progress
- Number of affected countries

### Country Comparison
- Compare up to 8 countries
- Multiple metrics available:
  - Total cases
  - New cases
  - Total deaths
  - New deaths
- Adjustable time periods:
  - Last 30 days
  - Last 90 days
  - Last 180 days
  - Last year

### Vaccination Tracking
- Country-wise vaccination rates
- Progress visualization
- Population coverage statistics

## Performance Considerations

- Data caching to minimize API calls
- Optimized chart rendering
- Responsive image loading
- Efficient state management

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT license.
