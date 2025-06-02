## Simple Image Uploader

[shadcn/ui](https://ui.shadcn.com/) is an amazing ui library but doesn't have an image uploader component. So I created one!

It has image validation built in and customizable styles with [tailwindcss](https://tailwindcss.com/)

The image is validated inside a shadcn Form using zod, react-drop-zone and react-hook-form.

### Caveats

- This component only works on client components and should not be used directly from a Nextjs page or layout component
- You need to be on NodeJs 20.x to use the File Interface which zod uses to verify the user uploads an image. If you can't update to Node 20.x you can skip that validation and use the native browser validation using required on the Input component.

### Demo

https://simple-image-uploader-bice.vercel.app/

### Svelte version

https://svelte-image-uploader.vercel.app/
