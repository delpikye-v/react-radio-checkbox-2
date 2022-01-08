<div align="center">
    <h1>react-radio-checkbox-2z</h1>
    <strong>
        <a href="https://www.npmjs.com/package/react-radio-checkbox-2z">react-radio-checkbox-2z</a>
    </strong>
    <br />
    <br />
    <a href="https://codesandbox.io/s/lljsl">LIVE EXAMPLE</a>
</div>

---

#### Description
+ You can customize <b>icon</b>, <b>theme</b> or <b>color</b> for <b>Checkbox/Radio</b>
+ Single option
+ It is not `react-radio-checkbox-z`

#### Usage
```js
npm install --save react-radio-checkbox-2z
```

Import the module in the place you want to use:
```js
import RadioOrCbx from "react-radio-checkbox-2z";
```

#### Snippet
```js
    const [value, setValue] = useState('label1') // radio
    // const [value, setValue] = useState(['label1']) // radio || checkbox

    <RadioOrCbx optionLabel='abcd1' optionValue='ab1' selectedValue={value} onChange={setValue} />
    <RadioOrCbx optionLabel='abcd2' optionValue='ab2' selectedValue={value} onChange={setValue} />

    // Customize label
    <RadioOrCbx optionValue='ds2' selectedValue={value} onChange={setValue}>Label</RadioOrCbx>
```

#### Props

| props                | type                          | description                                                                |
|----------------------|-------------------------------|----------------------------------------------------------------------------|
| id                   | String                        |                                                                            |
| theme                | String                        | default: `tick`                                                            |
| className            | String                        | css                                                                        |
| disabled             | boolean                       |                                                                            |
| boxSize              | number                        | default: 16                                                                |
| typeCheckbox         | boolean                       | default: `false` (radio)                                                   |
| floatRight           | boolean                       | default: `false` (Check in left)                                           |
| isRect               | boolean                       | default: `false` (Checkbox is circle)                                      |
| groupName            | String                        | groupName of radio/checkbox                                                |
|                      |                               |                                                                            |
| selectColor          | String                        | Default `#4169E1` (color when checked)                                     |
| unSelectColor        | String                        | Default `#cbd1d8` (color when unchecked)                                   |
| hoverColor           | String                        | Color when hover. Default using (selectColor)                              |
| tabFocusColor        | String                        | Default `#000000`  box shadow color when focus                             |
| tickColor            | String                        | Color of tick when check.                                                  |
|                      |                               |                                                                            |
| checkedIcon          |                               | Customize icon                                                             |
| optionLabel          |                               | Display label text                                                         |
| optionValue          | any                           | Value option (`string` || `number`)                                        |
| selectedValue        | Single, Array                 | Current selected value                                                     |
| onChange             | func                          | Event change                                                               |

##### Note
Theme 'fill', 'in', 'out', 'tick', 'tick-fill', 'tick-fill-in', 'x', 'x-fill', 'x-fill-in'

#### Example
<a href="https://codesandbox.io/s/lljsl">LIVE EXAMPLE</a>

A working example can be found in the `example` directory.

```js
npm install
```
```js
npm run dev
npm run start
```

### License
MIT
