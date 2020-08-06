# Notes
It's been a minute since I did .NET from the ground up, and this is my first time going full Angular SPA. Bear with me while I get a handle on the generated stuff.

Is there a better way to get a nice task runner?
`dotnet msbuild -target:push`

# Screens
- Landing page - overview of program
- List of resources (training plans, Strava, ...)
- List of goals
- Goal entry
- Signin
- Goal editing
  - Immutable updates, rather than edits

# Tasks
- Google oauth
- Goal entry

# Future
- Pull Strava/other data
- Profile pages

# Deployment
```
heroku buildpacks:set jincod/dotnetcore
heroku buildpacks:add --index 1 heroku/nodejs
```
