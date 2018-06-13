# scdf-recipe-routing

## Named Destination

Current message example goes here

## Fan-In/Fan-Out

Fan In means all different sources going to one channel (named Destination).

Fan In

```shell

s3 > :data
ftp > :data
http > :data

```

Fan Out

```shell

:data > jdbc
:data > log

```

Same messages writen to two different places
