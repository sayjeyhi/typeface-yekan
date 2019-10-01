Typeface package for byekan font

```bash
npm i typeface-byekan
```
Fonts will be copied to node_modules/typeface-byekan/dist directory
and you could add them easily to your project :
```javascript
import 'typeface-byekan';
```
and use `font-family: 'Yekan'` in your styling.


we used to do this with : 
```css
@font-face {
    font-family: 'Yekan';
    src: url('./Yekan.eot');
    src: url('./Yekan.eot?#iefix') format("embedded-opentype"),
    url('./Yekan.woff2') format('woff2'),
    url('./Yekan.woff') format('woff'),
    url('./Yekan.ttf') format('truetype'),
	url('./Yekan.otf') format('opentype'),
    url('.//Yekan.svg#Yekan') format('svg');
    font-weight: normal;
    font-style: normal;
}
```
