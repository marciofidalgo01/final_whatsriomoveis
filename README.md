<<<<<<< HEAD
# Como Rodar o Projeto

<div>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)



</div>

## Pré-requisitos

- Python
- Node.js
- Git

---

# ✅ BACKEND

## Configurando ambiente virtual

```bash
cd BACKEND
```

```bash
python -m venv venv
```

---

## Ativando o ambiente virtual

### Windows

```bash
venv\Scripts\activate
```

### Linux / MacOS

```bash
source venv/bin/activate
```

---

## Instalando dependências

```bash
pip install -r requirements.txt
```

---

## Aplicando migrações

```bash
python manage.py migrate
```

---

## Iniciando servidor Django

```bash
python manage.py runserver
```

<div >

✅ Backend rodando em:

```bash
http://127.0.0.1:8000/
```

</div>

---

# ✅ FRONTEND

## Inicialização

```bash
cd FRONTEND
```

## Instalando dependências

```bash
npm install
```

---

## Iniciando aplicação React

```bash
npm run dev
```

<div>

✅ Frontend rodando em:

```bash
http://localhost:5173/
```

</div>

---

# Estrutura do Projeto

```bash
Projeto/
│
├── BACKEND/
│   ├── manage.py
│   ├── requirements.txt
│   └── ...
│
└── FRONTEND/
    ├── src/
    ├── package.json
    └── ...
```

---
=======
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
>>>>>>> aeb55bc (first commit (frontend))
