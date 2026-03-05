Sistema web para gestão de processos administrativos da Secretaria Executiva Regional 2 de Fortaleza/CE.

https://img.shields.io/badge/SER%2520II-Gest%C3%A3o%2520de%2520Processos-0a2540

Sobre o Projeto
O SER II é uma aplicação front-end para cadastro, consulta, edição e exclusão de processos administrativos. Desenvolvido com HTML5, CSS3 e JavaScript puro, oferece uma interface moderna e intuitiva para gerenciamento de documentos processuais.

 Funcionalidades
Cadastro de Processos: Registro completo com número, data, assunto, destino e observações

Listagem Organizada: Visualização em tabela com numeração automática

Busca em Tempo Real: Filtro por número do processo

Edição Completa: Modal dedicado para alteração de dados

Exclusão Segura: Modal de confirmação antes de remover

Persistência Local: Armazenamento no localStorage do navegador

Design Responsivo: Adaptação para diferentes tamanhos de tela

Feedback Visual: Sistema de toast notifications para ações do usuário

 Tecnologias Utilizadas
HTML5: Estrutura semântica da aplicação

CSS3: Estilização avançada com:

Flexbox e Grid Layout

Gradientes e sombras

Animações CSS

Design responsivo

JavaScript (ES6+):

Manipulação do DOM

LocalStorage API

Funções assíncronas

Validações de formulário

Font Awesome 6: Ícones vetoriais

Google Fonts (Inter): Tipografia moderna

 Estrutura do Projeto
text
ser2-gestao-processos/
│
├── index.html          # Arquivo principal da aplicação
├── README.md          # Documentação do projeto
│
└── [Recursos Externos]
    ├── Font Awesome CDN
    ├── Google Fonts CDN
    └── localStorage (armazenamento local)
 Como Executar
Clone o repositório

bash
git clone https://github.com/seu-usuario/ser2-gestao-processos.git
Acesse o diretório

bash
cd ser2-gestao-processos
Abra no navegador

Clique duas vezes no arquivo index.html ou

Utilize uma extensão como Live Server no VS Code

 Como Usar
Cadastrar Processo
Preencha todos os campos obrigatórios no formulário superior

O número do processo deve seguir o formato: P0000/0000

Clique em "Registrar"

Buscar Processos
Utilize o campo de busca para filtrar por número do processo

Clique em "Buscar" ou pressione Enter

Use o botão "Atualizar lista" para limpar o filtro

Editar Processo
Clique no ícone de lápis na linha desejada

Altere os dados no modal aberto

Clique em "Salvar Alterações"

Excluir Processo
Clique no ícone de lixeira na linha desejada

Confirme a exclusão no modal

O processo será permanentemente removido

 Formato dos Campos
Campo	Formato	Obrigatório
Nº Processo	PXXXX/XXXX (ex: P2374/2025)	v
Data	AAAA-MM-DD (seletor de data)	v
Assunto	Texto livre	v
Destino	Texto livre	v
Observação	Texto livre	x
 Design e Interface
Cores Principais
Azul Escuro: #0a2540 (cabeçalho)

Azul Primário: #2b6ef0 (ações)

Vermelho: #b22234 (exclusão)

Branco: #ffffff (fundo)

Cinza Claro: #f8fcff (formulário)

Tipografia
Fonte: Inter (sans-serif)

Pesos: 400, 500, 600, 700

Componentes
Cards com bordas arredondadas (border-radius: 30px)

Sombras suaves para profundidade

Hover effects interativos

Modais com backdrop blur

 Armazenamento
Os dados são persistidos localmente usando a API localStorage do navegador. Isso significa que:

Os processos permanecem salvos mesmo após fechar o navegador

Cada navegador/usuário tem seu próprio conjunto de dados

Não há sincronização entre dispositivos

Dados podem ser perdidos ao limpar o cache do navegador

 Responsividade
A aplicação se adapta a diferentes tamanhos de tela:

>1200px: Layout completo com formulário em 5 colunas

900px-1200px: Formulário em 3 colunas

800px-900px: Formulário em 2 colunas

<800px: Formulário em 1 coluna e toolbar vertical

 Contribuição
Faça um fork do projeto

Crie uma branch para sua feature (git checkout -b feature/AmazingFeature)

Commit suas mudanças (git commit -m 'Add: nova funcionalidade')

Push para a branch (git push origin feature/AmazingFeature)

Abra um Pull Request

 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

 Melhorias Futuras
Implementar ordenação por colunas

Adicionar filtros avançados (por data, destino)

Exportar dados para CSV/PDF

Temas claro/escuro

Histórico de alterações

Backup automático

 Autor
Desenvolvido para a Secretaria Executiva Regional 2 - Fortaleza/CE

SER II · Gestão de Processos - Versão 1.0.0
