To reproduce:

1. `npm install`
2. `npm run dev`
3. Open `pages/index.js`
4. Add `bg-red-100` to the `className` prop
5. Save the file
6. Add `bg-red-200` to the `className` prop
7. Save the file
8. Add `bg-red-300` to the `className` prop
9. Save the file
10. Inspect the `h1` element and see that the `bg-red-100` and `bg-red-200` classes are duplicated
