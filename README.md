# PRISMA WITH EXPRESS

## TO START THE SERVER

```bash
npx ts-node src/index.ts
```

## MAKING REQUESTS

### GET ALL USER

```bash
curl http://localhost:3000/users
```

### GET USER BY ID

```bash
curl http://localhost:3000/users/1
```

### OTHER REQUESTS

| HTTP Method | Route              | Description                     |
|-------------|--------------------|---------------------------------|
| GET         | /feed              | Fetches all published posts.    |
| GET         | /post/:id          | Fetches a specific post by its ID. |
| POST        | /user              | Creates a new user.             |
| POST        | /post              | Creates a new post (as a draft). |
| PUT         | /post/publish/:id  | Sets the published field of a post to true. |
| DELETE      | post/:id           | Deletes a post by its ID.       |
