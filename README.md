# Gaming Facts

![logo](https://github.com/s1lvax/gamingfacts/assets/113994636/8f0d8a7f-fc8a-4723-bc65-9d18b2e074e8)

## Description

A simple api that returns a random interesting fact about videogames/gaming.

I wholeheartedly believe in learning-by-doing, so this is my first step into learning Go.

### Example Usage

```bash
curl https://gamingfacts.cfsilva.com/
```

Response

```json
{
  "fact": "‘Pac-Man’ was designed to attract female gamers, which led to the character’s round shape and love for eating."
}
```

### Limitations

The API is limited to `20 requests per minute`.

## Deployment

The API is deployed on a VPS using Docker and Nginx.

## Local Development

Clone the repository

```bash
git clone https://github.com/s1lvax/gamingfacts
```

Install dependencies

```bash
go mod download
```

Run API

```bash
go run main.go
```
