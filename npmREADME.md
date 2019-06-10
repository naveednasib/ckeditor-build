CKEditor 5 Custom Build Editor all version v1.0.4
========================================


## Quick start

First, install the build from npm:

```bash
npm install --save ckeditor5-build-all
```



use it in your ReactJs application:

```js

import CKEditor from '@ckeditor/ckeditor5-react'
import ClassicEditor from 'ckeditor5-build-all'

// Or using the CommonJS version:
// const ClassicEditor = require( '@ckeditor/ckeditor5-build-classic' );

 <CKEditor
                editor={ClassicEditor} {...this.props}
                config={{
                    fontSize: {
                        options: [
                            9,
                            11,
                            13,
                            'default',
                            17,
                            19,
                            21
                        ]
                    },
                    toolbar: ['heading', '|', 'bold', 'italic', 'link', 'blockQuote', 'numberedList', 'bulletedList', 'fontSize', 'undo', 'redo','fontColor','fontBackgroundColor', 'strikethrough','underline','insertTable', 'increaseIndention'],
                    heading: {
                        options: [
                            {model: 'paragraph', title: 'Paragraph', class: 'ck-heading_paragraph'},
                            {model: 'heading1', view: 'h1', title: 'Heading 1', class: 'ck-heading_heading1'},
                            {model: 'heading2', view: 'h2', title: 'Heading 2', class: 'ck-heading_heading2'},
                            {model: 'heading3', view: 'h3', title: 'Heading 3', class: 'ck-heading_heading3'},
                            {model: 'heading4', view: 'h3', title: 'Heading 4', class: 'ck-heading_heading4'},
                            {model: 'heading5', view: 'h4', title: 'Heading 5', class: 'ck-heading_heading5'},
                            {model: 'heading6', view: 'h6', title: 'Heading 6', class: 'ck-heading_heading6'},
                            {model: 'address', view: 'address', title: 'address', class: 'ck-address'}
                        ]
                    },
                    table: {
                        contentToolbar: [ 'tableColumn', 'tableRow', 'mergeTableCells' ]
                    }

                }}
            />
```

**Git Repo:**  Read more in the [Github](https://github.com/naveednasib/ckeditor-build).

## License

ISC
