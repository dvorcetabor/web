# Web projektu Dvorce Tábor

Pro psaní článků je třeba umět [markdown](https://cs.wikipedia.org/wiki/Markdown).

### Lokální test (pro experty)

V adresaři s repozitářem spustíme příkaz:
`docker run -p 8080:4000 -v $(pwd):/site bretfisher/jekyll-serve`
což spustí server v dockeru, nainstaluje zavislosti
a my si ho můžeme prohlédnout na [localhostu](http://localhost:8080).
