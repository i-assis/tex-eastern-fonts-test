# <span style="background-color: #FFFF00">React Sequential Snippets</span>

<html>
<style>
body {
  background-image: url(http://absfreepic.com/absolutely_free_photos/small_photos/green-grass-football-lawn-4020x2261_98957.jpg);
  background-color: #4E4F50
}
h3 {
  margin: auto;
  text-align: center;
  padding: 10px;
  color: 	#F8F8F8;
}
.table {
  background-color: #F8F8F8;
  margin: auto;
  width: 750px;
  border-collapse: separate;
  display: block;
  overflow-x: scroll;
}
thead,
tbody {
  display: inline-block;
}
thead {
  position: sticky;
  top: 1px;
  z-index: 9999;
}
tbody {
  height: 400px;
}
th {
  background-color: #32cd32;  
}
td,
th {
  min-width: 150px;
  max-width: 250px;
  word-wrap: break-word;
}
.fixed {
  position: sticky;
  width: 5em;
  left: 0;
  top: auto;
  z-index: 999;
  background-color: #99FF66;
}
.fixedcorner {
  position: sticky;
  width: 5em;
  left: 0;
  top: auto;
  z-index: 999;
  background-color: #145214;
}
td:not(.fixed) {
  z-index: 0;
}
</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet" />
<div class="conatiner">
  <table class="table table-bordered">
    <thead>
      <tr>
        <th class="fixedcorner"></th>
        <th colspan="6" style="text-align:center">Tipo de Operação</th>
      </tr>
      <tr>
        <th style="text-align:center">Step #</th>
        <th style="text-align:center">Where</th>
        <th style="text-align:center">Code or Command</th>
        <th style="text-align:center">Code or Command</th>
        <th style="text-align:center">Exibir</th>
        <th style="text-align:center">Excluir</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th class="fixed">#0001</th>
        <td><button>command line</button></td>
        <td><button class="btn btn-secondary fs-2">rails new crypto_wallet</button></td>
        <td><button class="btn btn-secondary fs-2">super</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button> <br /> <button class="btn btn-secondary fs-2">colaborador</button></td>
        <td> </td>        
      </tr>
      <tr>
        <th class="fixed">#0002</th>
        <td><button class="btn btn-secondary fs-2">super</button></td>
        <td><button class="btn btn-secondary fs-2">super</button></td>
        <td><button class="btn btn-secondary fs-2">super</button></td>
        <td><button class="btn btn-secondary fs-2">super</button></td>
        <td><button class="btn btn-secondary fs-2">super</button></td>        
      </tr>
      <tr>
        <th class="fixed">#0003</th>
        <td><button class="btn btn-secondary fs-2">super</button></td>
        <td><button class="btn btn-secondary fs-2">super</button></td>
        <td><button class="btn btn-secondary fs-2">super</button></td>
        <td><button class="btn btn-secondary fs-2">super</button></td>
        <td><button class="btn btn-secondary fs-2">super</button></td>        
      </tr>
      <tr>
        <th class="fixed">#0004</th>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button> <br /> <button class="btn btn-secondary fs-2">colaborador</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button></td>        
      </tr>
      <tr>
        <th class="fixed">Unidades</th>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button> <br /> <button class="btn btn-secondary fs-2">colaborador</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button> <br /> <button class="btn btn-secondary fs-2">colaborador</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button></td>
      </tr>
      <tr>
        <th class="fixed">Clientes</th>
        <td>Mangabeira</td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button> <br /> <button class="btn btn-secondary fs-2">colaborador</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button> <br /> <button class="btn btn-secondary fs-2">colaborador</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button> <br /> <button class="btn btn-secondary fs-2">colaborador</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button> </td>       
      </tr>
      <tr>
        <th class="fixed">Personalização</th>
        <td> </td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button> <br /> <button class="btn btn-secondary fs-2">colaborador</button> </td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button> <br /> <button class="btn btn-secondary fs-2">colaborador</button> <br /> <button class="btn btn-secondary fs-2">cliente</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button> <br /> <button class="btn btn-secondary fs-2">colaborador</button> <br /> <button class="btn btn-secondary fs-2">cliente</button></td>
        <td><button class="btn btn-secondary fs-2">super</button></td>
      </tr>
      <tr>
        <th class="fixed"> 9 </th>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button> <br /> <button class="btn btn-secondary fs-2">colaborador</button> <br /> <button class="btn btn-secondary fs-2">cliente</button></td>
        <td><button class="btn btn-secondary fs-2">super</button></td>        
      </tr>
      <tr>
        <th class="fixed"> 10 </th>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button></td>
        <td><button class="btn btn-secondary fs-2">super</button> <br /> <button class="btn btn-secondary fs-2">admin</button> <br /> <button class="btn btn-secondary fs-2">colaborador</button> <br /> <button class="btn btn-secondary fs-2">cliente</button></td>
        <td><button class="btn btn-secondary fs-2">super</button></td>        
      </tr>      
    </tbody>
  </table>
</div>
</html>

&nbsp;

<span style="background-color: #FFFF00">Snipett S0001:</span>

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

&nbsp; <span style="background-color: #FFFF00">Snipett S0002:</span>

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

&nbsp; <span style="background-color:  #FFFF00">Snipett S0003:</span>

```ruby
def index
  puts "hello world"
end
```
