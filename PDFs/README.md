<html>
  <body>
    <head>
<script src="jquery-3.5.1.min.js"></script>
</head>
    <script>
      (async () => {
        const response = await fetch('https://api.github.com/repos/Tracking-the-trackers/Tracking-the-trackers.github.io/contents/PDFs');
        const data = await response.json();
        let htmlString = '<ul>';
        for (let file of data) {
          htmlString += `<li><a href="${file.path}">${file.name}</a></li>`;
        }
        htmlString += '</ul>';
        document.getElementsByTagName('body')[0].innerHTML = htmlString;
      })()
    </script>
  <body>
</html>
