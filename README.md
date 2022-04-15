# Redwood JS Blog Example 1

The commands documented below came from the
[RedwoodJS Tutorial](https://redwoodjs.com/docs/tutorial/foreword)
webpage.

This repo contains the tutorial forward to intermission and
chapter 5 to the afterword will be in this tbd repo.

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
# auth
yarn rw setup auth dbAuth # y for overwrite default auth code
yarn rw prisma migrate dev # after adding user to schema.prisma
yarn rw g dbAuth # auth gui
# deploy db on railway.app and setup .env and schema.prisma provider
yarn rw prisma migrate dev
yarn rw setup deploy netlify
yarn rw g secret
# intermission
yarn rw setup ui tailwindcss
```
