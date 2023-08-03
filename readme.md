Steps

1.  npm init -y
2.  npm install -D tailwindcss
3.  npx tailwindcss init
4.  add src/input.css su 3 eilutemis:
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
5.  create src/index.html
6.  run commant to start Tailwind:
    npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
