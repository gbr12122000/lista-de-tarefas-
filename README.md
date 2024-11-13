<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="./assets/fonts/fonts.css">
    <title>Lista de Tarefas | G.C</title>
</head>
<body>
    <h1>Lista de Tarefas | Gabriel Correia</h1>
    <div class="content">
        <div class="content--add-item">
            <input type="text" id="input-new-task" placeholder="Digite sua nova lista">
            <button onclick="newTask()" id="btn-new-task" title="Clique aqui para adicionar uma nova lista">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-plus-lg" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M8 2a.5.5 0 0 1 .5.5v5h5a.5.5 0 0 1 0 1h-5v5a.5.5 0 0 1-1 0v-5h-5a.5.5 0 0 1 0-1h5v-5A.5.5 0 0 1 8 2Z"/>
                </svg>
            </button>
        </div>
        <div class="content--body">
            <ol id="to-do-list">
            </ol>
        </div>
    </div>
</body>
<script src="script.js"></script>
</html>
