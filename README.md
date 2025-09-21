# 🖥️ Resumo do Lab: Ferramentas de Implantação na Azure
Este repositório reúne os principais aprendizados adquiridos durante o curso **Ferramentas de Gerenciamento e Implantação na Azure** da plataforma [DIO.me](https://web.dio.me), Arquitetura e Serviços Azure - Módulo 3. 
O foco está nos benefícios e aplicações práticas da plataforma Microsoft Azure, explorando seus recursos e funcionalidades.
O Bootcamp oferece uma base sólida em tecnologias de nuvem, abordando desde os conceitos fundamentais até os componentes essenciais da arquitetura Azure.
Entre os temas estudados estão: criação e gerenciamento de máquinas virtuais, configuração de bancos de dados e soluções de armazenamento, além de tópicos avançados como arquitetura em nuvem, governança, monitoramento e segurança de ambientes cloud. 

---

## 📘 Tópicos Abordados
Este repositório apresenta um resumo sobre como gerenciar os recursos na nuvem - pode parecer bem complexo! Mas o Azure oferece um conjunto robusto de ferramentas e conceitos para simplificar esse processo.
Exploraremos as principais abordagens para interagir com o Azure, desde as interfaces visuais até a automação poderosa da Infraestrutura como Código (IaC), o Portal do Azure, o Azure CLI e o Azure PowerShell, o Azure Resource Manager (ARM) 
e por fim, os modelos ARM e o Bicep para voce ter uma ideia e se aprofundar no assunto acessando os links ao final.

---

# 🛠️ Ferramentas de Interação com o Azure

Gerenciar e implantar recursos no Azure pode ser feito de várias maneiras, cada uma com seus próprios pontos fortes.

## 🌐 Portal do Azure
- Interface gráfica (GUI) baseada na web.  
- Ideal para iniciantes e para gerenciar recursos visualmente.  
- É a forma mais fácil e visual de gerenciar recursos, ideal para quem está começando, para tarefas pontuais ou para visualizar o estado da sua infraestrutura.

## 💻 Azure CLI (Command-Line Interface)
- Ferramenta de linha de comando multiplataforma.  
- Oferece uma experiência de script consistente para a criação e gerenciamento de recursos.  
- Popular entre desenvolvedores e administradores que preferem agilidade e automação via scripts de shell.

## ⚙️ Azure PowerShell
- Conjunto de comandos (cmdlets) para o PowerShell.  
- Permite automatizar a criação, configuração e gerenciamento de recursos do Azure.  
- Amplamente utilizado por administradores de sistema e engenheiros de DevOps que já trabalham com PowerShell.

---

## 🧠 Domínio de Objetivo: O Cérebro do Azure

### 🔧 Azure Resource Manager (ARM)
Camada de gerenciamento e controle do Azure.  
Permite atualizar, criar e excluir recursos na assinatura do Azure.  
Pense nele como o cérebro que processa todas as solicitações (Portal, PowerShell, CLI, etc).  
Recursos oferecidos:
- Controle de acesso baseado em função (RBAC)
- Bloqueios de recursos
- Tags para organização
- Direcionamento seguro e organizado da criação e alteração de recursos
<img width="450" height="350" alt="imagem13" src="https://github.com/user-attachments/assets/67707cd0-e767-48a8-a1c4-9f51f080fd3e" />

### 🌍 Azure Arc
Solução que estende o gerenciamento do Azure para ambientes multinuvem e híbridos.  
Permite gerenciar:
- Servidores
- Clusters Kubernetes
- Serviços de dados fora do Azure  
Usa as mesmas ferramentas e políticas dos recursos nativos do Azure.
<img width="450" height="350" alt="imagem12" src="https://github.com/user-attachments/assets/8355b2aa-117d-4967-8399-e7588b9f2b32" />

---

## 🧾 Infraestrutura como Código (IaC)

Prática de gerenciar e provisionar infraestrutura de TI por meio de arquivos de código.  
Benefícios:
- Consistência
- Repetibilidade
- Rastreamento de versões

Ferramentas principais no Azure:
- **Modelos ARM**
- **Bicep**

### 📄 Modelos ARM (JSON Templates)
Arquivos JSON que definem a infraestrutura a ser implantada.  
Declaram recursos e configurações.  
Permitem implantar ambientes inteiros de forma consistente.  
Desvantagem: código pode ser complexo e extenso.

### 🪙 Bicep
Linguagem nativa de domínio específico (DSL) para ARM.  
Sintaxe mais limpa e legível.  
Compila para JSON do ARM.  
Facilita escrita e manutenção.  
Compatível apenas com a nuvem da Microsoft.

<img width="450" height="350" alt="imagem15" src="https://github.com/user-attachments/assets/fb99eabe-1aa0-4fa5-8bde-df61634ee816" />

---

## 📦 Características dos Modelos ARM
- Sintaxe declarativa  
- Resultados repetíveis  
- Orquestração  
- Arquivos modulares  
- Validação integrada  
- Código exportável  

---

## ✅ Conclusão

O Azure oferece diversas ferramentas para gerenciamento e implantação de recursos, adaptadas a diferentes perfis e necessidades. Desde interfaces gráficas amigáveis até linguagens declarativas poderosas como Bicep, o ecossistema do Azure permite automação, controle e escalabilidade com segurança e eficiência.  
Dominar essas ferramentas é essencial para qualquer profissional que deseje atuar com nuvem de forma estratégica e moderna.
> Este conteúdo faz parte do projeto **Ferramentas de Implantação na Azure - Laboratório** da plataforma DIO.me.

---
 
### 📚 Recursos Complementares
- [Tutorial oficial para criar e gerenciar VMs Windows](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/tutorial-manage-vm)
- [Portal Microsoft Azure](https://portal.azure.com/#allservices)
- [Calculadora de Preços Azure](https://azure.microsoft.com/pt-br/pricing/calculator/)
- [Visão Geral do Azure Arc](https://learn.microsoft.com/pt-br/azure/azure-arc/overview)
- [Preços do Azure Arc](https://azure.microsoft.com/pt-br/pricing/details/azure-arc/core-control-plane/)
- [Azure Arc](https://azure.microsoft.com/pt-br/products/azure-arc/?msockid=24a39583fb0a6a871e0683edfaf16bb2)
- [Bicep Playground - Comparativo de Códigos](https://azure.github.io/bicep/)

  
📎 Link do curso: [Microsoft Azure AZ-900 - DIO.me](https://web.dio.me/track/microsoft-azure-az-900)

🖼️ Imagens: Fonte Dio.me
