## API Endpoints testing

http://127.0.0.1:8000/api/menu/items

| Method | Action                  | TOKEN AUTH | STATUS CODE |
| ------ | ----------------------- | ---------- | ----------- |
| GET    | Retrieve all menu items | No         | 200         |
| POST   | Create a menu item      | No         | 201         |

```
http://127.0.0.1:8000/api/menu/items/{itemId}
```

```
http://127.0.0.1:8000/api/booking/tables
```

```
http://127.0.0.1:8000/api/booking/tables/{bookingId}
```
