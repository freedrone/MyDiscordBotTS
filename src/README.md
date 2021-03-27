This is where you put your code!

Write your implementations under this directory.

If and only if, you need some modifications to core classes or enhancements, then manipulate `/core` folder contents.

## Development

Initialize your bot's `index.ts` with at least following.
```javascript
const run = () => {
  // This is where my bot starts running
  console.log("My Bot");
  
  new MyBot();
}

export default run;
```

In your `package.json` use add following for development
```json
{
  ...
  "scripts": {
    "dev": "npm --prefix ../../ run dev"
  },
  ...
}
```

## Packaging
1. Use the template's root directory for packaging.
