# UPYUN Go SDK ChangeLog

## Version 1.1.0

date: 2015.06.10

### features

1. add purge and form api
2. user can use io.Reader or io.Writer instead of os.File in REST Put or Get
3. add user agent in http request headers

### Change

1. change default chunk size to 32kb, and SetChunkSize will influenced entire program once used.


### Bugfix

1. fix a bug when using md5 in put
