README - Sistema de Ferramentas de Desenvolvimento (Versão 2.0)

==================================================

DESCRIÇÃO:
Sistema para gerenciamento de ferramentas utilizadas no desenvolvimento de software, organizado por:
- Linguagens: Python, Java, JavaScript
- Fases: IDE, Controle de Versão, Teste, Documentação

==================================================

FUNCIONALIDADES PRINCIPAIS:

1. CADASTRAR (Create)
   - Adicionar novas ferramentas para cada combinação de linguagem/fase
   - Definir status de uso ("Utiliza" ou "Não Utiliza")

2. LISTAR (Read)
   - Visualizar todas as ferramentas cadastradas
   - Ver matriz completa de status

3. BUSCAR (Read)
   - Consultar ferramenta específica por linguagem e fase

4. ATUALIZAR (Update)
   - Modificar ferramentas e status já cadastrados

5. DELETAR (Delete) [NOVO]
   - Remover ferramentas específicas
   - Confirmação por segurança (S/N)

6. RELATÓRIO FILTRADO
   - Gerar listas por status de uso

==================================================

COMO USAR:

1. Execute o programa: python sistema_ferramentas.py

2. MENU PRINCIPAL:
   0 - Sair
   1 - Cadastrar Ferramentas
   2 - Listar Dados
   3 - Buscar Dados
   4 - Atualizar Dados
   5 - Relatório Filtrado
   6 - Deletar Dados [NOVO]

3. Para DELETAR:
   - Selecione a opção 6
   - Escolha linguagem e fase
   - Confirme com S (Sim) ou N (Não)
   - Dados serão substituídos por "" (vazio) e status "Não Utiliza"

4. Em qualquer momento:
   - Digite 0 para voltar ao menu
   - Validações automáticas evitam erros

==================================================

EXEMPLOS DE ENTRADAS:

Linguagens:
1 - Python
2 - Java
3 - JavaScript

Fases:
1 - IDE (Ex: VSCode, PyCharm, Eclipse, IntelliJ)
2 - Controle de Versão (Ex: Git, SVN, Mercurial)
3 - Teste (Ex: Selenium, JUnit, Cypress, pytest)
4 - Documentação (Ex: Markdown, Sphinx, Javadoc, Docusaurus)

Status:
1 - Utiliza
2 - Não Utiliza

==================================================

OBSERVAÇÕES IMPORTANTES:

- Dados deletados não podem ser recuperados
- Sempre confirme antes de deletar (S/N)
- Digite 0 para cancelar operações
- Programa desenvolvido para Laboratório de Programação I

==================================================

AUTORES:
- Bryan Farias
- Heitor Medrado
- Nathan Betzel

Última atualização: Junho/2025