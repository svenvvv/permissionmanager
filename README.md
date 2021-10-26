# Permission Manager, containerized

A node-based permission manager.

Allows you to create permissions and permission hierarchies.

By default the web interface listens on port 8000 and the back-end on port 8080.

## Setup

For information on setting up the modules individually and outside of containers
refer to the README files in the module repositories.

### Prerequisites

Install docker and docker-compose from your package manager.

### Build images

Build images by executing:
```
docker-compose build
```

### Run images

Run images by executing:
```
docker-compose up
```

After the initialization procedure, navigate to [http://localhost:8000](http://localhost:8000) to view the web interface.
