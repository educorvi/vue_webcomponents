# bootstrap_components

## Verwendung
Das package als script im HTML importieren, anschließend können die custom tags verwendet werden.
URL des gesamten Bundles: `https://unpkg.com/@educorvi/bootstrap_components/dist/bundle/dist.umd.min.js`

Zusätzlich muss das CSS von Bootstrap vorhanden sein.

Alternativ einfach `bundle` in der URL durch einen der folgenden Möglichkeiten ersetzen, um nur den entsprechenden Komponenten zu importieren:
- bundle
- accordion


Beispiel:
```html
<!DOCTYPE html>
<html lang="de">
<head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css">
    <title>Titel</title>
</head>
<body>
<hello-world msg="Hello"></hello-world>
<div style="width: 400px; margin: 20px">
    <vue-accordion data='[{"title": "Abschnitt 1", "content": "some html"},{"title": "Teil 2", "content": "some <b>more</b> html"}]'></vue-accordion>
</div>

<script src="https://unpkg.com/@educorvi/bootstrap_components/dist/bundle/dist.umd.min.js"></script>
</body>
</html>
```


Detailiertere Beschreibung der Komponenten folgt noch...