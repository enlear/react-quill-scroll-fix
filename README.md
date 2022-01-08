Workaround for React Quill Scroll Comes to Top

-------------

Usage

```bash
# in your project root
yarn add react-quill-scroll-fix
```

```js
// in your app – import and register the module
import CustomClipboard from 'react-quill-scroll-fix'

Quill.register('modules/clipboard', CustomClipboard);
```

*Note*: Setup `scrollingContainer='html, body'`
