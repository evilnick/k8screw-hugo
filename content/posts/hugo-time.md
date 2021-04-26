---
title: "Hello K8s Crew"
date: 2021-04-26T11:37:04+01:00
draft: false
---

This is really just a test of some markdown type stuff to see that we can do useful things.

For example, what does a list look like?

<!--more-->

-  It seems
-  to look very much
-  like this.


## code examples

These should be pretty straightforward.

```yaml
kind: Ingress
apiVersion: extensions/v1beta1
metadata:
  name: "foo"
  namespace: production

spec:
  rules:
    - host: example.net
      http:
        paths:
          - path: /bar
            backend:
              serviceName: service1
              servicePort: 80
          - path: /foo
            backend:
              serviceName: service1
              servicePort: 80
```

### Images

![an image](https://aws1.discourse-cdn.com/business6/uploads/kubernetes/original/2X/8/8a8e4ef1a1edf54a782080ef25bb3423210979f6.png)

This should also work
