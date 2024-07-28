# App Templates

This repository hosts the official templates (**'Apps Templates'**) definitions for Portainer.

For more information about the template definition format and how to deploy your own templates, see the [relevant documentation section](https://documentation.portainer.io/v2.0/templates/deploy_stack/).


I highly recommend using [Lissy93's templates](https://github.com/Lissy93/portainer-templates).
But if you want to use this repo's templates, you'll want to reference the following URL in the Portainer template settings:
```
https://raw.githubusercontent.com/shmolf/portainer-templates/main/templates-2.0.json
```

Any trademarks or logos used in the templates are the property of their respective owners, and are used for identification purposes only.

To generate the list of categories and applications, you can use the following command:
```bash
docker compose run app-meta
```

## Category List
<!--
Acquired by pasting the template JSON into browser DevTools, then running:
```js
console.log(
  '- '
  + Array.from(
    new Set(
      json.templates
        .flatMap((t) => t.categories)
        .map((c) => (c.charAt(0).toUpperCase() + c.slice(1)))
    )
  ).sort().join('\n- ')
)
```
-->
- Backup
- Cms
- Development
- Docker
- Games
- Graphic design
- Management
- Pdf
- Photos
- Secrets
- Tools

## Application List
<!--
Acquired by pasting the template JSON into browser DevTools, then running:
```js
console.log('- ' + Array.from(new Set(json.templates.map((t) => t.title))).sort().join('\n- '))
```
-->
- Asciinema {shmolf}
- Cockpit {shmolf}
- Code-server {shmolf}
- Immich {shmolf}
- Infisical {shmolf}
- Penpot (http) {shmolf}
- Stirling PDF {shmolf}
- Terraria Server {shmolf}
- Watchtower {shmolf}
