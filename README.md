# Hexagonal Architecture Training Project
This is a training project to practice hexagonal architecture.
## Requirements
 - Create a micro-service to manage hotels' information.
 - Create a hotel
 - Create a room
 - Update a hotel
 - Update a room
 - Filter by  hotel id, name, and number of rooms.
## Database
 - Postgres in a Docker container.
## Testing
 - Unit and integration tests.
## Data Model
### Hotel
 - Long: id
 - String: name
 - String: description
 - Integer: stars
 - List<Room>: rooms
### Room
 - Long: id
 - RoomType: type
### RoomType
 - Long: id
 - Integer: Beds
 - String: Description
