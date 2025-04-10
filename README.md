# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

# 🖥️ Criação de Máquinas Virtuais no Microsoft Azure

As **máquinas virtuais (VMs)** no Azure são recursos de **Infraestrutura como Serviço (IaaS)** que permitem executar sistemas operacionais e aplicativos em um ambiente virtualizado na nuvem.

## ✅ Etapas para Criar uma VM no Azure

1. **Acesse o Portal do Azure**  
   Vá para [https://portal.azure.com](https://portal.azure.com)

2. **Crie um novo recurso**  
   Clique em **"Criar um recurso" > "Máquina virtual"**

3. **Preencha as informações básicas**  
   - **Nome da VM**  
   - **Região** (localização do datacenter)  
   - **Imagem** (sistema operacional: Windows, Linux, etc.)  
   - **Tamanho da VM** (CPU, memória)  
   - **Usuário administrador** (senha ou chave SSH)

4. **Configure opções adicionais (opcional)**  
   - **Discos** (tipo e tamanho)  
   - **Rede virtual e IP público**  
   - **Portas de acesso** (ex: abrir porta 80 para web)

5. **Revise e crie**  
   Verifique todas as configurações e clique em **"Criar"**

6. **Provisionamento automático**  
   O Azure cria a máquina virtual em poucos minutos.

## 💡 Benefícios das VMs no Azure

- 🚀 **Implantação rápida**
- 📈 **Escalabilidade**
- 🔁 **Alta disponibilidade**
- 🌐 **Acesso remoto**
- 🔗 **Integração com outros serviços do Azure**

## 🔧 Gerenciamento da VM

Após a criação, você pode:
- Conectar via **RDP** (Windows) ou **SSH** (Linux)
- **Iniciar, parar, reiniciar ou redimensionar** a VM
- **Monitorar o desempenho** com Azure Monitor
- **Configurar backups e segurança**

---

📘 *Esse guia fornece uma visão geral prática para quem está começando a usar máquinas virtuais no Azure.*
