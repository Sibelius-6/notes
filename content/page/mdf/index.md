<script>
var location = window.location;
if (
       location.hostname == "notes.sibeliusp.com"
    && location.pathname.indexOf("/mdf") == 0
) {
    location.replace("https://mdf.sibeliusp.com");
}
</script>