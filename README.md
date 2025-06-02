# chanlenge-virtual-machine-azure
Chalange bootcamp cloud and IA - XP Investimentos

# Azure Virtual Machines - Guia Rápido

Este guia apresenta os principais conceitos sobre Máquinas Virtuais (VMs) no Microsoft Azure e mostra como criar uma VM gratuita utilizando o crédito de avaliação para novas contas.

## 🧠 5 Principais Pontos sobre Azure Virtual Machines

1. **Escalabilidade e Flexibilidade**
   - Você pode escalar vertical ou horizontalmente de acordo com suas necessidades.
   - Suporte para diferentes sistemas operacionais: Windows, Linux e distribuições customizadas.

2. **Preços e Modelos de Cobrança**
   - Baseado no uso (pay-as-you-go), reservas de longo prazo (1 ou 3 anos), e Spot VMs.
   - Há uma camada gratuita para novas contas e créditos iniciais de R$ 1.000 (USD 200).

3. **Alta Disponibilidade**
   - Suporte a zonas de disponibilidade, conjuntos de disponibilidade e balanceadores de carga.

4. **Segurança Integrada**
   - Integração com Azure Defender, criptografia de disco, autenticação via SSH/AD e regras de firewall via NSG.

5. **Gerenciamento e Monitoramento**
   - Uso do Azure Monitor, Log Analytics e Azure Automation para gerenciar e automatizar tarefas.

---

## 🚀 Como Criar uma VM Gratuita na Azure (Nova Conta)

### Pré-requisitos:
- Conta Microsoft (Outlook, Hotmail, etc.).
- Cartão de crédito (não será cobrado durante o teste gratuito).

### Passo a Passo:

1. **Crie uma conta gratuita**
   - Acesse: [https://azure.microsoft.com/pt-br/free](https://azure.microsoft.com/pt-br/free)
   - Complete o cadastro para receber **R$ 1.000 (USD 200)** em créditos por 30 dias.

2. **Acesse o Portal do Azure**
   - Vá para [https://portal.azure.com](https://portal.azure.com)

3. **Crie a VM**
   - No portal, clique em “Criar um recurso” > “Máquina virtual”.
   - Selecione:
     - **Imagem**: Ubuntu Server 22.04 LTS (gratuito elegível)
     - **Tamanho**: B1s (elegível para camada gratuita)
     - **Usuário/SSH**: Crie credenciais de login.
     - **Região**: Escolha uma que suporte o tamanho gratuito (ex: Leste dos EUA).

4. **Configure a Rede**
   - Mantenha a rede padrão com IP público e porta 22 aberta para acesso SSH.

5. **Revise e Crie**
   - Verifique os detalhes e clique em “Criar”.
   - Aguarde o provisionamento e conecte-se via SSH.

---

## 📎 Observações

- O tamanho **B1s** e a imagem **Ubuntu Server** são elegíveis à camada gratuita.
- Após os créditos expirarem, você será notificado para optar por continuar com cobrança ou encerrar o uso.

---

## 📚 Links Úteis

- [Documentação Oficial - Azure VMs](https://learn.microsoft.com/pt-br/azure/virtual-machines/)
- [Preços da Azure VM](https://azure.microsoft.com/pt-br/pricing/details/virtual-machines/)
- [Guia de Boas Práticas](https://learn.microsoft.com/pt-br/azure/cloud-adoption-framework/)


