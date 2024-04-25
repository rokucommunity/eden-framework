# http
We have an http service. Here's how you use it.

```brighterscript
promise = eden.http.get("api.server.com/userId")
promises.onThen(promise, function(userId)
    print userId
end function)
```