# Petful

This is where dogs and cats are adopted. Adoption here is first in, first out. Adoption is possible after you reach the top of the list.
## Link

Live app: https://petful-app-main.vercel.app/ 
Client repo: https://github.com/Cheyenne-development/petful
## What I Used for App

### Back End

- Node and Express
  - RESTful Api

- Production
  - Deployed via Heoku

### Front End

- React
  - Create React
  - React Router
  - React Context

- Testing
  - Jest(Somke tests)

- Production
  - Deployed via Vercel


## Documentation of API


### Petful's Endpoint

#### People Endpoint

```http
GET  /api/people
```

Provides array of all people in the queue

```http
POST  /api/people
```

|  Key         | Values               |
| :------------|----------------------|
|   name       | string, required     |

Adss a new person to the queue


```http
DELETE  /api/people
```

Delete first person in the queue


#### Cat Endpoint

```http
GET  /api/cats
```

Provides array of all cats in the queue

```http
DELETE  /api/cats
```

Deletes first cat in the queue

#### Dog Endpoint

```http
GET  /api/dogs
```

Provides array of all dogs in the queue

```http
DELETE  /api/dogs
```

Deletes first dog in the queue

