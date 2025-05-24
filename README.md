
# Desafio: Criação de Máquina Virtual no Microsoft Azure 🌐

## 💡 Visão Geral

Este repositório foi criado como parte do desafio prático da DIO, cujo objetivo é aplicar na prática os conceitos aprendidos sobre a criação e gerenciamento de máquinas virtuais na plataforma **Microsoft Azure**. A proposta inclui a documentação detalhada dos passos realizados, além de dicas e boas práticas para futuros projetos na nuvem.

---

## 🎯 Objetivos de Aprendizagem

Ao final deste laboratório, foi possível:

* Criar e configurar uma máquina virtual no Azure.
* Entender os principais componentes e configurações envolvidas.
* Registrar e documentar todo o processo técnico.
* Utilizar o GitHub como ferramenta de versionamento e compartilhamento de conhecimento técnico.

---

## 🛠️ Passo a Passo Realizado

### 1. Acesso ao Portal do Azure

* Criação de conta gratuita no [Portal do Azure](https://portal.azure.com).
* Navegação até a seção de **Máquinas Virtuais (VMs)**.

### 2. Criação da Máquina Virtual

* Escolha da imagem: Windows Server 2022
* Região: Brasil Sul
* Tipo de máquina: B1s (uso básico)
* Nome da VM: `vm-dio-desafio`
* Autenticação via senha
* Abertura da porta RDP (3389) para acesso remoto

### 3. Configurações Adicionais

* Criação de grupo de recursos
* Criação de rede virtual e IP público
* Testes de conexão via Remote Desktop (RDP)

### 4. Gerenciamento da VM

* Acesso ao sistema operacional
* Instalação de ferramentas básicas
* Teste de conectividade

---

## 📝 Anotações e Dicas

* **Evite esquecer de parar a VM** quando não estiver utilizando para evitar cobranças.
* É possível automatizar a criação de VMs com scripts ARM ou Bicep.
* Utilize **tags** para organizar e facilitar a gestão de recursos na conta Azure.
* Atente-se aos limites da conta gratuita (ex: crédito mensal).

---

## 📸 Capturas de Tela

As imagens estão disponíveis na pasta `/images` e incluem:

* Criação da VM
* Configurações de rede
* Acesso via RDP

---

## 📚 Recursos Utilizados

* [Documentação Oficial do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
* [GitHub Docs](https://docs.github.com/)
* [Guia de Markdown](https://www.markdownguide.org/cheat-sheet/)

---

## 🚀 Conclusão

Este desafio foi uma excelente oportunidade para consolidar o aprendizado teórico com a prática no ambiente real da **nuvem Microsoft Azure**. Documentar o processo fortaleceu minha capacidade de registrar soluções técnicas com clareza e compartilhar conhecimento com outros profissionais.

