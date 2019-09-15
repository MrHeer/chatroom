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
  - [ ] WelcomePage [0/3]
    - [ ] two button `Create Room` and `Join Room`
    - [ ] input `username` to create room
    - [ ] input `roomcode` and `username` to join room
  - [ ] RoomPage [0/4]
    - [ ] RoomName [0/1]
      - [ ] show `roomname` and `roomcode`
    - [ ] RoomMember [0/1]
      - [ ] show the menbers of the room
    - [ ] RoomWindow [0/1]
      - [ ] Message [0/3]
        - [ ] Time
        - [ ] UserName
        - [ ] Content [0/5]
          - [ ] Text
          - [ ] Picture
          - [ ] File
          - [ ] Audio
          - [ ] Video
    - [ ] RoomInput [0/5]
      - [ ] Text
      - [ ] Picture
      - [ ] File
      - [ ] Audio
      - [ ] Video
- [ ] chatroom-server [0/6]
  - [ ] Controller
  - [ ] Service
  - [ ] Repository
  - [ ] Entity
  - [ ] Model
  - [ ] Util
