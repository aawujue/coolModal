# coolModal
create cool modal plugin

This plugin is used to add some beautiful modal effects into your web page , and this is a developing project

I want someone's help to develop this project together

 you can use your imagination, create any cool effects by adding class in "coolModal.css". By the way, my code is not so good, you can edit it if you think you can code better.
 
 # the example to use this plugin
 
 ```
 <div id="content">
		<h1>Look at me!</h1>
		<p>I'm a modal window.</p>
		<input></input>
	</div>
	
<script type="text/javascript">
	var myContent = document.getElementById('content');
		var myModal = new Modal({
		  autoOpen: false,
      className: 'fade-and-drop',
      closeButton: true,//whether add close Button, true -- add ,  false -- remove
      content: mycontent, //main content
      maxWidth: 600,
      minWidth: 280,
      overlay: true //open or close overlay
		});
		myModal.open();
</script>

