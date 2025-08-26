# Bank of Checkmarx - Bank API

A Flask-based REST API service for the Bank of Checkmarx demo application with intentionally vulnerable endpoints. This service handles user authentication, account management, file operations, network utilities, and provides core banking functionality for the financial platform.

## Security Note

⚠️ **This is an intentionally vulnerable application for security testing purposes. Do not deploy in production or sensitive environments.**

## Overview

The Bank API is a Flask application that provides core banking functionality including user authentication, account data retrieval, file processing, and system operations. It integrates with SQLAlchemy for database operations and provides comprehensive logging and monitoring capabilities.

## Key Features

- **User Authentication**: JWT-based authentication system with session management
- **Account Management**: Account balance and information retrieval
- **File Operations**: File upload and processing capabilities
- **Network Utilities**: Ping functionality and network diagnostic tools
- **Comment System**: User-generated content handling and validation
- **Command Execution**: Subprocess execution for system operations
- **SQLAlchemy Integration**: Database operations with SQLite/PostgreSQL support
- **CORS Support**: Cross-origin resource sharing configuration
- **Health Monitoring**: Service health checks and dependency monitoring
- **Structured Logging**: Configurable logging with multiple levels

## Technology Stack

- **Python 3.8+**: Programming language
- **Flask 2.3.3**: Web framework
- **Werkzeug 2.3.7**: WSGI utilities
- **Flask-CORS 4.0.0**: Cross-origin resource sharing
- **SQLAlchemy 2.0.23**: Database ORM and query building
- **PyJWT 2.8.0**: Token-based authentication
- **Requests 2.31.0**: HTTP client for external API calls
- **aiohttp 3.9.1**: Asynchronous HTTP operations
- **Redis 5.0.1**: Caching and session storage
- **Cryptography 41.0.7**: Cryptographic operations
