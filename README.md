# URL Shortener using Redis and Docker

Simple URL shortener and resolver API that stores the shortened keys in a Redis node running on a local Docker container.

### Features:

1. Support for custom short URLs
2. Consumer can request lease time (upto 24 hours) for short URLs
3. Rate limited API with limit reset time
4. Quick Redis server setup with Docker containers
