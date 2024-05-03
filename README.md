# Iconscout Downloader

Iconscout Downloader is a Python class that allows you to retrieve content (videos or images) from Iconscout URLs.

## Installation

You can install the required dependencies using pip:

pip install beautifulsoup4 requests

## Usage

from iconscout_downloader import IconscoutDownloader

# Instantiate IconscoutDownloader
downloader = IconscoutDownloader()

# Example URL
url = "https://iconscout.com/illustration-kit-editor/business-sales-growth-11474625"

# Retrieve content URL from the provided Iconscout URL
content_url = downloader.get(url)

if content_url:
    print("Content URL:", content_url)
else:
    print("No content found.")

## Documentation

For detailed documentation of the IconscoutDownloader class and its methods, refer to the docstrings in the code.

License

This project is licensed under the MIT License - see the LICENSE file for details.
