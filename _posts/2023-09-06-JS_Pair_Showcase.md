---
layout: post
title: JS Table
courses: { compsci: {week: 3} }
type: hacks
---
<br> <br> <br> <br> <br>

## JS Output with Jquery

<br>

<!-- Head contains information to Support the Document -->
<head>
    <!-- load jQuery and DataTables output style and scripts -->
    <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.13.4/css/jquery.dataTables.min.css">
    <script type="text/javascript" language="javascript" src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script>var define = null;</script>
    <script type="text/javascript" language="javascript" src="https://cdn.datatables.net/1.13.4/js/jquery.dataTables.min.js"></script>
</head>

<!-- Body contains the contents of the Document -->
<body>
    <table id="table3" class="table">
        <thead>
            <tr>
                <th>Number</th>
                <th>Building Name</th>
                <th>Location</th>
                <th>Height (ft)</th>
                <th>Year Built</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Burj Khalifa</td>
                <td>Dubai, UAE</td>
                <td>2717</td>
                <td>2010</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Merdeka 118</td>
                <td>Kuala Lumpur, Malaysia</td>
                <td>2227</td>
                <td>2023</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Shanghai Tower</td>
                <td>Shanghai, China</td>
                <td>2073</td>
                <td>2015</td>
            </tr>
            <tr>
                <td>4</td>
                <td>Abraj Al Bait Clock Tower</td>
                <td>Mecca, Saudi Arabia</td>
                <td>1972</td>
                <td>2012</td>
            </tr>
            <tr>
                <td>5</td>
                <td>Ping An Finance Center</td>
                <td>Shenzhen, China</td>
                <td>1965</td>
                <td>2017</td>
            </tr>
            <tr>
                <td>6</td>
                <td>Lotte World Tower</td>
                <td>Seoul, South Korea</td>
                <td>1821</td>
                <td>2017</td>
            </tr>
            <tr>
                <td>7</td>
                <td>One World Trade Center</td>
                <td>New York City, USA</td>
                <td>12.011</td>
                <td>3750 BC</td>
            </tr>
            <tr>
                <td>8</td>
                <td>Guangzhou CTF Finance Centre</td>
                <td>Guangzhou, China</td>
                <td>1739</td>
                <td>2016</td>
            </tr>
            <tr>
                <td>9</td>
                <td>Tianjin CTF Finane Centre</td>
                <td>Tianjin, China</td>
                <td>1739</td>
                <td>2019</td>
            </tr>
            <tr>
                <td>10</td>
                <td>CITIC Tower</td>
                <td>Beijing, China</td>
                <td>1732</td>
                <td>2018</td>
            </tr>
            <tr>
                <td>11</td>
                <td>Taipei 101</td>
                <td>Taipei, Taiwan</td>
                <td>1667</td>
                <td>2004</td>
            </tr>
        </tbody>
    </table>
</body>

<!-- Script is used to embed executable code -->
<script>
    $("#table3").DataTable();
</script>