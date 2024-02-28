This is project about simple blockchain combining Linked List that coding in NodeJS and Typescript

## Install

Firstly, install packages:

```bash
npm i / npm install
# or
yarn add
```

## Run server

Secondly, run the development server:

```bash
npm run dev
# or
yarn dev
```

## How to use
![image](https://github.com/FromSunNews/SimpleBlockChain/assets/111409554/e016f272-b2b3-4cac-9b25-e93b233e4c37)
Thirdly, opening **Postman** and create new request by using **Add Request**. New request have:
1. method: **POST**
2. url: **http://localhost:8000/v1/blockchain/add_new_block**
3. data: json
Data Sample

```json
[
    {
        "sender": "Từ Nhật Phương",
        "recipient": "Adonl Hitle",
        "quantity": 1.455
    },
    {
        "sender": "Hanlis Okasa",
        "recipient": "Từ Nhật Phương",
        "quantity": 15.899
    },
    {
        "sender": "Tudes Polde",
        "recipient": "Hanji Kiloas",
        "quantity": 83.56299
    }
]
```

Good Luck!
