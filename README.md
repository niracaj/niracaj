<!DOCTYPE html>
<html>
<head>
    <title>CaringForCardano.com</title>
    <script>
        function redirect() {
            const urlParams = new URLSearchParams(window.location.search);
            const paramValue = urlParams.get('page');

            if (paramValue === 'Carin') {
                window.location.href = 'http://192.171.13.139:3000';
            } else if (paramValue === '3DGames') {
                window.location.href = 'http://192.171.13.139:3009/explore&room=Room1&from=Main';
            } else if (paramValue === 'Glock2021') {
                window.location.href = 'http://192.171.13.139:3000/PrintingPage';
            } else if (paramValue === 'PrintingPage') {
                window.location.href = 'http://192.171.13.139:3000/PrintingPage';
            } else {
                window.location.href = 'http://192.171.13.139:3000';
            }
        }

        window.onload = redirect;
    </script>
</head>
<body>
    </body>
</html>
