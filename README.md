# httpbin(1): HTTP Request & Response Service


![ice cream](http://farm1.staticflickr.com/572/32514669683_4daf2ab7bc_k_d.jpg)

Run locally:
```sh
docker pull prateek076/httpbin-image
docker run -p 80:80 prateek076/httpbin-image
```

See http://httpbin.org for more information.

## Officially Deployed at:

- http://httpbin.org
- https://httpbin.org
- Image: https://hub.docker.com/repository/docker/prateek076/httpbin-image

Install Helm Chart:

- Clone the httpbin helm chart.
- Run below command to install the chart: 
    helm upgrade --install -f httpbin-common/values.yaml --namespace ${{ NAMESPACE }} httpbintest httpbin-common
