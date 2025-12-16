# Agenda do Sindico

Sistema de gerenciamento de tarefas para sindicos de condominios.

## Funcionalidades

- Adicionar tarefas com titulo, descricao, categoria, prioridade e data limite
- Categorias: Manutencao, Financeiro, Reuniao, Documentacao, Emergencia
- Prioridades: Alta, Media, Baixa (com indicadores visuais coloridos)
- Filtros por status (pendentes/concluidas) e categoria
- Marcar tarefas como concluidas
- Excluir tarefas
- Estatisticas em tempo real (total, pendentes, concluidas, urgentes)
- Armazenamento local no navegador (localStorage)

## Como usar

1. Clone o repositorio:
```bash
git clone https://github.com/rafaelthome-sys/agendasindico.git
```

2. Abra o arquivo `index.html` diretamente no navegador

Ou inicie um servidor local:
```bash
python -m http.server 8080
```

3. Acesse http://localhost:8080

## Tecnologias

- HTML5
- CSS3
- JavaScript (Vanilla)
- LocalStorage para persistencia de dados

## Licenca

MIT License
