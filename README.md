const express = require('express');
const app = express();
const port = 8080;

app.get('/', (req, res) => {
    res.send('GET request to the homepage');
});

app.post('/', (req, res) => {
    res.send('POST request to the homepage');
});

app.listen(port, () => {
    console.log(`Servidor rodando na porta ${port}`);
});# cd-3
