# UC1 — Diagrama de Caso de Uso (Aula Assíncrona)

## 📌 Objetivo da Aula

Compreender o que é um diagrama de caso de uso e como utilizá-lo para representar um sistema de forma visual.

---

# 🧠 O que é um Diagrama de Caso de Uso

Um diagrama de caso de uso é uma forma de representar:

- quem usa o sistema  
- o que pode ser feito dentro dele  

👉 É uma visão simples e visual do sistema.

---

# 🎯 Para que serve

- facilitar o entendimento  
- melhorar a comunicação  
- organizar o sistema  
- transformar texto em visual  

---

# 👤 Ator

Ator é quem interage com o sistema.

Pode ser:

- uma pessoa  
- outro sistema  

### Exemplos

- Cliente  
- Administrador  

---

## 🖼️ Representação do Ator

👉 (Inserir imagem de um boneco representando ator)

---

# ⚙️ Caso de Uso

Caso de uso é uma ação que pode ser realizada no sistema.

👉 Sempre vem de um requisito funcional.

### Exemplos

- Fazer login  
- Comprar produto  
- Cadastrar produto  

---

## 🖼️ Representação do Caso de Uso

👉 (Inserir imagem de um oval com o nome da ação)

---

# 🔐 Permissões (Ligação entre ator e ação)

Nem todo ator pode fazer tudo.

Cada ator tem suas ações específicas.

### Exemplo (Loja Virtual)

Cliente:
- comprar produto  

Administrador:
- cadastrar produto  

👉 Isso representa as permissões do sistema.

---

## 🖼️ Representação da Ligação

👉 (Inserir imagem de linha ligando ator ao caso de uso)

---

# 🔗 <<include>> (Sempre acontece)

Representa uma ação que sempre faz parte de outra.

👉 É obrigatório.

### Exemplo

Finalizar compra  
→ <<include>> Validar pagamento  

👉 Toda compra precisa validar pagamento.

---

## 🖼️ Representação do Include

👉 (Inserir imagem de seta tracejada com <<include>>)

---

# 🔀 <<extend>> (Às vezes acontece)

Representa uma ação opcional.

👉 Pode ou não acontecer.

### Exemplo

Finalizar compra  
← <<extend>> Aplicar cupom  

👉 Nem toda compra usa cupom.

---

## 🖼️ Representação do Extend

👉 (Inserir imagem de seta tracejada com <<extend>>)

---

# ⚠️ Resumo Importante

- Ator → quem usa o sistema  
- Caso de uso → o que é feito  
- Ligação → quem faz o quê  
- <<include>> → sempre acontece  
- <<extend>> → às vezes acontece  

---

# 📝 ATIVIDADE

## 🎯 Objetivo

Criar um diagrama de caso de uso do sistema desenvolvido pelo grupo.

---

## 📌 Instruções

Utilize o sistema que o seu grupo vem desenvolvendo nas aulas anteriores.

---

## O diagrama deve conter:

- pelo menos 2 atores  
- casos de uso bem definidos  
- ligações corretas entre ator e ação  
- pelo menos 1 <<include>>  
- pelo menos 1 <<extend>>  

---

## 💡 Dicas

- use os requisitos funcionais como base  
- pense: “quem faz isso?”  
- pense: “isso sempre acontece ou só às vezes?”  

---

## 📤 Entrega

Enviar o diagrama por e-mail:

📧 prof.lebc@gmail.com

---

## 📅 Prazo

(Definir em aula)

---

## 🧠 Dica Final

O objetivo não é perfeição.

👉 É entender como representar um sistema de forma visual.