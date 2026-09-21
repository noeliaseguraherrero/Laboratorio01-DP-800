# Certificación DP-800: Diseñar e Implementar Objetos de Base de Datos con SQL

En este repositorio guardo la práctica del laboratorio 1 de la certificación **DP-800**, donde implementamos distintos objetos de base de datos en **SQL Server 2025**.

---

## Resumen de lo realizado

En este ejercicio diseñamos el esquema para una plataforma de e-commerce aplicando las siguientes técnicas:

* **Tablas y Restricciones:** Creación del modelo base con claves primarias, foráneas, reglas de validación (`CHECK`) e índices.
* **Tablas Temporales:** Seguimiento automático del historial de cambios de precios a lo largo del tiempo.
* **Columnas JSON:** Almacenamiento de metadatos con el tipo nativo `JSON` e indexación de propiedades.
* **Particionamiento de Tablas:** División de pedidos por rangos de fechas para optimizar consultas masivas.
* **Secuencias:** Generación de identificadores numéricos automáticos con objetos `SEQUENCE`.
* **Validación:** Comprobación del correcto funcionamiento de las reglas, consultas JSON e historial.

---

## Estructura del Repositorio

```text
├── Laboratorio 01 - Create and maintain database objects.pdf
├── .sql/
│   ├── add-json.sql
│   ├── cleanup.sql
│   ├── create-database.sql
│   ├── ...
└── images/
    └── [Capturas de pantalla del resultado de cada consulta]
```

### Detalle de archivos:

* **`Laboratorio 01 - Create and maintain database objects.pdf`**: Documento completo con las instrucciones del laboratorio y las capturas del paso a paso.
* **`.sql/`**: Carpeta con todos los scripts T-SQL ejecutados de forma ordenada.
* **`images/`**: Capturas de pantalla con la salida de las consultas en SSMS.

---

**Tecnologías utilizadas:** SQL Server 2025, SQL Server Management Studio (SSMS), Git & GitHub.
