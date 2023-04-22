<script>
    let radius = 10;
    function calc_circ(radius) {
        circ = radius * 2 * 3.14
        return Math.round(circ, 2);
    }
</script>
The circumference of a circle with radius {radius}m is {calc_circ(radius)}m