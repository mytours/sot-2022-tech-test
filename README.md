# STQRY Tech Test

Welcome to the STQRY Tech Test for the Summer of Tech 2022 internship.

To complete this test:

- Clone the repo
- `yarn`
- `yarn dev`
- Navigate to `http://localhost:5173`
- Open `Image.tsx`
- Complete the TODOs
- Send us the `Image.tsx` file when you're done

**Note**: this test is not timed, but we expect it to take no more than 1 hour.

**Important**: you MUST NOT use `object-fit: cover` or `objectFit: 'cover'` so this solution will not be accepted:

```tsx
function Image(props: Props) {
  const { src, alt } = props;
  return (
    <img
      style={{
        width: '100%',
        height: '100%',
        objectFit: 'cover',
      }}
      src={src}
      alt={alt}
    />
  );
}
```
