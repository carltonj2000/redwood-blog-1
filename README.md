# Redwood JS Blog Example 1

The commands documented below came from the
[RedwoodJS Tutorial](https://redwoodjs.com/docs/tutorial/foreword)
webpage.

```bash
yarn redwood dev
yarn rw generate page Home /
yarn rw g page about # note g shorthand and NO/default page link
yarn rw generate layout blog
yarn rw prisma migrate dev
yarn rw prisma studio
yarn rw g scaffold post
yarn rw g types # for Cannot query "posts" on type "Query"
yarn rw g cell Articles
yarn rw g page Article
yarn rw g cell Article
yarn rw g component Article
# form below
yarn rw g page contact # add to schema.prisma
yarn rw prisma migrate dev
yarn rw g sdl Contact
```
