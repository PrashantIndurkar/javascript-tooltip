[Github](https://github.com/PrashantIndurkar/javascript-tooltip).

# What is javascript-tooltip?

Its a small tooltip library for javascript to help you get tooltip when you hover on text. its uses data attribute.

you can use this in any `.js` file by just installing like other npm package.

**How to use?**

1. `npm i javascript-tooltip`.

2. add data-tooltip to whichever element you want to have tooltip.

3. make sure add content to that data-tooltip like this `data-tooltip="javascript tooltip"`.

## Extra things

**Spacing:**

you can give padding / spacing to the tooltip by using data attribute `data-spacing` and value can be any css number.

_Example:_ ` data-spacing="12"`.

**Positions:**

you can specify where the first tooltip shows like top/left/bottom/right its a by default positions but u can give any direction.

but u have to use same keywords top|left|bottom|right as u can see u can give more than one by giving pipe sine (|).

**Example**: `data-positions="top|right"`.

**Full Example:**

```html
<h1
  data-spacing="12"
  data-positions="top|right"
  data-tooltip="javascript tooltip"
>
  which package is this
</h1>
```

![image](https://user-images.githubusercontent.com/32466796/194895381-4f6c17a3-d890-4a5e-9f48-f6ca24c2ea64.png)
