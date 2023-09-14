---
myst:
    substitutions:
        "key4": |
            ```{image} _static/img/search01.png
            :alt: rivt-search logo
            :target: https://github.com/search
            :width: 50px
            ```
---

# {{ key4 }} **rivt-search** 

<head>
<style>
.button {
  background-color: #cfdde2; 
  border: 3 px solid black;
  color: black;
  padding: 10px 20px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}
</style>

<script> function searchRivt(){var strng1 = document.getElementById("terms"); var strng2 = document.getElementById("terms").value;URL = `https://github.com/search?q=rivt+${strng2}+in%3Areadme`;window.open(URL,'_self')};document.addEventListener("keydown", function(e) {if ((e.keyCode == 10 || e.keyCode == 13) && e.ctrlKey){document.getElementById("searchBtn").click();}});
</script>

<script> function searchOrg(){var strng1 = document.getElementById("terms");var strng2 = document.getElementById("terms").value;URL = `https://github.com/search?q=rivt+${strng2}+in%3Areadme`;window.open(URL,'_self')};document.addEventListener("keydown", function(e) {if ((e.keyCode == 10 || e.keyCode == 13) && e.ctrlKey){document.getElementById("searchBtn").click();}});
</script>

</head>

<hr>

## GitHub
<hr>

Full text **rivt** document search across README files

Enter search terms separated by a + sign

Example: concrete+beam+bridge  [**rivt** term is inserted by the search function]

<input type="text" id="terms" name="terms" size=60 style="height:40px;font-size:14pt; font-weight: bold"><br>

[ctrl+R or F5] to clear search terms

<button class="button" id="searchBtn" onclick="searchRivt()">Search [ ctrl+enter ]</button>

<hr>

## GitHub Organization
<hr>

Search within a GitHub organization

<input type="text" id="terms" name="terms" size=30 style="height:40px;font-size:14pt; font-weight: bold"> Enter Organization<br>


<input type="text" id="terms" name="terms" size=60 style="height:40px;font-size:14pt; font-weight: bold"> Search Terms<br>

<button class="button" id="searchBtn" onclick="searchOrg()">Search [ ctrl+enter ]</button>

