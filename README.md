# Webshot
Webshot is a CLI interface for creating perfect full-height vector PDF screenshots of webpages. Based on Google's Puppeteer. In order to support H.264 video and other advanced features, Google Chrome is required to be installed.

## Installation
`npm install -g JacobBerube/webshot`

## Usage
`webshot https://jacobberube.com -s mobile`

Supports a `-s` argument for the output size. Options are `mobile` or `desktop`. Mobile size is an iPhone X width screen.

## Known issues
Right now, there is an issue with height calculation that may cause some pages to export to the wrong height, causing overflow onto a second page or extra white space.
