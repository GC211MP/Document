# API

### Server

- Provide User and Rank data for App.
- [Diagrams](https://github.com/GC211MP/API)
- [API Document](https://github.com/GC211MP/API/blob/main/documents/api.md)

- Demo
  - **POST: `/user`**
    - |demo|
      |:--:|
      |![]()|

  - **GET: `/user?uid=[user_id]`**
    - |demo|
      |:--:|
      |![]()|

  - **PATCH: `/user`**
    - |demo1|demo2|demo3|
      |:--:|:--:|:--:|
      |![]()|![]()|![]()|

  - **POST: `/data`**
      - |demo|
      |:--:|
      |![]()|

  - **GET: `/data?c=""&o=""`**
    - |demo1|demo2|
      |:--:|:--:|
      |![]()|![]()|

### App

- Connect with server and manage data through API.
- `APIManager.java`: maintain API connection and received data.
  - This class will be implemented by Singleton pattern
  - With Singleton, every view can access and use API data.
- Demo
  - (will be added)