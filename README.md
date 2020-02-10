# React Notes

## Step 1: BEFORE REACT

folder: step.1\

1. On VSC create simple index.html file in the public folder with typical content.

  - Tip: Setup to 2 spaces indetation: [CTRL ,] type "editor tab size" set "2".

  - Tip: Set LF to CRLF.

    ```
    <!DOCTYPE html>
    <html>

    <head>
      <meta charset="UTF-8">
      <title>First app</title>
    </head>

    <body>
      This is my HTML file!
    </body>

    </html>
    ```

2. Create server: 

  > npm install -g live-server

  - Test with:
  > live-server -v

  > You get: live-server 1.2.1

3. Run simple index.html: 
    > cd step.1

    > live-server public

    VOILÁ!

## Step 2: BASIC REACT

1. On VSC create simple index.html file in the public folder with a call to react library.

```
    <!DOCTYPE html>
    <html>

    <head>
      <meta charset="UTF-8">
      <title>First app</title>
    </head>

    <body>
      <script src="https://unpkg.com/react@16.0.0/umd/react.development.js"></script>
      <script src="https://unpkg.com/react-dom@16.0.0/umd/react-dom.development.js"></script>
      <script src="/scripts/app.js"></script>
    </body>

    </html>
```

2. Check if React is loaded

> On Developer Tool Console type: React and ReactDOM

3. Check if Babel is loaded

> On Terminal type: babel --help


