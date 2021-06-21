# superset-ui-plugins
![release-workflow](https://github.com/berdiyev7/superset-ui-plugins/workflows/release-workflow/badge.svg)

### Project Overview

#### Template repository
This repository is a [template repository](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) that enables you to create a custom set of plugins that by Github workflow process generate a ready to load docker image bundled with the plugins

#### Monorepo
This repository is using a monorepo strategy which lets us have one source of truth for ***many projects***. All the projects hosted here rely on the same tools.


#### Artifacts Deployment

- Npm packages are deployed [here](https://www.npmjs.com/search?q=%40superset-ui-plugins)
- Docker Image is deployed [here](https://hub.docker.com/r/nielsenoss/apache-superset)

  
### Connection to superset

1. Replace `superset/superset-frontend/webpack.config.js` with [webpack.config.js](./docs/webpack.config.js)
2. Use [this](https://preset.io/blog/2020-07-02-hello-world/) tutorial to connect plugins to superset


### Storybook examples (uses Chromatic)

- [Stories view](https://master--60d060bb2987070039615441.chromatic.com)
- [Library view](https://chromatic.com/library?appId=60d060bb2987070039615441&branch=master)

### Plugins in repository

| Package                                                                                                                       | Version                                                                                                                                                         |
| ----------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [@superset-ui-plugins/plugin-chart-composed](https://github.com/berdiyev7/superset-ui-plugins/tree/master/plugins/plugin-chart-composed)                     | 
[![Version](https://img.shields.io/npm/v/@superset-ui-plugins/plugin-chart-composed?style=flat-square)](https://www.npmjs.com/package/@superset-ui-plugins/plugin-chart-composed)                             |
| [@superset-ui-plugins/plugin-chart-waterfall](https://github.com/berdiyev7/superset-ui-plugins/tree/master/plugins/plugin-chart-waterfall)                     | 
[![Version](https://img.shields.io/npm/v/@superset-ui-plugins/plugin-chart-waterfall?style=flat-square)](https://www.npmjs.com/package/@superset-ui-plugins/plugin-chart-waterfall)                             |
| [@superset-ui-plugins/plugin-chart-pie](https://github.com/berdiyev7/superset-ui-plugins/tree/master/plugins/plugin-chart-pie)                     | 
[![Version](https://img.shields.io/npm/v/@superset-ui-plugins/plugin-chart-pie?style=flat-square)](https://www.npmjs.com/package/@superset-ui-plugins/plugin-chart-pie)                             |
| [@superset-ui-plugins/plugin-chart-pivot-table](https://github.com/berdiyev7/superset-ui-plugins/tree/master/plugins/plugin-chart-pivot-table)                     | 
[![Version](https://img.shields.io/npm/v/@superset-ui-plugins/plugin-chart-pivot-table?style=flat-square)](https://www.npmjs.com/package/@superset-ui-plugins/plugin-chart-pivot-table)                             |
| [@superset-ui-plugins/plugin-chart-status](https://github.com/berdiyev7/superset-ui-plugins/tree/master/plugins/plugin-chart-status)                     | 
[![Version](https://img.shields.io/npm/v/@superset-ui-plugins/plugin-chart-status?style=flat-square)](https://www.npmjs.com/package/@superset-ui-plugins/plugin-chart-status)                             |


### Additional docs:

[Manage Repository](./docs/MANAGE_REPOSITORY.md)
