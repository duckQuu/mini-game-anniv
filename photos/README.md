# Photos

Put your pictures in this folder, then list them in `movie.photos` in the CONFIG block at the top of `index.html`, in the order they should play:

```js
photos: [
  { src: 'photos/1.jpg', text: 'The first day we met' },
  { src: 'photos/2.jpg', text: 'Our first trip together' },
],
```

Use JPG or PNG. iPhone HEIC photos don't show in most browsers. Export them as JPG, or convert them on a Mac with `sips -s format jpeg photo.heic --out photo.jpg`.
