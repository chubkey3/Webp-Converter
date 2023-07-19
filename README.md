# DEPRECATED

Used to create the newer [compress](https://github.com/chubkey3/compress) library.

It can be installed using ```npm install @chubkey/compress```

## Webp-Converter
Converts a folder of image into webp format while keeping the same file structure.

<br>
Configure by adding a <code>.env</code> file.

## Example <code>.env</code>

```
TARGET="C:\Users\jason\test\Projects\webp-converter\images" <-- folder of images to be converted

DEST="C:\Users\jason\test\Projects\webp-converter\compressed" <-- folder of converted webp images

QUALITY=100 <-- quality of the webp images (1-100)
```

> .env must follow the same format as the example

# Run

After setting up the <code>.env</code> file, type <code>npm install</code> to download the neccessary dependencies in the same directory as <code>index.js</code> and type in <code>npm start</code> to begin converting.
