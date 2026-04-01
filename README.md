# Weather API

The Weather API lets you retrieve current weather conditions 
and multi-day forecasts for any city worldwide.

## Endpoints

| Endpoint      | What it does                                          |
|---------------|-------------------------------------------------------|
| GET /current  | Retrieves current weather conditions for a specified city  |
| GET /forecast | Retrieves a multi-day weather forecast for a specified city |

## Prerequisites

Before you begin, make sure you have:

- **Python 3.8 or higher** — required to run MkDocs
- **MkDocs with Material theme** — install by running:
```
  pip install mkdocs-material
```
- A **GitHub account** — to view or fork this project

## Getting started

1. **Clone the repository**

   Download the project to your computer:
```
   git clone https://github.com/Amruta192/weather-api-docs.git
   cd weather-api-docs
```

2. **Install MkDocs**

   In your terminal, run:
```
   pip install mkdocs-material
```

3. **Run the documentation site locally**
```
   mkdocs serve
```

4. **Open in your browser**

   Go to: http://127.0.0.1:8000/

## View the API spec

The full API specification is written in OpenAPI 3.0 format.
To explore it interactively:

1. Open [Swagger Editor](https://editor.swagger.io/)
2. Copy the contents of `openapi.yaml` from this repository
3. Paste it into the left panel of the editor
4. The interactive API documentation will render on the right

## Documentation site

This project uses MkDocs with the Material theme to turn 
Markdown files into a browsable documentation website. 
To run it locally, open your terminal and run `mkdocs serve`, 
then visit http://127.0.0.1:8000/ in your browser.
