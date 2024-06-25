# Wallet Management System

...

## Example Code Snippet

Below is an example code snippet with a "copy" button:

```html
<div>
  <pre>
    <code>
      const example = 'Hello, World!';
      console.log(example);
    </code>
  </pre>
  <button onclick="copyToClipboard()">Copy</button>
</div>

<script>
  function copyToClipboard() {
    const code = document.querySelector('pre code').innerText;
    navigator.clipboard.writeText(code).then(() => {
      alert('Copied to clipboard');
    }).catch(err => {
      console.error('Failed to copy: ', err);
    });
  }
</script>
