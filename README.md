# Guía de Implementación: Calculadora de Macronutrientes para Shopify

Esta guía está diseñada para ayudarte a implementar y mantener una calculadora de macronutrientes en tu tienda Shopify. El proyecto está pensado para integrarse fácilmente dentro de una temática ya existente y adaptarse a cambios futuros.

----------

## 🔄 Estructura del Proyecto

Esta extensión de tema está compuesta por 2 archivos: **page.macro-calculator.liquid** y **tailwind.css**. Aquí es donde se encuentran:
```
shopify/
├── templates/
│   └── page.macro-calculator.liquid
└── assets/
    └── tailwind.css
```

----------

## Paso 1: Crear una Página en Shopify

1.  Entra al panel de Shopify.
    
2.  Ve a **"Tienda online" > "Páginas"**.
    
3.  Crea una nueva página con el nombre deseado. Verifica que la opción **'Visible'** esté seleccionada.
    
> [!NOTE]
> La página estará vacía por ahora. Le asignaremos el tema después de crearla.
    

----------

## Paso 2: Crear Plantilla Liquid Personalizada

1.  Ve a **"Tienda online" > "Plantillas" > "Editar código"**.

![](/docs/images/2.png)
    
2.  Dentro de `/templates`, crea un nuevo archivo: `page.macro-calculator.liquid`.

![](/docs/images/2.png)
    
3.  Copia y pega el siguiente código base:
