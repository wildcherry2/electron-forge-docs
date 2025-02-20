# Vite + TypeScript

To get you up and running as fast as possible with [TypeScript](https://www.typescriptlang.org/) and [Vite](https://vitejs.dev/), we provide a template that makes use of the [`@electron-forge/plugin-vite` module](../config/plugins/vite.md) with sane TypeScript configuration defaults.

{% tabs %}
{% tab title="Yarn" %}
```bash
yarn create electron-app my-new-app --template=vite-typescript
```
{% endtab %}

{% tab title="npm" %}
```bash
npm init electron-app@latest my-new-app -- --template=vite-typescript
```
{% endtab %}
{% endtabs %}

Once you've initialized the template, you'll need to run `npm start` in the generated directory.

See the [Vite Plugin](../config/plugins/vite.md) documentation for Electron Forge-specific configuration options.
