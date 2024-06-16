## Video
  
[![Watch the video](https://img.youtube.com/vi/CNOmfvD8HVM/maxresdefault.jpg)](https://youtu.be//CNOmfvD8HVM?si=SXT-OMEgirmrvSiD)

https://youtu.be/CNOmfvD8HVM?si=SXT-OMEgirmrvSiD

## Install

```
npm i -D @babel/core @babel/cli @babel/preset-typescript
npm i -D @babel/preset-env
```

## Configure

```
touch babel.config.json
```
```json
{
  "presets": ["@babel/preset-typescript", "@babel/preset-env"]
}
```

## Run

```
npx babel src/hello.ts  --extensions ".ts"  --out-dir=lib
```