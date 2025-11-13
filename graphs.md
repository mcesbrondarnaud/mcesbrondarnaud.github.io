---
layout: page
title: Interactive Graphs
---

Here’s where the interactive visualizations will appear.

<canvas id="myChart"></canvas>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctx = document.getElementById('myChart');
const myChart = new Chart(ctx, {
    type: 'line',
    data: {
        labels: ['Jan','Feb','Mar','Apr','May'],
        datasets: [{
            label: 'Example data',
            data: [10,20,5,30,15],
            borderWidth: 2
        }]
    }
});
</script>
