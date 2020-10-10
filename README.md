<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="pl" lang="pl"> 

<head> 

<meta http-equiv="Content-Type" content="text/html; charset="iso-8859-2" />

<meta name="Description" content="Opis Twojej strony dla wyszukiwarek" /> 

<link rel="shortcut icon" type="image/png" href="icon.png">

<title>PeepoHappy</title> 

<link rel="stylesheet" type="text/css" href="css.css">

</head> 

<body style="background-color:#0e0e10">

<div id="text">
      <p style="color:#313134; font-family:Roobert; font-size:14px">
         by <a style="color:#313134; text-decoration:none" href="https://www.twitch.tv/kretynzz1" target="_blank"><b>kretynzz1</b></a>
      </p>
</div>

<div id="film">
<iframe 
	src="https://ebd.cda.pl/620x368/299996138" 
	width="100%" 
	height="100%" 
	style="border:none;" 
	scrolling="no" 
	allowfullscreen name="v2" 
	allow="encrypted-media"
></iframe>
</div>

<div id="chat">
<iframe 
	frameborder="0"
	theme="dark"
	scrolling="no"
	id="chat_embed"
	src="https://www.twitch.tv/embed/podrez_chat?parent=kretynzz.github.io"
	height="100%"
	width="350"
	align="right"
></iframe>
</div>

    <div id="twitch-embed"></div>
    <script src="https://embed.twitch.tv/embed/v1.js"></script>
    <script type="text/javascript">
      new Twitch.Embed("twitch-embed", {
        width: "100%",
        height: "100%",
		layout: "video",
		
        channel: "podrez_",
        parent: ["kretynzz.github.io"]
      });
    </script>

</body>

</html>
