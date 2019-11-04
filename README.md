# ember-monaco

This is a fork of [ember-monaco](https://github.com/mike-north/ember-monaco), used for prototyping purposes only.

Changes made:

- The `{{code-editor}}` component can take a `readOnly: true` argument. This has an upstream PR.
- The `monaco.editor` is exposed as a second param in `editorReady`. This is a hack.

## License

This project is licensed under the [BSD-2-Clause](LICENSE.md).

## Thanks

Thanks to @MiguelMadero for writing [ember-monaco-editor](https://github.com/MiguelMadero/ember-monaco-editor), which served as a starting point for this work
