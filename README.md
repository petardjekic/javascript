# javascript
<html>
<head>
<title>Dogadjaji sa misem</title>
<SCRIPT LANGUAGE="JavaScript">
alert("Before ActiveX");
    var obj =new ActiveXObject("c:\temp\hellworld.dll");// dll name is JSDll, class: CoTest,it'll got from //regedit repositry
    alert("After ActiveX");
    alert(obj.SampleMethod());// This is VC++ COM DLL Method
    alert("After Method");// This Alert box Not Exceuting
    //alert(vResult);
    }catch(e) {
    if(e.message == "Automation server can't create object")
        alert("myproject value in javascript "+vResult);
</SCRIPT>
 </head>
 <body>
 <FORM METHOD="post" NAME="mojaforma">
X &nbsp; = &nbsp;
<INPUT TYPE="text" NAME="X" SIZE=5> <br>
Y &nbsp; = &nbsp;
<INPUT TYPE="text" NAME="Y" SIZE=5> <br><br>
<INPUT TYPE="button" VALUE="SABERI"
NAME="dugme" onClick="Saberi()"> <br><br>
<hr>
REZULTAT &nbsp; = &nbsp;
<INPUT TYPE="text" NAME="zbir" SIZE=5> <br>
</FORM>

 </body>
 </html>
