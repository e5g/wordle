# Wordle Clone

- Go play the real Wordle [here](https://www.powerlanguage.co.uk/wordle/)

This is just a remake of the original game as i wanted to be able to download it and modify it directly on my computer.

_To Run Locally:_
Clone the repository and perform the following command line actions:
```bash
$ cd wordle
$ npm install
$ npm run start
```

_To build/run docker container:_
```bash
$ docker build -t notwordle .
$ docker run -d -p 3000:3000 notwordle
```
open http://localhost:3000 in browser.


