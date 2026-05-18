# NeuroEdit

Premium-for-free AI image editing application offering pro features like U²-Net background removal, Generative Fill outpainting, Portrait Mode (Bokeh), and Cinematic LUTs without the subscription.

## Architecture

- **Frontend:** HTML/CSS/Vanilla JS (Standalone interface based on the NeuroEdit Web Studio)
- **Backend:** FastAPI wrapper around PyTorch U²-Net (Rembg) for salient object detection and background removal.

## Setup

### Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn app:app --reload
```

### Frontend

Just open `frontend/index.html` in your browser.
