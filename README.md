emmet
===

 A simplistic DOM Manipulation JavaScript library heavily inspired by [emmet.io](http://www.emmet.io/).

 This piece of code
  ``` <script>
	var sting = 'div#id.class>p>span{Text}+a[href=#]^section*2'
        emmet.render(sting).append();
     </script>
  ```
  
  ...will produce.
  ![contributors](http://i42.photobucket.com/albums/e316/tanasiliev/Apps/crossword_zps609ca8eb.png)
  
  ```
    <div id="id" class="class">
        <p>
    	  <span>Text</span>
    	  <a href="#"></a>
    	</p>
    	<section></section>
    	<section></section>
    </div>

    
  
