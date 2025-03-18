## APIs to Test

### Authentication
- **POST** `/auth/token/login`  
  _Use credentials:_  
  ```json
  {
    "username": "admin",
    "password": "root"
  }
  ```

### Restaurant
- **GET** `/restaurant`
- **GET, POST** `/restaurant/menu`
- **GET** `/restaurant/menu/<id>`

### User Booking
- **GET, POST** `/restaurant/booking/users`
- **GET** `/restaurant/booking/users/<id>`

### User Management
- **GET, POST** `/auth/users`
