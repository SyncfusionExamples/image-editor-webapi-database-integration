# Image Editor WebAPI Database Integration

## Repository Description

This API sample demonstrates how to load and save images to a database using the Image Editor. It provides a complete solution for managing image data with database persistence, including upload, retrieval, and editing capabilities through a web interface.

## Features

- **Image Upload**: Upload images directly to the database with validation
- **Image Editing**: Interactive editing capabilities using the Image Editor component
- **Database Persistence**: Seamless storage and retrieval from the database
- **RESTful API**: Comprehensive API endpoints for all image operations
- **Web Interface**: User-friendly interface for image management and editing

## Prerequisites

- Node.js (version 12.0 or higher)
- Compatible database system (SQL Server, MongoDB, or similar)
- Basic knowledge of REST APIs and web development
- Image Editor library installed and configured

## Installation

1. Clone the repository
2. Install dependencies: `npm install`
3. Configure database connection in the environment file
4. Initialize the database schema with migration scripts
5. Start the server: `npm start`

## Usage

### Workflow

1. Navigate to the web interface
2. Upload an image using the upload feature
3. Open the image in the Image Editor
4. Make desired edits and save
5. Edited image persists to the database

### API Endpoints

- `GET /api/images` - Retrieve all images
- `POST /api/images` - Upload a new image
- `GET /api/images/:id` - Get a specific image
- `PUT /api/images/:id` - Update an image
- `DELETE /api/images/:id` - Delete an image

## Configuration

Environment variables:

- `DATABASE_URL` - Database connection string
- `PORT` - Server port (default: 3000)
- `IMAGE_UPLOAD_LIMIT` - Maximum upload size in MB

## Contributing

Contributions welcome! Follow existing code style and submit pull requests with clear descriptions.

## License

This project is provided as a sample for educational and commercial use.
