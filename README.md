# Development
Steps to run app in development mode

1. Up database
```
docker compose up -d
```

2. Rename .env.template to .env
3. Replace environment variables
4. Execute seed to [create local database](localhost:3000/api/seed)


# Prisma commands
```
npx prisma init
npx prisma migrate dev
npx prisma generate
```

# Prod

# Stage