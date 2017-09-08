# Oh My Compose

A collection of some useful Composé sequences.

```
$ git clone https://github.com/iamale/oh-my-compose.git ~/.oh-my-compose
$ cat > ~/.XCompose
include "/home/[username]/.oh-my-compose/diacritics"
include "/home/[username]/.oh-my-compose/common"
include "/home/[username]/.oh-my-compose/arrows"
# include "/home/[username]/.oh-my-compose/math"
# include "/home/[username]/.oh-my-compose/music"
```

(You have to specify absolute paths, otherwise applications will look for
`.oh-my-compose` in `$PWD` and fail!)
