# Diesel Demo

A very small CRUD cli application using Diesel.

## How to use

First, start the Database (Postgres): docker-compose up

```
// Create Posts
cargo run --bin write_post

// Read Posts
cargo run --bin show_posts

// Update/Publish Post
cargo run --bin publish_post POST_ID

// Delete Post
cargo run --bin delete_post POST_TITLE
```
