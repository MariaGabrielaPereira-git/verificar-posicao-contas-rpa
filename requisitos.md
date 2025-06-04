# Requisitos do Processo

## 🎯 Regras de Negócio

- Apenas contas com status “Open” devem ser validadas
- A soma dos valores no sistema legado deve ser idêntica ao valor do ACME para aprovação
- Todos os resultados devem ser registrados em banco (ClientID, Account, Resultado)

## 🛑 Validações Necessárias

- Verificar se o campo Amount está preenchido
- Confirmar que a conexão com o banco SQL está ativa
- Validar acesso ao sistema legado antes de iniciar

## 📤 Saídas Esperadas

- Planilha consolidada dos resultados
- Log de execução salvo localmente
- Tabela atualizada no banco com status final
