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
- APIManager singleton is managed with using DTO(Data Transfer Object), DAO(Data Access Object) class for each database table.
  - Structure
  - ![]()
- Communication Demo
  - **USER**
    - |demo|
      |:--:|
      |![app_user](https://github.com/GC211MP/Document/blob/main/backend-dokyoon-kim/img/app_user.png?raw=true)|

  - **DATA**
    - |demo: POST(Create)|
      |:--:|
      |![app_data_post](https://github.com/GC211MP/Document/blob/main/backend-dokyoon-kim/img/app_data_post.png?raw=true)|
    - |demo: GET(Read) with ascending order|
      |:--:|
      |![user_post](https://github.com/GC211MP/Document/blob/main/backend-dokyoon-kim/img/app_data_asc.png?raw=true)|
      |**demo: GET(Read) with descending order**|
      |![user_post](https://github.com/GC211MP/Document/blob/main/backend-dokyoon-kim/img/app_data_desc.png?raw=true)|
