# Requisitos do Processo

---

## Regras de Negócio

- Somente contas com status **"Aberto"** devem ser validadas
- A **soma dos valores no sistema legado** deve ser **idêntica** ao valor do ACME para aprovação
- Todos os resultados devem ser **registrados no banco de dados** com os campos: "ClientID", "Account", "Resultado"

---

## Validações Necessárias

- Verifique se o **campo Valor** está preenchido corretamente
- Confirme se a **conexão com o banco SQL** está ativa
- Validar acesso ao **sistema legado** antes de iniciar o processo

---

## Saídas Esperadas

- **Planilha consolidada** com os resultados validados por cliente
- **Log de execução detalhado** salvo localmente para rastreabilidade
- **Tabela SQL atualizada** com o status final de cada item para fins de auditoria e monitoramento

---

##  Critérios de Sucesso

-  100% das exceções tratadas automaticamente ou devidamente registradas
-  Tabela SQL refletindo fielmente o resultado da execução
-  E-mail de encerramento enviado com os relatórios anexos
-  Registros disponíveis para consulta técnica e auditoria a qualquer momento

---

