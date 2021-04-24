# Netflix Clone

This project is a replica of the Netflix App, it allows the user to search top rated movies by genre.

![Logo](https://thewhitonline.com/wp-content/uploads/2021/03/Netflix.jpg)

## Demo

![Alt Text](https://media.giphy.com/media/27beCzep4HaiW064Rx/giphy.gif)

## Features

- JavaScript - client-side
- React
- TMDB - api requests
- react-youtube
- firebase - backend
- Cross platform

## Lessons Learned

During this project i learned how to make api requests with `axios`
promise-based HTTP client that sports an easy-to-use API and can be used in both the browser and Node. js. Making HTTP requests to fetch or save data.

## Deployment Version

To deploy this project in browser and give it a spin.

Open [https://netflix-clone-17f20.firebaseapp.com/](https://netflix-clone-17f20.firebaseapp.com/) to view it in the browser.

## Run Locally

Clone the project

```bash
  git clone https://github.com/ShamelLakin/netflix-clone.git
```

Go to the project directory

```bash
  cd netflix-clone
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## API Reference

#### Get all items

```http
  GET "https://api.themoviedb.org/3"
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${YOUR_API_KEY}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. `/trending/all/week?api_key=${API_KEY}&language=en-US` |

## License

[MIT](https://choosealicense.com/licenses/mit/)




  

