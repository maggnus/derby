# Derby

The Derby MVC framework makes it easy to write realtime, collaborative applications that run in both Node.js and browsers.

Derby includes a powerful data synchronization engine called Racer that automatically syncs data among browsers, servers, and a database. Models subscribe to changes on specific objects, enabling granular control of data propagation without defining channels. Racer supports offline usage and conflict resolution out of the box, which greatly simplifies writing multi-user applications.

Derby applications load immediately and can be indexed by search engines, because the same templates render on both server and client. In addition, templates define bindings, which instantly update the view when the model changes and vice versa. Derby makes it simple to write applications that load as fast as a search engine, are as interactive as a document editor, and work offline.

See docs here: **https://derbyjs.github.io/derby/**

Main site: **https://derbyjs.com/**

Examples here: **https://github.com/derbyjs/derby-examples**

## Development

Derby needs Node.js 22 or newer. While the forks of Racer and Tracks are not published, they are installed from the folders next to this repository (`../racer` and `../tracks`), and they have to be built first.

```sh
npm install
npm test         # unit tests of the templates, parsing, components and server
npm run lint
npm run build    # compiles src/ to dist/
npm run docs     # generates the API documentation
```

## Getting in touch

Create an [issue](https://github.com/derbyjs/derby/issues) or reach out to the derbyjs [team](https://github.com/orgs/derbyjs/people).

Further resources: **https://derbyjs.com/resources**

## License

MIT, see [LICENSE](LICENSE).
