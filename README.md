# 🎉 Aplicativo Cadastro de Eventos (.NET MAUI)

![.NET 8](https://img.shields.io/badge/.NET-8.0-blueviolet)
![MAUI](https://img.shields.io/badge/Mobile-MAUI-ff69b4)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen) 
![License](https://img.shields.io/badge/Licença-MIT-blue)

**Repositório do aplicativo de cadastro de eventos** desenvolvido para o projeto *Sistema de Gerenciamento de Eventos* da disciplina *Desenvolvimento de Sistemas II*.

Aplicativo para cadastro e visualização de eventos, com preenchimento de informações como nome, descrição, data de início e término.

✔ **Interface intuitiva com design responsivo**

✔ **Cadastro de eventos com validação de datas**

✔ **Navegação entre telas: cadastro e resumo**

✔ **Tema claro/escuro com estilos personalizados**

---

## 📝 Descrição do Projeto

Sistema de cadastro de eventos com as seguintes funcionalidades:

* **Preenchimento de informações do evento** (nome, descrição, datas)
* **Validação automática de datas** (início e término)
* **Visualização do resumo do evento**

---

## ✨ Recursos Implementados

✅ **Entrada de dados com Entry, Editor e DatePicker**

✅ **Validação básica e navegação entre páginas**

✅ **Layout responsivo para dispositivos móveis e desktop**

✅ **Tema escuro e claro com cores definidas em ResourceDictionary**

✅ **Navegação com NavigationPage**

---

## 🛠 Tecnologias Utilizadas

* **Front-end**: XAML (MAUI)
* **Back-end**: C# (lógica de navegação e manipulação de eventos)
* **Plataforma**: .NET MAUI (Multi-platform App UI)

---

## 📂 Estrutura do Projeto

```
CadastroEventos/  
├── Pages/  
│   ├── HomePage.xaml          # Tela inicial de cadastro do evento  
│   ├── ResumoPage.xaml        # Tela de resumo do evento cadastrado  
│   |
├── Models/  
│   ├── Evento.cs              # Modelo de dados do evento  
├── Resources/  
│   ├── Styles/  
│   │   ├── Colors.xaml        # Paleta de cores do tema  
│   │   └── Styles.xaml        # Estilos globais  
├── App.xaml                   # Configurações de recursos da aplicação  
└── README.md                  # Esta documentação  
```

---

## 🚀 Como Executar

1. **Pré-requisitos**:

   * .NET 8.0 SDK instalado
   * Visual Studio 2022 ou superior (com suporte ao MAUI)

2. **Clone o repositório**:

   ```bash
   git clone https://github.com/seuusuario/CadastroEventos.git  
   ```

3. **Execute o projeto**:

   ```bash
   dotnet build  
   dotnet run --project CadastroEventos  
   ```

4. **Teste no emulador Android, iOS ou Windows**

---

## 📌 Informações Acadêmicas

| Item           | Detalhe                                 |
| -------------- | --------------------------------------- |
| **Disciplina** | Desenvolvimento de Sistemas II          |
| **Curso**      | Técnico em Desenvolvimento de Sistemas  |
| **Objetivo**   | Sistema de cadastro e resumo de eventos |

---

> ✨ **Dica**: personalize os estilos e cores no arquivo `Styles.xaml` para adequar ao branding do evento ou da instituição!
