<!DOCTYPE html>
<html>
<head>
<title> Click me </title>

<script type="text/javascript">
flag=1
function f1()
{
    alert("Sabi ko na eh.")
}
function f()
{
    if(flag==1)
        {
            Bn.style.top=400
            Bn.style.left=300
            flag=2
        }
    else if(flag==2)
        {
            Bn.style.top=400
            Bn.style.left=50
            flag=3
        }
    else if(flag==3)
        {
            Bn.style.top=370
            Bn.style.left=166
            flag=1
        }
}
</script>

</head>
<body>
<h1>  <h1>
<img src="https://i0.wp.com/media.tenor.com/images/83d6a5ed40a24164dfe1e4e19fad23d9/tenor.gif" height="200" />
<h1 style="#">Crush mo ko?</h1>
<div id="By" style="position:absolute; left:64px; top:370px; width:210px;
height:210px;">
<input type="button" value=" Oo " onClick="f1()" />
</div>
<div ID="Bn" style="position:absolute; left:166px; top:370px; width:210px; height:210px;">
<input type="button" value=" Hindi " onMouseOver="f()" />
</div>

</body>
</html>
