# Etapas do Processo: Verificar Posição de Contas

1. Acessar o sistema “ACME System 1”
2. Preencher os campos “Email” e “Password” e clicar em Login
3. Filtrar itens na fila com Type='WI1', Status='Open' e Description='Verify Account Position'
4. Clicar na lupa para capturar Client ID e WIID
5. Abrir sistema legado e realizar login
6. Pesquisar o Client ID
7. Identificar e capturar o Account Number
8. Somar todos os valores da coluna 'Amount'
9. Comparar com o valor no campo ‘Account Amount’ no ACME System
10. Atualizar status: 
   - 'Completed' se os valores coincidirem
   - 'Rejected' se forem diferentes
11. Salvar o resultado na base SQL
12. Preencher comentário e confirmar a validação no ACME System
