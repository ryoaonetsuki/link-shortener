# URL Shortener

A lightweight web service for creating shortened URLs.

## Requirements

- Node.js
- npm

## Installation

```bash
git clone https://github.com/ryoaonetsuki/link-shortener.git
cd link-shortener
npm install
```

## Development

```bash
npm run dev
```

Build:

```bash
npm run build
```

Start:

```bash
npm start
```

## Usage

Run the service locally and use its web interface to submit a destination URL. The application returns a shortened URL that redirects to the destination.

## Configuration

Review the project configuration for storage, domain, and environment settings before production deployment.

## Security

Validate destination URLs and protect administrative or storage endpoints before exposing the service publicly.
