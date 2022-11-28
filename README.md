# renovate-terraform-bug-19151

https://github.com/renovatebot/renovate/issues/19151

## Current Behavior

Renovate changes the suffix from `-debian` to `-distroless-static`

```
docker.io/timberio/vector:0.25.1-debian
    -> docker.io/timberio/vector:0.25.1-distroless-static
```

## Expected Behavior

No PR opened, or if there is an update to continue to use the `-debian` prefix

```
docker.io/timberio/vector:0.25.1-debian
    -> docker.io/timberio/vector:0.68.420-debian
```
