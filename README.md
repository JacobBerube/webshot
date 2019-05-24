# Webshot
Webshot is a CLI interface for creating perfect full-height vector PDF screenshots of webpages. Based on Google's Puppeteer. In order to support H.264 video and other advanced features, Google Chrome is required to be installed.

## Installation
`npm install -g JacobBerube/webshot`

## Usage
`webshot https://jacobberube.com -s mobile`

Supports a `-s` argument for the output size. Options are `mobile` or `desktop`. Mobile size is an iPhone X width screen.

## Known issues
Right now, all pages are exported as the same height which means there will be extra whitespace at the bottom of the PDF.
