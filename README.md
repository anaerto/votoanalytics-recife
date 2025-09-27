# 📊 VotoAnalytics Recife

**VotoAnalytics Recife** é um aplicativo web para análise de dados eleitorais, focado inicialmente nas eleições municipais de 2024 em Recife-PE.
O objetivo é oferecer consultas granulares de votos (zona, bairro, local de votação e seção) com visualizações intuitivas e relatórios avançados.

---

## 🚀 Objetivo do Projeto

* Fornecer uma plataforma acessível para políticos, coordenadores de campanha e dirigentes partidários.
* Permitir análise comparativa entre candidatos.
* Garantir usabilidade simples e visualizações claras.

---

## 🛠️ Stack Tecnológica (MVP Enxuto)

* **Frontend:** React + Vercel + TailwindCSS + Recharts/Chart.js
* **Backend:** FastAPI (Python) ou Express.js (Node.js) em Render Free
* **Banco de Dados & Auth:** Supabase (PostgreSQL + autenticação integrada)
* **ETL:** Scripts Python (pandas), executados manualmente para importar dados do TSE
* **CI/CD:** GitHub Actions (deploy automático)

---

## 📂 Estrutura de Pastas

```
votoanalytics-recife/
├── frontend/   # React + Tailwind + Vercel
├── backend/    # FastAPI ou Express.js
├── etl/        # scripts Python para importar CSV do TSE
├── docs/       # anotações, schemas, relatórios técnicos
└── README.md
```

---

## 🔧 Instalação (para desenvolvimento local)

### Clonar o repositório

```bash
git clone https://github.com/seu-usuario/votoanalytics-recife.git
cd votoanalytics-recife
```

### Frontend (React)

```bash
cd frontend
npm install
npm run dev
```

### Backend (FastAPI exemplo)

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

---

## 📊 Fonte de Dados

* Dados abertos do **TSE** (Tribunal Superior Eleitoral).
* Dataset: [Resultados Eleitorais 2024](https://dadosabertos.tse.jus.br/dataset/resultados-2024)

---

## ✅ Roadmap MVP

* [ ] Configuração inicial do repositório e arquitetura
* [ ] Banco de dados no Supabase
* [ ] Backend com APIs básicas de consulta
* [ ] Frontend com busca de candidatos e visualização de votos
* [ ] ETL para importar dados do TSE
* [ ] Deploy em nuvem (Vercel + Render + Supabase)

---

## 👨‍💻 Autor

Projeto desenvolvido por ANAERTO LUNA, como iniciativa independente para análise política em Recife.

