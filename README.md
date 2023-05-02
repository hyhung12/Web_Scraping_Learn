# Web_Scraping_Learn

```
$("h1").text()
```
-Table
```
<table>
<tr> (table row)
<th> (table header)
<td> (table data)
```
```
$("body > table > tbody > tr").each((index, element) => {
console.log($(element).text())  });
