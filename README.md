# Aplicativo IMC - GS2

Este projeto utilizando Jetpack Compose! A proposta foi criar um aplicativo de IMC com navegação entre telas, login, cálculo de IMC e exibição de uma lista de integrantes da equipe.
O projeto foi feito com base nas aulas e nos exemplos de navegação do professor, seguindo o padrão dos repositórios utilizados como referência.

---

## Funcionalidades

- Tela de Login com validação de usuário e senha  
- Menu principal com botões para acessar as demais telas  
- Tela de cálculo de IMC com nome, peso, altura e resultado  
- Tela com a lista de integrantes da equipe  
- Navegação implementada com Navigation Compose  
- Botões de voltar em todas as telas internas  

---

## Telas

<img width="302" height="598" alt="image" src="https://github.com/user-attachments/assets/03cedbc4-988c-4e8f-ad9c-49e3650b9e2f" />
<img width="283" height="576" alt="image" src="https://github.com/user-attachments/assets/65be7f98-c89b-4137-bfc9-c82b03782eb3" />
<img width="299" height="588" alt="image" src="https://github.com/user-attachments/assets/73c81a67-6473-4132-9891-e2c6eeb69d45" />
<img width="269" height="572" alt="image" src="https://github.com/user-attachments/assets/0f8b955e-e07e-48fc-9a48-8751bdabc3bd" />
<img width="279" height="577" alt="image" src="https://github.com/user-attachments/assets/7e9db9aa-78fb-4c6a-8812-01371b3c7ccc" />
<img width="285" height="576" alt="image" src="https://github.com/user-attachments/assets/abcbe43e-e90b-4baa-beeb-c3fdd53f00f0" />
<img width="271" height="589" alt="image" src="https://github.com/user-attachments/assets/a735c302-53ab-459b-a23a-8546dd84e876" />
<img width="268" height="579" alt="image" src="https://github.com/user-attachments/assets/89e8a420-dabc-480e-b647-e76325cbdcc3" />
<img width="287" height="577" alt="image" src="https://github.com/user-attachments/assets/dc9fe6c8-cac7-4f74-a3f3-eac8ca3e7434" />


---

### Tela de Login

- Possui dois campos: **usuário** e **senha**
- Somente permite continuar se os valores forem válidos
- Após o login, o usuário é encaminhado para o menu principal

<img width="302" height="598" alt="image" src="https://github.com/user-attachments/assets/03cedbc4-988c-4e8f-ad9c-49e3650b9e2f" />
<img width="283" height="576" alt="image" src="https://github.com/user-attachments/assets/65be7f98-c89b-4137-bfc9-c82b03782eb3" />

---

### 2. Menu Principal

- Exibe três botões:
  - **Calcular IMC**
  - **Equipe**
  - **Sair**

<img width="287" height="576" alt="image" src="https://github.com/user-attachments/assets/c57b0ba8-2de8-4a6e-b134-550b27215436" />

---

### 3. Tela de IMC

- O usuário informa:
  - Seu nome
  - Peso em kg
  - Altura em metros
- O app calcula o IMC e exibe:
  - O valor formatado
  - A classificação (abaixo do peso, normal, sobrepeso ou obesidade)
- Também existe um botão para voltar ao menu

<img width="269" height="572" alt="image" src="https://github.com/user-attachments/assets/0f8b955e-e07e-48fc-9a48-8751bdabc3bd" />
<img width="279" height="577" alt="image" src="https://github.com/user-attachments/assets/7e9db9aa-78fb-4c6a-8812-01371b3c7ccc" />
<img width="285" height="576" alt="image" src="https://github.com/user-attachments/assets/abcbe43e-e90b-4baa-beeb-c3fdd53f00f0" />

---

###  4. Tela de Equipe

- Mostra uma lista simples contendo nomes de integrantes
- A lista é exibida dentro de cartões
- Contém um botão de voltar para retornar ao menu

<img width="268" height="579" alt="image" src="https://github.com/user-attachments/assets/89e8a420-dabc-480e-b647-e76325cbdcc3" />
<img width="271" height="589" alt="image" src="https://github.com/user-attachments/assets/a735c302-53ab-459b-a23a-8546dd84e876" />


