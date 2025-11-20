# Guía para Ejecutar el Proyecto

La interfaz hecha para este proyecto está compuesto por un Backend en FastAPI y un
Frontend en Angular.\
A continuación se describen los pasos necesarios para ejecutar ambos
componentes.

------------------------------------------------------------------------

## 🚀 Backend (FastAPI)

### 1. Crear y activar un entorno virtual (solo la primera vez)

En la carpeta del backend, crea el entorno virtual y actívalo:

``` bash
cd backend
python -m venv venv
source venv/bin/activate     # En Windows: venv\Scripts\activate
```

### 2. Instalar dependencias (solo la primera vez)

``` bash
pip install fastapi uvicorn[standard] joblib pandas scikit-learn xgboost
```

### 3. Ejecutar el servidor Backend

``` bash
uvicorn app:app --reload --port 8001
```

------------------------------------------------------------------------

## 🌐 Frontend (Angular)

### 1. Instalar dependencias (solo la primera vez)

``` bash
npm install
```

### 2. Ejecutar el servidor Frontend

``` bash
ng serve
```

El frontend quedará disponible normalmente en:\
👉 **http://localhost:4200**
