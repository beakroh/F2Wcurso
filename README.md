# WebGIS Leaflet - 3 Mapas de Fundo

Este é um exemplo simples de WebGIS usando **Leaflet** com **3 mapas de fundo (basemaps)**:

- OpenStreetMap
- OpenTopoMap
- CartoDB Positron

## Como usar

1. Certifique-se de estar na pasta `Webgis1`.
2. Abra o arquivo `index.html` diretamente no navegador (clique duas vezes no arquivo ou use "Abrir com" no navegador).
   - Em alguns navegadores pode ser necessário servir o arquivo via um pequeno servidor HTTP.

### Servindo com um servidor simples (opcional)

Se você tiver o Python instalado:

```bash
cd c:\Cursos\w2f\Webgis1
python -m http.server 8000
```

Depois, abra no navegador:

`http://localhost:8000/index.html`

## Funcionalidades

- Mapa inicial centralizado aproximadamente no Brasil.
- Controle de camadas no canto superior direito permitindo alternar entre os 3 basemaps.
- Todos os basemaps usam provedores públicos (OpenStreetMap, OpenTopoMap e CartoDB) com as devidas atribuições.

