<html>
<head>
<title> Hay Cantik </title>

<script type="text/javascript">
flag=1
function f1()
{
    alert("Thanks Udah pilih Jawaban YA")
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
<h1> there's something i want to say <h1>
<img alt="EvilicaCell" src="https://www.icegif.com/wp-content/uploads/icegif-4798.gif" height="200" />
<h1 style="#">do you want to be my girlfriend?</h1>
<div id="By" style="position:absolute; left:64px; top:370px; width:210px;
height:210px;">
<input type="button" value=" YA " onClick="f1()" />
</div>
<div ID="Bn" style="position:absolute; left:166px; top:370px; width:210px; height:210px;">
<input type="button" value=" TIDAK " onMouseOver="f()" />
</div>

    </body>
</html>
