## API Documentation

### Endpoints

- `GET /search?q={query}` - Search for answers
- `POST /questions` - Submit new question  
- `GET /questions/{id}` - Get specific question
- `POST /answers/{id}` - Submit answer
- `GET /users/{id}` - Get user profile

### Rate Limits

- 300 requests per hour for anonymous users
- 10,000 requests per hour for authenticated users

### Response Format

All responses follow standard JSON format with proper error handling.