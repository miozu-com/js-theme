# @miozu/js

Miozu color theme exported as javascript object. 

## Installation

```bash
npm install @miozu/js-theme
```

## Usage with tailwind

In your `tailwind.config.js`:

```javascript
import miozu from '@miozu/js-theme';

export default {
  theme: {
    extend: {
      colors: {
        ...miozu
      }
    }
  }
  // ... rest of your Tailwind configuration
};
```

## Available Colors

- base1: '#232733'
- base2: '#2C3040'
- base3: '#3E4359'
- base4: '#565E78'
- base5: '#737E99'
- base6: '#D0D2DB'
- base7: '#F3F4F7'
- base8: '#FAFBFD'
- red: '#EB3137'
- orange: '#FF9837'
- green: '#6DD672'
- yellow: '#E8D176'
- blue: '#83D2FC'
- magenta: '#C974E6'
- peach: '#FF9982'
- cyan: '#40FFE2'

*(more docs are coming soon)

## License

MIT
