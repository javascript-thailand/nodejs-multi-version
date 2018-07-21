# nodejs-multi-version

[https://www.facebook.com/JavaScriptThailand/](https://www.facebook.com/JavaScriptThailand/)

Run the following commands one by one:

docker run --rm --mount type=bind,source="$(pwd)"/js,target=/js node:8 node /js/version.js

docker run --rm --mount type=bind,source="$(pwd)"/js,target=/js node:10 node /js/version.js