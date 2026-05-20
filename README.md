# flanker_do_badan_emocje
Zadanie typu Flankera do eksperymentu dotyczącego oceny fragmentów filmów i muzyki
<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Zadanie Flankera</title>

<script src="https://cdn.jsdelivr.net/npm/xlsx/dist/xlsx.full.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@4/dist/email.min.js"></script>

<style>
body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin-top: 40px;
}

#stimulus {
    font-size: 56px;
    margin-top: 50px;
}

input {
    padding: 10px;
    font-size: 18px;
    margin-top: 10px;
}

button {
    padding: 12px 24px;
    font-size: 18px;
    margin-top: 20px;
    cursor: pointer;
}
</style>
</head>
<body>

<div id="flanker-task">

<h2>Zadanie Flankera</h2>

<div id="instruction-screen">

<p>Za chwilę zobaczysz ciągi strzałek.</p>

<p>
Twoim zadaniem jest wskazanie kierunku ŚRODKOWEJ strzałki.
</p>

<p>
Jeżeli środkowa strzałka wskazuje w lewo — naciśnij klawisz <b>A</b>.
</p>

<p>
Jeżeli środkowa strzałka wskazuje w prawo — naciśnij klawisz <b>L</b>.
</p>

<p>
Odpowiadaj możliwie szybko i dokładnie.
</p>

<h3>Numer osoby badanej</h3>

<input type="text" id="participant-id" placeholder="Wpisz numer osoby badanej">

<br>
</html>
