# n8n Integration Docs

This project documents and provides a setup to integrate [n8n](https://n8n.io/), an open-source workflow automation tool. It includes configuration examples and required environment variables to connect services like OpenAI and Supabase.

## Features

- Integration with the OpenAI API for natural language processing.
- Connection with Supabase for data storage and retrieval.
- Basic authentication setup to secure access to n8n.

## Prerequisites

Make sure you have the following installed:

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Steps to Run

1. **Clone the repository**:

   ```bash
   git clone <REPOSITORY_URL>
   cd n8n-integration-docs
   ```

2. **Configure environment variables**:

   Rename the `.env.example` file to `.env` and update the values as needed:

   ```bash
   cp .env.example .env
   ```

3. **Start services with Docker Compose**:

   Run the following command to start n8n and its related services:

   ```bash
   docker-compose up -d
   ```

4. **Access n8n**:

   After starting the services, n8n will be available in your browser at:

   ```
   http://localhost:5678
   ```

   Use the credentials configured in the `.env` file to log in.

5. **Stop services**:

   To stop the services, run:

   ```bash
   docker-compose down
   ```

## Contribution

Feel free to open issues or submit pull requests to improve this project.

## License

This project is licensed under the [MIT License](LICENSE).
