# trailing-slash-redirect-test

https://stackblitz.com/edit/trailing-slash-redirect-test?file=README.md

- clone this repository to your local drive
- `pnpm install`
- `pnpm run generate`
- `docker run -v ./dist:/usr/share/nginx/html:ro -v ./nginx.conf:/etc/nginx/conf.d/default.conf:ro -p 3000:80 nginx:latest`
- navigate to `http:/localhost:3000/test` with chrome devtools > network tab open
