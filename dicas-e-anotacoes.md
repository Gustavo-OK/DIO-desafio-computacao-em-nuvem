# Dicas Práticas e Anotações – Criação de Máquina Virtual no Azure

---

## 🪜 Etapas para Criar a VM

1. Acesse o [Portal do Azure](https://portal.azure.com)
2. Vá em **"Máquinas Virtuais" > "Criar"**
3. Preencha os dados:
   - **Nome:** desafio-vm
   - **Região:** Brasil Sul
   - **Imagem:** Ubuntu 20.04 LTS ou Windows Server
   - **Tamanho:** B1s (opção gratuita)
   - **Autenticação:** Usuário/senha

---

## Acesso à VM

- **Ubuntu:** Acesso via SSH usando o IP público fornecido.
- **Windows:** Acesso via RDP (Remote Desktop).

---

## Dicas Importantes

- **Custo:** Lembre-se de parar ou excluir a VM após o uso para evitar cobranças.
- **Segurança:** Configure as portas corretamente (ex: 22 para SSH, 3389 para RDP).
- **Organização:** Use tags para identificar os recursos do seu projeto.
- **Regiões:** Escolher regiões próximas reduz latência e melhora performance.

---

## Observações Finais

- A interface do Azure é intuitiva, mas há muitas opções – explore com calma.
- O Azure oferece monitoramento e logs úteis para entender o comportamento da VM.
