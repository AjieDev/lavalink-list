![lavalink-list](https://socialify.git.ci/AjieDev/lavalink-list/image?description=1&font=Inter&forks=1&language=1&logo=https%3A%2F%2Fcdn-cf.ajieblogs.eu.org%2Fimg%2F1727676032086.png&name=1&owner=1&pattern=Plus&pulls=1&stargazers=1&theme=Auto)

<div align="center"> <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/AjieDev/lavalink-list?style=for-the-badge"> <a href="https://dsc.gg/ajidevserver"><img alt="Discord - AjieDev" src="https://img.shields.io/discord/993867537337024565?label=Discord&logo=discord&style=for-the-badge"></a></div>

<p align="center">
    <a href="https://free.lavalink.rf.gd/list">The Website</a>
    .
    <a href="https://github.com/AjieDev/lavalink-list/pulls">Make a pull request</a>
  </p>

[EN](README.md) | [ID](docs/README_id-ID.md)

**Attention:** For any extra support, questions, check out our [Discord](https://dsc.gg/ajidevserver).



# Add new nodes
1. Fork this repository
2. Edit the nodes.json file and add your node like the example
3. Create pull request

### nodes.json example
```json
[
    {
        "unique-id": "nodes-v4",
        "identifier": "My Node v4", 
        "host": "lavalink1.example.com",
        "port": 2333, 
        "password": "youshallnotpass",
        "secure": false,
        "version": "v4"
    }
]

```
- `unique-id` - The unique id of your node (example: nodes-v4) (Note: must used lowercase and change space with - )
- `identifier` - The identifier of your node (example: My Node v4)
- `host` - The host of your node (can be sub domain or IP)
- `port` - The port of your node
- `password` - The password of your node (if you have one)
- `secure` - If your node is using SSL (true or false)
- `version` - The version of your node (lavalink rest api version) (v3 or v4)

# API

### Badges

Stats service also supports badges generation, here the breakdown:

```
https://lavalink-list-api.ajieblogs.eu.org/<unique-id>/badge/<type>
```
- `<unique-id>` - Your unique-id
- `<type>` - Badge type, supported badge type are: `Players`, `Status`, `Load`

Example: `https://lavalink-list-api.ajieblogs.eu.org/serenetia-v3/badge/Players` <br />
Output: ![Players](https://lavalink-list-api.ajieblogs.eu.org/serenetia-v3/badge/Players) <br />

Example: `https://lavalink-list-api.ajieblogs.eu.org/serenetia-v3/badge/Status` <br />
Output: ![Players](https://lavalink-list-api.ajieblogs.eu.org/serenetia-v3/badge/Status) <br />

Example: `https://lavalink-list-api.ajieblogs.eu.org/serenetia-v3/badge/Load` <br />
Output: ![Players](https://lavalink-list-api.ajieblogs.eu.org/serenetia-v3/badge/Load)


# Note

- Stats service may spam your stats and info endpoint (based on how many people opens the website and badges being generated), if you have firewall or rate limit you can whitelist this IP:

```
2a06:98c0:3600::103
```

- Node will marked as offline if timeout for 3 seconds
- Inactive servers or nodes may get deleted to avoid status delay.

# Contributors

<a href="https://github.com/AjieDev/lavalink-list/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=AjieDev/lavalink-list" />
</a>
