#usage:

```
version: 0.01
type: Deploy
namespace: {{vars.ZKUBE_NAMESPACE}} 
secretKey: {{secrets.ZKUBE_SECRET_KEY}}
deploys:
    - name: FastAPI HTTP Server
      slug: fastapi-http
      image: https://github.com/zkube-io/fastapi
```
  
