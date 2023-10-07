<!DOCTYPE html>
<html>

<head>

  <title>replit</title>


  <style>
    #table_head {

      background-color: yellow;
      text-align: center;
      margin: 20px auto 0 auto;
      max-width: 500px;
      padding: 10px;
      color: red;
      width: 100%;
      transform: rotate(0deg);
    }


    .table-list {
      border-collapse: collapse;
      margin: 20px 600px;
      font-size: 1em;
      min-width: 300px;

      border-radius: 5px 5px 0 0;
      overflow: hidden;
      padding: 30px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
    }

    .table-list thead tr {
      background-color: seagreen;
      color: white;
      text-align: left;
      font-weight: bold;


    }

    .table-list th,
    .table-list td {
      padding: 12px 15px;

    }

    .table-list tbody tr {
      border-bottom: 1px solid lightslategray;
    }

    .table-list tr:last-of-type(even) {
      background-color: lightgray;
    }

    .table-list tr:last-of-type {
      border-bottom: 2px solid seagreen;
    }

    .table-list tr.active-row {
      font-weight: bold;
      color: seagreen;
    }


    tr {
      cursor: pointer;
    }



    tr:hover {
      background-color: lightgray;
    }
  </style>
</head>

<body>
  <h1 id="table_head">Table for css</h1>
  <br>
  <table class="table-list">
    <thead class="table-list thead">


      <tr class="" active-row>
        <th>s1.no</th>
        <th>name</th>
        <th>phone</th>

      </tr>
    </thead>


    <tr class="active-row">
      <td>1</td>
      <td>Shree</td>
      <td>2486267</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Shrinath</td>
      <td>2843247</td>
    <tr class="active-row">
      <td>3</td>
      <td>Shrihari</td>
      <td>2543247</td>
    </tr>

    <tr>
      <td>4</td>
      <td>Hari</td>
      <td>6786766</td>

    </tr>
  </table>

</body>

</html>
