# Instalação do Active Directory Domain Services (AD DS)

## Objetivo
Transformar o Windows Server em um Controlador de Domínio (Domain Controller) e criar um domínio Active Directory funcional para o laboratório.

## Instalação do AD DS

1. Abra o **Server Manager**
2. Clique em **Add roles and features**
3. Escolha:
   - Role-based or feature-based installation
4. Selecionei o servidor local (SERVIDOR30)
5. Marque:
   - ☑ Active Directory Domain Services
6. Aceite a instalação das features adicionais
7. Finalize a instalação

Após isso, o servidor ainda não é um DC.  

---

## Promoção para Domain Controller

1. No Server Manager, clique no aviso:
   > Promote this server to a domain controller

2. EscolhA:
   - ☑ Add a new forest


