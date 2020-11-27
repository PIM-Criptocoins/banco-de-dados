## Linguagem Sql: ### Introdução: • A **linguagem de consulta estruturada(SQL)** surgiu em meados da decada de 70 sendo seu principal foco ser uma linguagem que adapta-se ao modelo relacional. Seu sucesso foi tão grande que a ANSI (American National Standarts Institute), padronizou as implementações da linguagem, hoje a maior parte de BD&#39;s seguem criteriosamente esta padronização, podendo ter algumas variações. ###

## Podemos colocar restrições para limitar o tipo de dados a introduzir. Essas tais restrições podem ser declaradas quando fizermos a instrução CREATE TABLE ou ALTER TABLE que são comandos DDL que cria e altera uma tabela. Alguns tipos comuns de restrições(CONSTRAINT) incluem o seguinte:
**- Not null**
**- Default**
**- Unique**
**- Check**
**- Primary Key**
**- Foreign Key ** ##

**Procedimento**

1. Efetue login no computador no qual você deseja restaurar o banco de dados.
2. Abra o Microsoft SQL Server Management Studio.
3. Na barra de navegação esquerda, clique com o botão direito em  **Bancos de Dados**  e em  **Restaurar Banco de Dados**.

1. Na seção Origem, selecione  **Dispositivo**  e clique no botão com três pontos.

1. Na janela pop-up que é aberta, clique em  **Incluir**  e procure o arquivo de backup. Clique em  **OK**.
2. No menu de navegação esquerdo, clique em Opções.
3. Na área de janela à direita, selecione **Sobrescrever o banco de dados existente (COM SUBSTITUIR)** e em  **Fechar conexões existentes com o banco de dados de destino**.
4. Clique em  **OK**.