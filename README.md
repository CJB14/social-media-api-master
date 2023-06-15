# Social Media API

## User Story
As a social media startup, I want an API for my social network that uses a NoSQL database so that my website can handle large amounts of unstructured data.

# Instructions


1. Make sure you have MongoDB installed (https://docs.mongodb.com/manual/installation/))

2. Clone the repo
3. Install `npm -i`
4. Run `npm start`
5. Use your browser or [Insomnia](https://insomnia.rest/) to test

# User
Get users:            `GET /api/users`
Create a user:        `POST /api/users`
Get user by ID:       `GET /api/users/:id`
Update a user:        `PUT /api/users/:id`
Delete a user:        `DELETE /api/users/:id`
Add a friend:         `PUT /api/users/:userId/friends/:friendId`
Delete a friend:      `DELETE /api/users/:userId/friends/:friendId`

# Thoughts
Get thoughts:       `GET /api/thoughts`
Create thought:     `POST /api/thoughts`
Get ID:             `GET /api/thoughts/:id`
Update thought:     `PUT /api/thoughts/:id`
Delete thought:     `DELETE /api/thoughts/:id`

# Reaction
- Add a reaction:       `PUT /api/thoughts/:id/reactions`
- Delete a reaction:    `DELETE /api/thoughts/:id/reactions`

# packages to install
- express
- moment
- mongoose
