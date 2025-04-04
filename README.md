# PPE Violation Detection

Flask web application for detecting PPE violations using YOLOv7.

## Quick Start

1. Install requirements:
```bash
pip install -r requirements.txt
```

2. Run the app:
```bash
python app_pc.py
```

3. Access at: `http://localhost:5000`

## Key Features
- Video file processing
- Live stream analysis
- Email alerts
- Violation reports

## Project Structure
- `app_pc.py` - Main application
- `real__hubconfCustom.py` - Detection logic
- `templates/` - Web interface
- `static/` - Assets and uploads
- `models/` - YOLOv7 model files
