## VocalPrint

VocalPrint is an **AI-powered vocal mixing tool** that applies **professional vocal mix filters** to raw vocals, making them sound identical to artist-specific mixes like **Drake** or **The Weeknd**. This tool applies the exact mix characteristics, including EQ, compression, mic tone, and reverb, from trained acapellas onto any raw vocal track.

## Features
- **Transform Raw Vocals**: Upload raw vocals and apply **artist-specific vocal mix filters** (e.g., Drake, The Weeknd).
- **Professional Mixing**: Replicates the exact compression, EQ, mic sound, and reverb of the original artist.
- **Real-Time Processing**: Print the artist’s mix onto your vocals instantly.
- **Customizable**: Fine-tune EQ, reverb, and compression settings if needed.

## How It Works
1. **Train on Acapellas**: The AI learns from **acapellas** of professional artists’ tracks.
2. **Apply Mix Filters**: After training, it applies the **exact mix filters** from the learned data to your vocals.
3. **Print the Mix**: The AI **prints** the final mix, transforming your raw vocal into a polished, professional sound.

## Installation

To run this project locally, follow the steps below:

### Prerequisites
- Python 3.x
- Node.js
- npm

### Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/VocalPrint.git
    cd VocalPrint
    ```

2. Set up a virtual environment for Python:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Windows: venv\Scripts\activate
    ```

3. Install required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up the frontend:
    ```bash
    cd frontend
    npm install
    cd ..
    ```

5. Run the backend:
    ```bash
    python app.py  # Starts the backend
    ```

6. Run the frontend:
    ```bash
    cd frontend && npm start  # Starts the frontend (UI)
    ```

## How to Contribute
We welcome contributions! Here’s how you can help:
- Fork the repo
- Create a feature branch (`git checkout -b feature-name`)
- Commit your changes (`git commit -m "Add a feature"`)
- Push to your branch (`git push origin feature-name`)
- Open a pull request!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- The tool uses **deep learning models** to replicate the mixing styles of famous artists.
- Special thanks to all contributors who make this project a reality!

 VocalPrint
Transform your raw vocals with AI! VocalPrint applies pro mix filters from trained acapellas
