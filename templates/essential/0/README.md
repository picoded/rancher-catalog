# Essential docker container stack

Essential docker containers, that should run with every instance.
You may however disable them, with the use of tags (though i do not see why).

Note this deploy on all instances within a cluster

### Instance Control Tags:

Disable the stack:
+ `no-essential=true`

Disable individual components
+ `no-haveged=true`
+ `no-logrotate=true`