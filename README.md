emmet.js
===

 A simplistic DOM Manipulation JavaScript library.
 This library is heavily inspired by [emmet.io](http://http://emmet.io/).


```html
    <script>
	    var sting = 'div#id.class>p>span{Text}+a[href=#]^section*2'
        emmet.render(sting).append();
        
     </script>
     
    
    <div id="id" class="class">
        <p>
    	  <span>Text</span>
    	  <a href="#"></a>
    	</p>
    	<section></section>
    	<section></section>
    </div>
