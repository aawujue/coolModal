# coolModal
create cool modal plugin

This plugin is used to add some beautiful modal effects into your web page , and this is a developing project

I want someone's help to develop this project together

 you can use your imagination, create any cool effects by adding class in "coolModal.css". By the way, my code is not so good, you can edit it if you think you can code better.
 
## the example to use this plugin
just copy the following code and you will see result 
 ```
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<link rel="stylesheet" type="text/css" href="coolModal.css">
</head>
<body>	
	<script type="text/javascript" src="coolModal.js"></script>
	<script type="text/javascript">
        var myModal = new Modal({
          autoOpen: false,
	      className: 'fade-and-drop',
	      closeButton: true,//whether add close Button, true -- add ,  false -- remove
	      content: '<div id="content"><h1>Hello!</h1><p> a modal window.</p></div>', //main content
	      maxWidth: 600,
	      minWidth: 280,
	      overlay: true //open or close overlay
        });
        myModal.open();
</script>
</body>
</html>

