# element.min.js
Simple element maker using Minified JavaScript.
Only used to learn CDNJS.

Using:
- **Including the library**:
  First, include the libary in your HTML script using:
  ```html
  <script src="https://cdnjs.cloudflare.com/ajax/libs/element/1.0.0/element.min.js">
- **setup()**:
  Second, use the ``setup()`` function in your HTML.
  ```html
  <script>
    setup(
        type = 'a',
        id = 'test',
        text = 'Hello World',
        href = 'https://www.google.com'
    )
  </script>
- **Run**:
  Third, run the script.
- You should see this:
  <a href="https://www.google.com" id="test">Hello World</a>
