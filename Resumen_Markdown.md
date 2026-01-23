# Introducción a Markdown

Markdown es un lenguaje de marcado ligero, fácil de aprender y muy usado para escribir documentación, apuntes, README en proyectos, blogs técnicos y más. Permite crear contenido con formato usando una sintaxis simple y legible.

A continuación, tienes una **guía rápida** con los elementos esenciales de Markdown. Al final, se indican formas de convertir estos archivos `.md` a PDF, HTML y otros formatos.

---

# Sintaxis Markdown

## 1. Encabezados

# Título 1  
## Título 2  
### Título 3  
#### Título 4  
##### Título 5  
###### Título 6

---

## 2. Énfasis (cursiva, negrita, tachado)

*Texto en cursiva*  
_Texto en cursiva_  
**Texto en negrita**  
__Texto en negrita__  
***Negrita y cursiva***  
~~Texto tachado~~

---

## 3. Listas

### Lista con viñetas (no ordenada)

- Elemento 1  
- Elemento 2  
  - Sub-elemento  
* También se puede usar asteriscos

### Lista numerada

1. Elemento 1  
2. Elemento 2  
   1. Sub-elemento

---

## 4. Enlaces e Imágenes

### Enlace

[Texto del enlace](https://ejemplo.com)

### Imagen

![Texto alternativo](https://ejemplo.com/imagen.png)

---

## 5. Código

### Código en línea

Este es un `código en línea`.

### Bloque de código (con lenguaje opcional)

```javascript
// Ejemplo en JavaScript
function saludar() {
  console.log("Hola mundo");
}
```

---

## 6. Citas

> Esto es una cita.  
>> Cita anidada.

---

## 7. Línea horizontal

---

---

## 8. Tablas

| Nombre | Edad | Ciudad     |
|--------|------|------------|
| Ana    | 23   | Madrid     |
| Juan   | 30   | Barcelona  |

---

## Convertir Markdown a PDF, HTML y otros formatos

Puedes usar varias herramientas para convertir archivos `.md` a otros formatos:

### Herramientas en local:

- **Visual Studio Code** + extensión como `Markdown PDF`
  - Abre el `.md`, haz clic derecho → "Exportar como PDF"
- **Pandoc** (muy potente)
  - Convertir a PDF:
    ```
    pandoc archivo.md -o salida.pdf
    ```
  - Convertir a HTML:
    ```
    pandoc archivo.md -o salida.html
    ```

### Herramientas online:

- [Dillinger.io](https://dillinger.io)
- [StackEdit](https://stackedit.io)
- [Markable.in](https://markable.in)
- [Markdown Live Preview](https://markdownlivepreview.com)

---

