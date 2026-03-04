# 📁 Uploader de Arquivos - ASP.NET Core

API simples para upload de arquivos desenvolvida com ASP.NET Core (.NET 8).

Permite envio de arquivos via endpoint HTTP utilizando Swagger para testes.

---

## 🚀 Tecnologias Utilizadas

- .NET 8
- ASP.NET Core Web API
- Swagger (Swashbuckle)
- Ngrok (para testes externos)
- Git & GitHub

---

## 📌 Funcionalidades

- Upload de arquivos via `POST`
- Armazenamento local em pasta `Uploads`
- Documentação automática com Swagger
- Acesso externo via Ngrok

---

## 🔧 Como Executar o Projeto

### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/SEU_USUARIO/uploader-arquivos.git
```

### 2️⃣ Entrar na pasta

```bash
cd uploader-arquivos
```

### 3️⃣ Restaurar dependências

```bash
dotnet restore
```

### 4️⃣ Rodar a aplicação

```bash
dotnet run
```

A API ficará disponível em:

```
http://localhost:5000/swagger
```

---

## 🌍 Acesso Externo (Opcional)

Para expor a API publicamente durante o desenvolvimento:

```bash
ngrok http 5000
```

Utilize o link HTTPS gerado pelo ngrok.

---

## 📂 Estrutura do Projeto

```
UploaderArquivos/
│
├── Controllers/
│   └── UploadController.cs
│
├── Uploads/
│
├── Program.cs
└── UploaderArquivos.csproj
```

---

## 📄 Licença

Este projeto é para fins de estudo e demonstração.
