# NFL Player Performance Analysis

This project analyzes NFL player performance data and provides insights for sponsorship opportunities using a Dash web application.

## Features

- Analyze player performance metrics such as touchdowns, yardage, and receptions.
- Compare player performance across different seasons.
- Visualize player performance using interactive graphs.
- Predict player sponsorship suitability using machine learning models.

## Installation

### Prerequisites

- Python 3.8 or higher
- Poetry

### Setup

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/nfl-player-analysis.git
    cd nfl-player-analysis
    ```

2. **Install dependencies:**

    ```sh
    poetry install
    ```

3. **Download the dataset:**

    The dataset is downloaded automatically using the `kagglehub` package. Ensure you have your Kaggle API credentials set up.

4. **Run the application:**

    ```sh
    poetry run python app.py
    ```

## Usage

- Navigate to `http://127.0.0.1:8050/` in your web browser to access the application.
- Use the season slider to select the range of seasons for analysis.
- Select players from the dropdowns to compare their performance.
- View various performance metrics and sponsorship predictions.

## Project Structure

- `app.py`: Main application file.
- `player_analysis.py`: Contains functions for data analysis and visualization.
- `data/`: Directory for storing datasets.
- `assets/`: Directory for storing static assets like CSS files.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.