# @jackholden/npm-package

This repository serves as a simple starter template for creating and publishing an NPM package. It includes automated semantic versioning (Semver) and changelog generation.

## Installation

### Latest version

```bash
npm install @jackholden/npm-package
```

### Specific version

```bash
npm install @jackholden/npm-package@0.0.1
```

## Usage

```javascript
import { helloWorld } from '@jackholden/npm-package';
```

```html
<script src="dist/npm-package.umd.cjs"></script>

<script>
  npmPackage.helloWorld();
</script>
```

```html
<script type="module">
  import { helloWorld } from '/npm-package.js';

  helloWorld();
</script>
```

### Create a tarball from a package

```bash
npm pack
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
