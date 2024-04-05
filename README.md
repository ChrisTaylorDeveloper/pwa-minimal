# PWA Calculators

Genesis  
https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/how-to/

I had his running on Digital Ocean App Platfrom for a while.

Running locally, assuming npx is installed
```
cd pwa-calculators
npx http-server
```

Run with nginx in Docker
```
cd pwa-calculators
docker run --rm -p 80:80 --name our_ws -v $PWD:/usr/share/nginx/html nginx
```