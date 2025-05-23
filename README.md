<h1 align="center">PriorityHub</h1>
PriorityHub e уеб приложение на NestJS и React с цел следене на продуктивност.

## Стартиране

За да стартираш приложението, изпълни тези команди:

```
# Clone the repository locally
git clone https://github.com/pesho21/priorityhub --recurse-submodule
cd priorityhub

# Fill out the .env variables for the backend
cp priorityhub-backend/env.template priorityhub-backend/.env
nano priorityhub-backend/.env

# Fill out the .env variables for the frontend
cp priorityhub-frontend/env.template priorityhub-frontend/.env
nano priorityhub-frontend/.env

# Start all necessary containers using docker compose
docker compose up -d
```

## Функционалности

- API, написан на NestJS.
- Автентикация, чрез имейл ИЛИ потребителско име и парола.
- Опция за създаване, преглед, редактиране и изтриване на работни задачи.
- Способността за задаване на един или повече потребители към всяка задача.
- Приоритизация на задачите.
- Таймер, който да следи времето, отделено на всяка една от работните задачи. 
- Групировка на работните задачи по итерации (спринтове).
- Опция за генериране на доклад за всяка изминала итерация, който включва броя на изпълнените работни задачи и времето отделено за изпълнението им в периода на итерацията. 

