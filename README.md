# parcel-html-ts
Setup process for an HTML app with Typescript support using Parcel.

### Creating the app
Create the app directory
```bash 
mkdir app
cd app
```

Create the `src/index.html` file.
```html
<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>App</title>
    <script src="main.ts"></script>
</head>
<body>
    <h1>HTML + TS</h1>
</body>
</html>
```

Create the `src/main.ts` file.
```ts
const value: string = "TS";
console.log(value);
```

Install Parcel
```bash
npm i -D parcel
npx parcel src/index.html
```