# Copyright Demo

There are many solutions for displaying copyright text in your website footer. These three are the most common.

### Using only HTML:

```html
<span>Copyright © 2017 Gregor Laan. All rights reserved.</span>
```

### Using HTML and Vanilla Javascript:

```html
<span>Copyright © <script>document.write(new Date().getFullYear())</script> Gregor Laan. All rights reserved.</span>
```

### Using HTML and PHP:

```html
<span>Copyright © <?php echo date("Y"); ?> Gregor Laan. All rights reserved.</span>
```

### Preview
<span>Copyright © 2017 Gregor Laan. All rights reserved.</span>
