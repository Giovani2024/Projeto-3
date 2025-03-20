### Frontend (Exemplo simplificado)##

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/static/css/styles.css">
    <script src="/static/js/scripts.js" defer></script>
    <title>Controle de Chaves</title>
</head>
<body>
    <h1>Controle de Entrada e Saída de Chaves</h1>
    <form id="key-form">
        <input type="text" name="name" placeholder="Nome" required>
        <input type="text" name="phone" placeholder="Telefone" required>
        <input type="text" name="company" placeholder="Empresa" required>
        <input type="text" name="key_code" placeholder="Código da Chave" required>
        <input type="time" name="pickup_time" required>
        <input type="date" name="date" required>
        <button type="submit">Registrar</button>
    </form>
    <div id="logs"></div>
</body>
</html>
```
