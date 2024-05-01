# YouTube Downloader 🚀 By Arash Ariamanesh

This is a simple YouTube video downloader built using Streamlit and Pytube. It allows users to download videos from YouTube by providing the URL and selecting the desired video resolution.

## Features

- Allows users to input YouTube video URL.
- Retrieves video details such as title, length, available resolutions, frame rate, and format.
- Provides a selection box for choosing the desired video resolution.
- Enables users to specify the filename for saving the downloaded video.
- Downloads the selected video with the chosen resolution.

## Installation

To run this application locally, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/arash-ariamanesh/youtube-downloader.git
```

2. Navigate to the project directory:

```bash
cd Youtube-downloader
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Run the Streamlit application:

```bash
streamlit run src/main.py
```

## Usage

1. Open the application in your web browser.
2. Paste the URL of the YouTube video you want to download in the provided text input field.
3. Select the desired video resolution from the dropdown menu.
4. Optionally, specify the filename for saving the downloaded video.
5. Click the "Download" button to initiate the download.
6. Once the download is complete, the success message will be displayed.

## Credits

- [Streamlit](https://streamlit.io/) - For creating the interactive web application.
- [Pytube](https://github.com/pytube/pytube) - For providing the YouTube video downloading capabilities.

## Author

- Arash Ariamanesh - [GitHub](https://github.com/arash-ariamanesh)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
