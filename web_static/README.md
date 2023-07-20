<div align="center">

# AirBnB Clone - Web Static

</div>

<div align="center">
  <img src="https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/9/939d6b9448e63776610d05d2226aa8985209ee4d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230720%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230720T181940Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=941495cd2d4186dd818c67a8c243951976f47c479e736640e0670290e7a0a7e3" alt="AirBnB Clone Screenshot">
</div>

This project focuses on creating an HTML page that displays a header and a footer using inline styling. The header should be colored red (#FF0000), have a height of 70px, and a width of 100%. The footer should be colored green (#00FF00), have a height of 60px, and a width of 100%. The text "Holberton School" in the footer should be centered both vertically and horizontally, and it should always appear at the bottom of the page.

## HTML Code

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Inline Styling - Header and Footer</title>
</head>

<body style="margin: 0; padding: 0;">

  <header style="background-color: #FF0000; height: 70px; width: 100%;"></header>

  <footer style="background-color: #00FF00; height: 60px; width: 100%; display: flex; align-items: center; justify-content: center; position: fixed; bottom: 0;">
    Holberton School
  </footer>

</body>

</html>
```

## Description

The provided HTML file displays a simple web page with a header and a footer. The body has no margin and no padding. The header and footer are styled using inline CSS to achieve the specified requirements.

## Requirements

- Use the `<header>` and `<footer>` tags for the header and footer, respectively.
- Do not import any external files.
- Do not use the `<style>` tag within the `<head>` tag.
- Apply inline styling for all elements to set their styles.
- Center the text "Holberton School" in the footer both vertically and horizontally.
- Ensure that the footer always appears at the bottom of the page using the `position: fixed; bottom: 0;` CSS properties.
- Verify that the header has a red background (#FF0000), a height of 70px, and a width of 100%.
- Verify that the footer has a green background (#00FF00), a height of 60px, and a width of 100%.