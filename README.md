# GatherSpace


## How to run back-end
1. di chuyển đến thư mục `\GatherSpace\backend\gatherspace` 
2. Build docker image

```
docker build -t gs_backend .
```

3. Run server bằng docker-compose

```
docker-compose up
```

4. Khởi tạo Database

```
docker exec -it gs-backend pipenv run python manage.py migrate
```

> Đối với những lần chạy sau chỉ cần `docker-compose up` tại thư mục `\GatherSpace\backend\gatherspace`