### Ops

#### Main tech

- docker
- docker compose

#### Containers

- server containers:
  - API _Rust_
  - express _Node.js, Socket.io_
- client containers:
  - web-client _vue.js, nuxt.js_
  - mobile-client _react-native_ (optional)
- database containers:
  - mysql
  - redis
- other containers (for further development):
  - nginx

#### volumes

- data volumes:
  - mysql
  - redis
- node_modules volumes **?**:
  - express
  - web-client
  - mobile-client (optional)
