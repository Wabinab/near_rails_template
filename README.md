# Rails JS Template (Under Development)

The first thing is to recreate master key and credentials. 

```
EDITOR="code ." bin/rails credentials:edit
```

**Close the file.** Then run migrations:

```
rails db:migrate
```

Everything should be fine after that. Try to start `rails s` and see if it starts or not. 