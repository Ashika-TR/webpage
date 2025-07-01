# webpage

```
<!DOCTYPE html>
<html>
<head>
    <title>Inline vs Block Elements</title>
    <style>
        .block {
            background-color: lightblue;
            padding: 10px;
            margin-bottom: 10px;
        }
        .inline {
            background-color: lightgreen;
            padding: 5px;
        }
    </style>
</head>
<body>

    <h1>Block and Inline Elements Example</h1>

    <!-- Block Elements -->
    <div class="block">This is a &lt;div&gt; element (block-level)</div>
    <p class="block">This is a &lt;p&gt; paragraph (block-level)</p>
    <h2 class="block">This is a &lt;h2&gt; heading (block-level)</h2>

    <!-- Inline Elements inside a paragraph -->
    <p>This is a paragraph with <span class="inline">a span</span> inside it and <b class="inline">bold text</b>.</p>

    <!-- Comparison -->
    <p><b>div</b> starts on a new line and takes full width (block).</p>
    <p><b>span</b> stays inside the line and wraps only the content (inline).</p>

</body>
</html>
```


## OUTPUT:

![Screenshot 2025-07-01 152825](https://github.com/user-attachments/assets/05a87d50-3b95-475a-ad8d-31c5aa625918)

```
