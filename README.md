# Signed S3 URLs

## Usage

```
go run src/main.go <bucket>/<key> <aws-profile>
go run src/main.go my-bucket/my/key.txt dev-profile
```

Verify the upload with:
```
curl -X PUT -T <my-file> '<generated-url>'
```

