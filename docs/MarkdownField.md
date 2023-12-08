---
layout: default
title: The MarkdownField Component
DateStarted: 2023-12-08
DateModified: 2023-12-08
---

# `<MarkdownField>`

This [Enterprise Edition](https://marmelab.com/ra-enterprise)<img class="icon" src="./img/premium.svg" /> component allows to render Markdown data as HTML.

```jsx
import { Show, SimpleShowLayout, TextField } from 'react-admin';
import { MarkdownField } from '@react-admin/ra-markdown';

const PostShow = () => (
    <Show>
        <SimpleShowLayout>
            <TextField source="title" />
            <MarkdownField source="description" />
        </SimpleShowLayout>
    </Show>
);
```

Check [the `ra-markdown` documentation](https://marmelab.com/ra-enterprise/modules/ra-markdown) for more details.
