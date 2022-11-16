
<h1 align="center">react-iconkillua for React</h1>



<p align="center">
  1000 icons in 6 different styles, total 6000 icons | 
Perfectly balance | 
24px grid-based
<p>

<p align="center">
  <a href=""><strong>Browse icons at site</strong></a>
</p>
<br>
<br>

> ©️ iconsax <a href="https://iconsax.io/">github</a> and <a href="https://iconsax.io/">official
> website</a>(other format and platform available)

## Installation

```bash
yarn add react-iconkillua
# or
npm i react-iconkillua
```

## Usage

```jsx
import React from 'react';
//import icon.
import { EmojiHappy } from 'react-iconkillua';

const Example = () => {
  // then use it as a normal React Component
  return <EmojiHappy />;
};
```

You can configure Icons with inline props:

```jsx
<EmojiHappy color="#eee" variant="Bulk" size={54} />

// happy emoji with color #eee, variant Bulk and size 54px with love ❤️ (ibnahmad)

```

## Props

| Prop      | Type                                                | Default        | Note                   |
| --------- | --------------------------------------------------- | -------------- | ---------------------- |
| `color`   | `string`                                            | `currentColor` | css color              |
| `size`    | `number` `string`                                   | 24px           | size={24} or size="24" |
| `variant` | `Linear` `Outline` `TwoTone` `Bulk` `Broken` `Bold` | `Linear`       | icons styles           |

---

## Contributing

See
<a href="https://github.com/IBNAHMADMOHAMED1/react-iconkillua-/blob/main/CONTRIBUTING.md">CONTRIBUTING.md</a>

## License

<a href="https://github.com/IBNAHMADMOHAMED1/react-iconkillua-/blob/main/LICENSE">MIT</a>
