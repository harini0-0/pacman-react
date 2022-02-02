# pacman-react

Pacman game written as a React component

## Dependencies

- `npm install && npm run build`
- `npm run dev`

Note that `rsync` is required.


## Use as a dependency

To use `pacman-react` as a dependency, run (in your project)

`npm install -S pacman-react`

Then you can do something like the following:

```js
import { render } from 'react-dom';
import Pacman from 'pacman-react';

render(<Pacman />, document.getElementById('root'));
```


