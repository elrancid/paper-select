### WARNING! This is an early alpha test! Do not use!

##&lt;paper-select&gt;

Material design: [Text fields](https://www.google.com/design/spec/components/text-fields.html)

`<paper-select>` is like a browse select field with Material Design styling.

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-select.html">
    <link rel="import" href="../iron-icons/iron-icons.html">
    <style>
      paper-select {
        max-width: 400px;
        margin: auto;
      }
      iron-icon, div[suffix] {
        color: hsl(0, 0%, 50%);
        margin-right: 12px;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-select always-float-label label="Floating label"></paper-select>
<paper-select label="username">
  <iron-icon icon="mail" prefix></iron-icon>
  <div suffix>@email.com</div>
</paper-select>
```
