
# Weather App

This project is a basic implementation of using API Integration with Vite+React framework.


## API Reference

This project using API from [API source](https://api.openweathermap.org).
for full documentation, you can access [here](https://openweathermap.org/current).

#### Get item

```http
  https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${api_key}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `city`      | `string` | **Required**. City name of item to fetch |
| `api_key`      | `string` | **Required**. Get from the website after subscribe. You can check here (https://home.openweathermap.org/api_keys) |



## Demo

Click [here](https://weather-app-five-gamma-84.vercel.app).


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`VITE_APP_ID`= put api key from https://home.openweathermap.org/ in here


## Running Tests

To run tests, run the following command

```bash
  npm run test
```


## Run Locally

Clone the project

```bash
  git clone https://github.com/Moontaz/weather-app/
```

Go to the project directory

```bash
  cd weather-app
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev 
```
