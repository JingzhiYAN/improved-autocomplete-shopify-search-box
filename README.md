# improved-autocomplete-shopify-search-box
This is a improved version of shopify search box autocomplete function.
Based on shopify's original version.
Solved the problem: when your titles are all very long and cannot be desplayed inside the box.
Some of them even just disappeared by line.

How to:<br></br>
1.Put search-autocomplete.liquid into the Snippets folder in Edit HTML/CSS page.<br></br>
2.Put search.json.liquid into the template folder in Edit HTML/CSS page.<br></br>
3.Add <br></br>
{% include 'search-autocomplete' %}<br></br>

at the bottom of file theme.liquid.<br></br>
NB: This line should be added above the "\</body>\".

You are done now. Enjoy your work!
