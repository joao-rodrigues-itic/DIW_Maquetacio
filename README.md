# 🍽️ DIW_Maquetacio

Repositori per a l'activitat de maquetació de l'assignatura de **Disseny d'Interfícies Web (DIW)**.

El projecte consisteix en la pàgina web d'un restaurant fictici, **Restaurant Els Coberts**, maquetada amb HTML5 i CSS3 sense cap llibreria ni framework.

![Captura de la pàgina principal](img/portada.jpg)

## 🎯 Objectius

- Reconèixer les possibilitats de modificar les etiquetes HTML.
- Definir i associar estils globals a fulls externs.
- Redefinir estils.
- Identificar les diferents propietats de cada element.
- Crear classes d'estils.
- Utilitzar eines de validació de fulls d'estils.

## 📄 Contingut de la pàgina

La pàgina principal (`index.html`) s'organitza en les seccions següents:

| Secció | Descripció |
| --- | --- |
| **Menú de navegació** | Enllaços interns a Nosaltres, Carta i Galeria. |
| **Capçalera** | Imatge de portada amb el nom i el lema del restaurant. |
| **Sobre nosaltres** | Bloc alternat d'imatges i text. |
| **Carta** | Quadrícula amb els menús, descripcions i imatges dels plats. |
| **Galeria d'imatges** | Mostrari de vuit plats. |
| **Reserva** | Formulari amb nom, nombre de persones, data, hora i descripció. |
| **Footer** | Correu, telèfon i logotip. |

## 📁 Estructura del projecte

```text
DIW_Maquetacio/
├── .vscode/                    # Configuració de l'editor
├── img/                        # Imatges (portada, carta, galeria, favicon...)
├── style/
│   ├── styleHeaderFooter.css   # Estils compartits: menú i footer
│   └── index.css               # Estils de la pàgina principal
├── index.html                  # Pàgina principal
└── README.md
```

## 🛠️ Tecnologies

- **HTML5**: estructura semàntica (`header`, `nav`, `footer`, `label`...).
- **CSS3**: fulls d'estils externs, classes pròpies i maquetació de seccions.
- **[Material Symbols](https://fonts.google.com/icons)**: icones del footer, carregades des de Google Fonts.

## 🚀 Com executar-lo

1. Clona el repositori:
```bash
   git clone https://github.com/joao-rodrigues-itic/DIW_Maquetacio.git
```
2. Entra a la carpeta:
```bash
   cd DIW_Maquetacio
```
3. Obre `index.html` al navegador, o utilitza l'extensió **Live Server** de VS Code.

> Les icones del footer necessiten connexió a Internet per carregar-se.

## ✅ Validació

Els fitxers s'han validat amb les eines oficials del W3C:

- [W3C Markup Validation Service](https://validator.w3.org/) per a l'HTML.
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) per al CSS.

## 👤 Autor

**João Rodrigues**: [@joao-rodrigues-itic](https://github.com/joao-rodrigues-itic)(https://github.com/joaorodskt)

Activitat realitzada per a l'assignatura de Disseny d'Interfícies Web.