<!DOCTYPE html>
<html>

<body>
    <h1 id="item"></h1>
    <script type="text/javascript">
        (function () {
            const items = ["TA", "CBT"];
            var selected = items[Math.floor(Math.random() * items.length)];
            document.getElementById("item").innerHTML = selected;
        })();
    </script>
</body>

</html>
