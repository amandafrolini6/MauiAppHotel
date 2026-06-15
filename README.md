# 🏨 MauiAppHotel
 
Aplicativo mobile de gerenciamento de hospedagem desenvolvido com **.NET MAUI**, como projeto acadêmico da disciplina de Desenvolvimento Mobile — Fatec Jahu.
 
---
 
## 📋 Sobre o Projeto
 
O **MauiAppHotel** simula o processo de contratação de hospedagem em um hotel. O usuário pode se cadastrar, fazer login, selecionar uma suíte, informar as datas e a quantidade de hóspedes, e visualizar o valor total da estadia antes de confirmar.

---

## 🧩 Conceitos Utilizados

### **BindingContext**
Utilizado para:
- Vincular dados do ViewModel à interface  
- Atualizar automaticamente campos da tela quando valores mudam  
- Passar informações de uma página para outra sem acoplamento

### **MVVM**
Estrutura aplicada para organizar:
- **Model**: dados do hóspede e da reserva  
- **View**: telas XAML  
- **ViewModel**: lógica, propriedades e comandos

---

## 📂 Estrutura do Projeto

```
MauiAppHotel/
│
├── Models/
│   ├── Usuario.cs            → Representa o usuário (nome, e-mail, senha)
│   ├── Quarto.cs             → Representa um tipo de suíte (descrição e valores)
│   └── Hospedagem.cs         → Junta quarto + datas + hóspedes e calcula o valor total
│
├── Views/
│   ├── Login.xaml / .cs      → Tela de login
│   ├── Cadastro.xaml / .cs   → Tela de cadastro
│   ├── ContratacaoHospedagem.xaml / .cs  → Tela principal de seleção da hospedagem
│   └── HospedagemContratada.xaml / .cs   → Tela de resumo com o valor calculado
│
├── App.xaml.cs               → Configurações globais do app (lista de usuários em memória)
├── AppShell.xaml             → Define a navegação entre telas
└── MauiProgram.cs            → Ponto de entrada do aplicativo
```

---

## 🛠️ Tecnologias Utilizadas
 
| Tecnologia         | Finalidade                                      |
|--------------------|-------------------------------------------------|
| .NET MAUI          | Framework para desenvolvimento multiplataforma  |
| C#                 | Linguagem de programação                        |
| XAML               | Linguagem para construção das interfaces visuais|
| SecureStorage      | Armazenamento seguro da sessão do usuário       |
| LINQ               | Consulta e verificação de dados em listas       |
| Data Binding       | Ligação entre dados do modelo e a interface     |

 
---
 
## 👩‍💻 Autora
 
**Amanda Frolini**  
Estudante de Desenvolvimento de Software Multiplataforma — Fatec Jahu  
