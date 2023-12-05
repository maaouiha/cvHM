# CV project with Next.js and Docker

## Development phase

1. Clone the repository:

    ```bash
    git clone https://github.com/othmenbelgacem/othmen_portfolio.git
    cd othmen_portfolio
    ```

2. Building and Running with Docker Compose:

    Build and run the Docker containers using Docker Compose:

    ```bash
    docker-compose up --build
    ```

    This command will build the Docker image and start the container.

3. Access the Application:

    Open [http://localhost:3000](http://localhost:3000) with your browser to view the application.

4. Development in the Container:

    You are now inside the container. Carry out your development tasks as normal. The page updates automatically as you edit the file.

5. Container Shutdown:

    When you're done, you can stop and remove the containers by running:

    ```bash
    docker-compose down
    ```

6. Other Useful Commands:

    - To list all running containers: 
      ```bash
      docker ps
      ```

    - To list all containers (including stopped ones):
      ```bash
      docker ps -a
      ```

    - To stop a running container:
      ```bash
      docker stop <CONTAINER_ID>
      ```

7. Additional Notes:

    - Make sure the port needed for development is exposed in the Dockerfile.
    - Development-specific configurations can be adjusted in the Dockerfile or docker-compose.yml as needed.
