# API

### Server

- Provide User and Rank data for App.
- [Diagrams](https://github.com/GC211MP/API)
- [API Document](https://github.com/GC211MP/API/blob/main/documents/api.md)

- Demo
  - **POST: `/user`**
    - |demo|
      |:--:|
      |![user_post](https://github.com/GC211MP/Document/blob/main/backend-dokyoon-kim/img/user_post.png?raw=true)|

  - **GET: `/user?uid=[user_id]`**
    - |demo|
      |:--:|
      |![user_get](https://github.com/GC211MP/Document/blob/main/backend-dokyoon-kim/img/user_get.png?raw=true)|

  - **PATCH: `/user`**
    - |demo1|demo2|
      |:--:|:--:|
      |![user_patch1](https://github.com/GC211MP/Document/blob/main/backend-dokyoon-kim/img/user_patch1.png?raw=true)|![user_patch2](https://github.com/GC211MP/Document/blob/main/backend-dokyoon-kim/img/user_patch2.png?raw=true)|
      |**demo3**| |
      |![user_patch3](https://github.com/GC211MP/Document/blob/main/backend-dokyoon-kim/img/user_patch3.png?raw=true)| |

  - **POST: `/data`**
    - |demo|
      |:--:|
      |![data_post](https://github.com/GC211MP/Document/blob/main/backend-dokyoon-kim/img/data_post.png?raw=true)|

  - **GET: `/data?c=""&o=""`**
    - |demo1|demo2|
      |:--:|:--:|
      |![data_get1](https://github.com/GC211MP/Document/blob/main/backend-dokyoon-kim/img/data_get_1.png?raw=true)|![data_get2](https://github.com/GC211MP/Document/blob/main/backend-dokyoon-kim/img/data_get_2.png?raw=true)|

### App

- Connect with server and manage data through API.
- `APIManager.java`: maintain API connection and received data.
  - This class will be implemented by Singleton pattern
  - With Singleton, every view can access and use API data.
- Demo
  - (will be added)