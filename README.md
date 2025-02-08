# fetch-rewards
backend exercise
## About
This is the backend exercise provided by fetch. Refer to details at [receipt-processor-challenge](https://github.com/fetch-rewards/receipt-processor-challenge/tree/main). \
I chose to use Python just because of previous similar experiences.

## Project Structure
All source code are in the root directory. A.k.a. no structure. \
The backend implementation can be found in `app.py`.

## Build Docker Image
To build the Docker image, you can use the following command:
```
docker build -t fetch-backend .
```
Feel free to replace `fetch-backend` with any name you please.

Run the Docker image in a container
```
docker run -d -p 3000:3000 fetch-backend
```
This command runs the container in the detach mode and maps the opened 3000 port to localhost:3000.

## Postman
A Postman collection exported as json is provided at your disposal. \
It contains the 2 tests provided in the original project repo.