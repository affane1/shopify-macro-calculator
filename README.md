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
> La página estará vacía por ahora. Le asignaremos el tema después de crearlo.
    

----------

## Paso 2: Crear El Tema Liquid Personalizado

1.  Copia la integralidad de [este código➡️](https://raw.githubusercontent.com/affane1/shopify-macro-calculator/refs/heads/main/shopify/templates/page.macro-calculator.liquid)
2.  Ve a **"Tienda online" > "Temas" > "Editar código"**.

![](/docs/images/1.png)

3.  Dentro de `/templates`, crea un nuevo archivo: `macro-calculator`.

![](/docs/images/2.png)

4. Pega todo el código que copiamos anteriormente y guarda.
5. Ahora con el segundo código. Copia la integralidad de [este código➡️](https://raw.githubusercontent.com/affane1/shopify-macro-calculator/refs/heads/main/shopify/assets/tailwind.css)
6. Dentro de `/assets` crea un nuevo archivo: `tailwind`.

![](/docs/images/3.png)

> [!IMPORTANT]
> La página estará vacía por ahora. Le asignaremos el tema después de crearlo.
> ![](/docs/images/4.png)

----------
