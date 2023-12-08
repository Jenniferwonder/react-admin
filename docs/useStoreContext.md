---
layout: default
title: useStoreContext
DateStarted: 2023-12-08
DateModified: 2023-12-08
---

# `useStoreContext`

This hook allows to access the global [Store](./Store.md).

It should not be used directly. Prefer the specialized hooks (`useStore`, `useResetStore`, `useRemoveFromStore`) instead.

## Syntax

```jsx
import { useStoreContext } from 'react-admin';

const store = useStoreContext();
```
