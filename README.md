# 🌐 URL Shortener
A functional URL shortener made with TypeScript

## :pushpin: Installation
Using ```yarn``` to install all dependencies
```bash
yarn
```

Compile TypeScript to Javascript

```bash
yarn build:watch
```

To run the server

```bash
yarn dev
```


## :pencil: How to Use
Create a ```.env``` file and set these environment variables
```
MONGO_CONNECTION=Your mongodb uri
API_URL=Your server address(ex: http://localhost:5500) 
```

## Routes
- [POST] ```API_URL/shorter```
    
    Curl
    ````bash
    curl -XPOST -H "Content-type: application/json" -d '{ "originUrl": "http://www.example.com"}' "http://localhost:5500/shorter"
    
- [GET] ```/:hash``` 
  You must give a valid hash as a param, you can get it creating a shortened url 

## :bookmark: Project Responsibilities

- [x] Create a URL shortener
- [x] Redirect the original site

## :information_source: Motivation

I was rusty programming, so i decided to create a simple project to practice some typescript and node tools. 

## :raised_hand: Contributions
You can open an issue or send me a email

## :scroll: License
[MIT](https://choosealicense.com/licenses/mit/)
