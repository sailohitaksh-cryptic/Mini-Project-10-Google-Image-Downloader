# Mini-Project-10

# Google Image Downloader

This is a Python script that allows you to easily download images from Google using the Google Custom Search API. It uses the `google_images_search` package from PyPI to perform the image search and download the images.

## Installation

To use this script, you need to have Python installed on your system. You also need to install the `google_images_search` package. You can install it using pip: `pip install google_images_search`

## Getting Google Developer Custom Search Credentials

Before using the script, you need to obtain the Google Custom Search API credentials, which include the `GCS_DEVELOPER_KEY` and `GCS_CX`.


Follow these steps to obtain the credentials:

1. Visit the [Google Developers Console](https://console.developers.google.com) and create a new project.
2. Enable the "Custom Search API" for your project by visiting [Custom Search API](https://console.developers.google.com/apis/library/customsearch.googleapis.com).
3. Generate API key credentials for your project by clicking on "Create Credentials" and selecting "API key" in the Credentials section. This API key will be your `GCS_DEVELOPER_KEY`.
4. Visit [Google Custom Search Engines](https://cse.google.com/cse/all) and create a new search engine. Add `https://images.google.com/` as the URL in the "Sites to Search" section and provide a name for your search engine. Once created, you can find the `GCS_CX` key as `cx=b9b7c4211a73eae3c` in the generated code snippet, or under the "Setup" option in the left-hand side panel.

## Usage

To use the script, follow these steps:

1. Run the script using the Python interpreter.
2. Enter the item you want to search for when prompted.
3. Enter the number of images you want to download when prompted.
4. The script will search for the images on Google and download them to a folder named `query_images`, where `query` is the item you searched for.

The script will also create a zip file of the downloaded images for easier sharing and storage.

Please note that the Google Custom Search API has usage limits and pricing details. Make sure to review the API usage limits and pricing on the Google Cloud Platform website.

Feel free to modify and enhance the script according to your specific needs!

## License

This project is licensed under the [MIT License](LICENSE).
