<script>
    const time_element = document.getElementById('time')
    setInterval(function() {time_element.innerHTML = Date().split('(')[0].trim()}, 1000)
</script>
