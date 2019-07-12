
```text
<project-root>
├── contrib
├── examples
|  └── realize-product-catalogue
|     └── src
└── packages
|  ├── realize-core
|  |  └── src
|  ├── realize-renderer-react
|  |  └── src
|  ├── realize-theme-materialui
|  |  └── src
|  └── realize-theme-react-bootstrap
|     └── src
```

### Package Types

#### Core Package

Implements shared logic between renderers.

#### Renderer Package

Defines the component's interface for a specific framework. Implements base components for theme implementation.

#### Theme Package

Implements all components defined by renderer package.
