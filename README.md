# Parallel Algorithm Executor

A web-based system to upload, store, and execute parallel algorithms written in various programming languages, such as Python and C++. Built with Django, Celery, and Redis, this project supports real-time updates on the execution process and results.

## Features

- **Algorithm Upload**: Upload and store algorithms written in Python or C++.
- **Parallel Execution**: Execute algorithms in parallel using Celery.
- **Real-time Updates**: Get real-time updates on the execution status via WebSockets.
- **Result Visualization**: Display execution results and logs.

## Requirements

- Python 3.9+
- Django 3.2+
- Celery 5.0+
- Redis
- GCC (for compiling C++ code)
- Gunicorn (for serving the Django application)
- Docker (for containerization)

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/parallel-algorithm-executor.git
cd parallel-algorithm-executor
```
