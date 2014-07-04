<h1>Multi-Column-Select</h1>

<p>Jquery CSS Multi Column Select Box</p>


<h2>Tested on:</h2>
<ul>
<li>IE7+</li>
<li>Safari</li>
<li>Firefox </li>
<li>Chrome</li>
</ul>


<h2>Installation</h2>
<pre>

<!-- Stylesheet-->
link rel="stylesheet" href="MultiColumnSelect/MultiColumnSelect.css"

<!-- Include js plugin -->
script src="MultiColumnSelect/MultiColumnSelect.js"

</pre>

<h2>Set up your HTML</h2>

<div class="selectcontrol">
        <select name="car">
          <option value="a">A</option>
          <option value="b">B</option>
          <option value="c">C</option>
          <option value="d">D</option>
          <option value="e">E</option>
          <option value="f">F</option>
          <option value="a">A</option>
          <option value="b">B</option>
          <option value="c">C</option>
        </select>
</div>

Wrap the select control with a div and give that container an ID or class

<h2>Call the plugin</h2>

$(".selectcontrol").MultiColumnSelect({

            menuclass : 'columnselect',
            openmenu : 'openmenubutton',
            openmenutext : 'Choose An Option',
            menucontainer : 'menucontainer',
            menuitem : 'menuitem',
            hideclass : 'hidden',
            openclass : 'open',
            clearclass : 'clear',
            duration : 200

});

