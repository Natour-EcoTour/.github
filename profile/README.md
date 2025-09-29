# Natour EcoTour

<div align="center">
  
 <img src="https://media.discordapp.net/attachments/1412422804158156931/1422277203181174876/fullNatourLogo.png?ex=68dc165d&is=68dac4dd&hm=7a541fa9dd43918531ef7176f2391765b4a4b1cc29fe59f97a4c8254f14547d7&=&format=webp&quality=lossless&width=815&height=815" alt="Natour Logo" width="200"/>
  
  ### Plataforma de Ecoturismo e Descoberta de Pontos Naturais
  
  ![Status](https://img.shields.io/badge/status-active-success.svg)
  ![Python](https://img.shields.io/badge/Python-3.13.7-3776AB?logo=python&logoColor=white)
  ![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
  ![React Native](https://img.shields.io/badge/React_Native-20232A?logo=react&logoColor=61DAFB)
  ![Expo](https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=white)
  ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white)
  ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
  ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white)
  ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
  
</div>

---

## Sobre o Projeto

O Natour EcoTour é uma plataforma completa de ecoturismo que conecta pessoas a pontos naturais, permitindo a descoberta, compartilhamento e avaliação de locais de interesse ecológico. O projeto é composto por três aplicações principais:

- Backend API (Django REST Framework)
- Aplicativo Mobile (React Native + Expo)
- Painel Administrativo Web (Next.js)

---

## Arquitetura do Sistema

```
natour-ecotour/
├── back/          # API Django REST Framework
├── app/           # App React Native + Expo
└── front/        # Painel administrativo/Landing Page Next.js
```

---

## Tecnologias Utilizadas

### Backend

- **Django** & **Django REST Framework**
- **Python 3.13.7**
- **PostgreSQL** (banco de dados)
- **Docker** (containerização)
- **Prometheus, Loki, Tempo** (monitoramento e logs)

### Mobile

- **React Native**
- **Expo** & **Expo Router**
- **TypeScript**
- **Axios** (comunicação HTTP)
- **Yup** (validação de formulários)

### Web Admin

- **Next.js**
- **React**
- **TypeScript**
- **Tailwind CSS** (estilização)

---

## Repositórios

| Repositório                                      | Descrição                         | Tecnologia          |
| ------------------------------------------------ | --------------------------------- | ------------------- |
| [back](https://github.com/Natour-EcoTour/back)   | API REST e lógica de negócios     | Django + Python     |
| [app](https://github.com/Natour-EcoTour/app)     | Aplicativo mobile multiplataforma | React Native + Expo |
| [front](https://github.com/Natour-EcoTour/front) | Painel de administração           | Next.js             |

---

## Instalação e Execução

### Backend (Django)

```bash
# Clone o repositório
git clone [url-do-repositorio-backend]
cd backend

# Instale as dependências
pip install -r requirements.txt

# Execute as migrações
python manage.py migrate

# Inicie o servidor
python manage.py runserver

# (Opcional) Inicie os serviços Docker
docker-compose up
```

### Mobile (React Native + Expo)

```bash
# Clone o repositório
git clone [url-do-repositorio-mobile]
cd mobile

# Instale as dependências
npm install

# Inicie o Expo
npx expo start

# Para Android
npx expo start --android

# Para iOS
npx expo start --ios
```

### Web Admin (Next.js)

```bash
# Clone o repositório
git clone [url-do-repositorio-web]
cd web-admin

# Instale as dependências
npm install

# Inicie em modo desenvolvimento
npm run dev

# Acesse http://localhost:3000
```

---

## Funcionalidades Principais

### Para Usuários

- Descoberta de pontos naturais no mapa
- Upload e compartilhamento de fotos
- Avaliação e reviews de pontos
- Busca avançada de locais
- Gerenciamento de perfil
- Visualização detalhada de pontos turísticos

### Para Administradores

- Gerenciamento de usuários
- Dashboard de estatísticas
- Moderação de conteúdo
- Gerenciamento de pontos turísticos
- Análise de reviews e avaliações
- Configurações do sistema

---

## Estrutura dos Projetos

### Backend

```
natour/
├── api/
│   ├── methods/        # Funções auxiliares
│   ├── migrations/     # Migrações do banco
│   ├── schemas/        # Validação de dados
│   ├── serializers/    # Serializadores API
│   ├── utils/          # Utilitários
│   └── views/          # Endpoints da API
├── settings.py
└── urls.py
```

### Mobile

```
src/
├── app/                # Rotas (Expo Router)
├── components/         # Componentes reutilizáveis
├── services/          # Integração com API
├── utils/             # Funções auxiliares
└── validations/       # Schemas de validação
```

### Web Admin

```
src/
├── app/               # Páginas e rotas (Next.js)
├── components/        # Componentes UI
├── services/         # APIs e serviços
├── hooks/            # Hooks customizados
└── utils/            # Funções utilitárias
```

---
