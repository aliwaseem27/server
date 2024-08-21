# Music App Backend

This repository contains the backend for the Music App, built using [FastAPI](https://fastapi.tiangolo.com/) and [PostgreSQL](https://www.postgresql.org/). The backend provides a RESTful API for managing music-related data, such as users, playlists, tracks, and more.

## Features

- **User Authentication:** Secure user registration and login using JWT tokens.
- **Playlist Management:** Create, update, and delete playlists.
- **Track Management:** Add, update, and delete tracks.
- **Search Functionality:** Search for tracks and playlists.
- **PostgreSQL Database:** Store all application data securely.
- **pgAdmin4:** Database management tool.
- **Swagger UI:** Interactive API documentation available at `/docs`.

## Technology Stack

- **FastAPI:** For creating the RESTful API.
- **PostgreSQL:** As the database to store application data.
- **SQLAlchemy:** For database migrations.
- **JWT:** For handling user authentication.

## Environment Variables

Ensure you have a `.env` file with the following variables:

```env
DATABASE_URL=postgresql://user:password@localhost/dbname
SECRET_KEY=your_secret_key
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.