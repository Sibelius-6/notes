<script>
var location = window.location;
if (
       location.hostname == "notes.sibeliusp.com"
    && location.pathname.indexOf("/pdf") == 0
) {
    location.replace("https://pdf.sibeliusp.com");
}
</script>