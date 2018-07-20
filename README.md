# nodejs-multi-version

[https://www.facebook.com/JavaScript-Thailand-1611235618987819/](https://www.facebook.com/JavaScript-Thailand-1611235618987819/)

Run the following commands one by one:

docker run --rm --mount type=bind,source="$(pwd)"/js,target=/js node:8 node /js/version.js

docker run --rm --mount type=bind,source="$(pwd)"/js,target=/js node:10 node /js/version.js