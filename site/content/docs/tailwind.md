# Tailwind support

Flowershow comes with built-in [tailwind](https://tailwindcss.com) support on any markdown page for styling your content.

That means you can do things like:

```hmtl
<div className="text-green-500">
Hello World!
</div>
```

Which is rendered like this:

<div className="text-green-500">
Hello World!
</div>

And it means you have access to the full ecosystem of tailwind features and components.

> [!Note] className rather than class
>
> You may have noticed we used `className` rather than `class` attribute in our html. That's because we are using [[docs/mdx|MDX]] (markdown extended) rather than pure markdown, so we follow React conventions and use `className`
