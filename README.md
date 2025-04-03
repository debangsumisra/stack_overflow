# Stack Overflow Tags Visualization

This project visualizes the distribution of top Stack Overflow tags over time, showing their percentage of total questions.

## Project Structure

```
line_graph/
├── app.py              # Flask application
├── static/             # Static files
│   └── index.html      # Visualization page
├── DEBANGSU.csv        # Data source
├── requirements.txt    # Python dependencies
└── README.md           # This file
```

## Setup and Running

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Run the application:
   ```
   python app.py
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## Features

- Interactive line chart showing tag distribution over time
- Percentage-based visualization for better comparison
- Responsive design that works on all devices
- Detailed tooltips showing exact percentages
- Color-coded tags for easy identification 