# Hotel Booking System

This project contains a microservices-based hotel booking platform. The services are currently empty and serve as placeholders for future development.

## Services

- **hotel-admin-service**: Manage rooms and hotel data.
- **hotel-search-service**: Search for available rooms with filtering by location and date.
- **book-hotel-service**: Handle booking operations and adjust capacity.
- **hotel-comments-service**: Store and display user reviews.
- **notification-service**: Send notifications and process queued jobs.
- **ai-agent-service**: Provide a chatbot interface that routes requests to other services.

## Setup

1. Clone the repository.
2. Develop each service independently, preferably in Docker containers for isolation.

Each service currently contains a `.gitkeep` file so that the directories are tracked in Git. Replace these with your implementation as development progresses.

## Development Tasks

1. **Hotel Admin Service**: Implement APIs for adding rooms, updating availability and retrieving occupancy. Secure the endpoints with authentication.
2. **Hotel Search Service**: Provide filtering by location and dates, return rooms with available capacity, and show discounts for logged-in users.
3. **Book Hotel Service**: Create bookings and reduce room capacity for the selected dates. Payment integration is simulated.
4. **Hotel Comments Service**: Store comments in a NoSQL database and generate rating statistics.
5. **Notification Service**: Schedule nightly jobs to warn hotels with low capacity and send reservation details from a queue.
6. **AI Agent Service**: Build a chat interface that understands user requests and forwards them to the other services through an API gateway.

Refer to `SE4458_Final_202425_02_spring.pdf` for detailed requirements.
