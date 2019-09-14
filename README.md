# chatroom

A chat room that is destroyed when it is used up. It's using a simple `roomcode` to connect users.
You can use it to communicate with others, transfer files, pictures, etc.

## Frontend
1. `$ npm install -g cnpm --registry=https://registry.npm.taobao.org` china mirror
2. `$ cnpm install` install dependencies
3. `$ cnpm run dev` frontend devolop
4. `$ cnpm run dev:no-mock` devolop with backend
5. `$ cnpm run build` build frontend

## Backend
1. copy the output files('chatroom-ui/dist/') of frontend to 'chatroom-server/src/main/resources/static/'
2. gradle build

## Todo [1/3]
- [X] init project
- [ ] chatroom-ui [0/2]
  - [ ] WelcomePage [0/2]
    - [ ] create room or join room
    - [ ] input `roomcode` to join room
  - [ ] WelcomePage [0/4]
    - [ ] ChatTitle [0/1]
      - [ ] title and `roomcode`
    - [ ] ChatMember
    - [ ] ChatWindow
    - [ ] ChatInput
- [ ] chatroom-server [0/6]
  - [ ] Controller
  - [ ] Service
  - [ ] Repository
  - [ ] Entity
  - [ ] Model
  - [ ] Util
