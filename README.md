# SergioMann

# Algunas definiciones  
## Este es un repositorio de prueba con MD.  
## Que deberíamos ver?

- Definición del repositorio
- Información adicional importante



Algo de metadata

```md title="docs/hello.md" {1-4}
---
sidebar_label: 'Hi!'
sidebar_position: 3
---

# Hello

This is my **first document**!
```

Algunas tareas

- [x] Tarea 1 
- [ ] Tarea 2 
- [ ] Tarea 3 
- [x] Tarea 4 
- [x] Tarea 5 
- [ ] Tarea 6 
- [x] Tarea 7 


## Create your first React Page

Create a file at `src/pages/my-react-page.js`:

```jsx title="src/pages/my-react-page.js"
import React from 'react';
import Layout from '@theme/Layout';

export default function MyReactPage() {
  return (
    <Layout>
      <h1>My React page</h1>
      <p>This is a React page</p>
    </Layout>
  );
}
```

The static files are generated in the `build` folder.
