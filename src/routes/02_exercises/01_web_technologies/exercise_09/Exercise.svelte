<script>
    let radius = 10;
    const calc_circ = (radius) => {
        let circ = radius * 2 * 3.14;
        return (circ.toFixed(2));
    }
</script>
The circumference of a circle with radius {radius}m is {calc_circ(radius)}m