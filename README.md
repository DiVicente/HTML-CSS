<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de Suporte</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        .header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        .main-content {
            margin-top: 2rem;
        }
        .media img {
            margin-right: 1rem;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Comunidade de Suporte a Mães</h1>
    </div>
    <div class="container main-content">
        
        <div class="row">
            <div class="col-md-6">
                <h2>Lista de Recursos</h2>
                <ul class="list-group">
                    <li class="list-group-item">Artigo sobre Cuidados</li>
                    <li class="list-group-item">Vídeo Educativo</li>
                    <li class="list-group-item">Guia de Terapia</li>
                </ul>
            </div>
        </div>
        
        <div class="row mt-4">
            <div class="col-md-6">
                <h2>Tabela de Eventos</h2>
                <table class="table table-striped">
                    <thead>
                        <tr>
                            <th>Data</th>
                            <th>Evento</th>
                            <th>Local</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>15/07/2024</td>
                            <td>Workshop de Terapia</td>
                            <td>São Paulo</td>
                        </tr>
                        <tr>
                            <td>22/07/2024</td>
                            <td>Grupo de Apoio</td>
                            <td>Rio de Janeiro</td>
                        </tr>
                        <tr>
                            <td>29/07/2024</td>
                            <td>Sessão de Terapia Online</td>
                            <td>Online</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
        
        <div class="row mt-4">
            <div class="col-md-12">
                <h2>Mídia em Destaque</h2>
                <div class="media">
                    <img src="https://via.placeholder.com/150" class="mr-3" alt="Imagem de exemplo">
                    <div class="media-body">
                        <h5 class="mt-0">Título da Mídia</h5>
                        Descrição breve sobre o conteúdo da mídia. Pode ser um vídeo, um artigo ou qualquer outro recurso útil.
                    </div>
                </div>
            </div>
        </div>
        
        <div class="row mt-4">
            <div class="col-md-12">
                <h2>Formulário de Contato</h2>
                <form>
                    <div class="form-group">
                        <label for="nome">Nome</label>
                        <input type="text" class="form-control" id="nome" placeholder="Digite seu nome">
                    </div>
                    <div class="form-group">
                        <label for="email">E-mail</label>
                        <input type="email" class="form-control" id="email" placeholder="Digite seu e-mail">
                    </div>
                    <div class="form-group">
                        <label for="telefone">Telefone</label>
                        <input type="tel" class="form-control" id="telefone" placeholder="Digite seu telefone">
                    </div>
                    <div class="form-group">
                        <label for="data-nascimento">Data de Nascimento</label>
                        <input type="date" class="form-control" id="data-nascimento">
                    </div>
                    <div class="form-group">
                        <label for="mensagem">Mensagem</label>
                        <textarea class="form-control" id="mensagem" rows="3" placeholder="Escreva sua mensagem"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Enviar</button>
                </form>
            </div>
        </div>
    </div>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
