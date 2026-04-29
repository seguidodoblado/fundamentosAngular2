# Fundamentos de Angular 2

Repositorio de práctica del curso de **Angular 2** (Udemy) con ejemplos introductorios en **TypeScript**.

## 📚 Objetivo
Este proyecto reúne ejercicios básicos para entender:
- configuración inicial con TypeScript,
- tipado estricto,
- compilación de archivos `.ts` a `.js`,
- fundamentos previos al desarrollo con Angular.

## 🛠️ Requisitos
Antes de empezar, necesitas tener instalado:

- [Node.js](https://nodejs.org/es/download/)
- npm (incluido con Node.js)
- TypeScript (opcional global, recomendado)

Instalación global recomendada:

```bash
npm install -g typescript
```

## 🚀 Cómo ejecutar el proyecto
1. Clona el repositorio:

```bash
git clone git@github.com:seguidodoblado/fundamentosAngular2.git
cd fundamentosAngular2
```

2. Compila el archivo TypeScript de ejemplo:

```bash
tsc TypeScript/error1.ts
```

3. Abre `TypeScript/index.html` en el navegador para probar el resultado.

## 📁 Estructura básica

```text
TypeScript/
├── error1.ts       # Ejemplo básico con tipado
├── error1.js       # JavaScript generado
├── index.html      # Archivo de prueba
└── tsconfig.json   # Configuración del compilador TypeScript
```

## ⚙️ Configuración TypeScript
Este proyecto incluye `tsconfig.json` con opciones como:
- `target: es5`
- `module: commonjs`
- `strict: true`

## 🎓 Curso de referencia
Curso utilizado:
https://www.udemy.com/angular-2-fernando-herrera/learn/v4/overview

## 📄 Licencia
Este proyecto está bajo la licencia definida en el archivo `LICENSE`.
