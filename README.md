<html>
    <head>
        <title>calculator</title>    
    </head>
    <body bgcolor="#FF297A">
        <center><br>
            <h1><B><font color="white" style="Font-size:50">CALCULATOR</font></B></h1>
        <form name="calculator">
            <input name="display" placeholder="0" style="text-align:right; height:40px; width:254px; font-size:30; border-radius:8px; margin:3px">
            <br>
            <input type="button" value="7" onclick="document.calculator.display.value+='7'" style="height:60px; width:60px; font-size:30; border-radius:8px; margin:3px">
            <input type="button" value="8" onclick="document.calculator.display.value+='8'" style="height:60px; width:60px; font-size:30; border-radius:8px">
            <input type="button" value="9" onclick="document.calculator.display.value+='9'" style="height:60px; width:60px; font-size:30; border-radius:8px">
            <input type="button" value="+" onclick="btnplus()" style="height:60px; width:60px; font-size:30; border-radius:8px">
            <br>
            <input type="button" value="4" onclick="document.calculator.display.value+='4'" style="height:60px; width:60px; font-size:30; border-radius:8px; margin:3px">
            <input type="button" value="5" onclick="document.calculator.display.value+='5'" style="height:60px; width:60px; font-size:30; border-radius:8px">
            <input type="button" value="6" onclick="document.calculator.display.value+='6'" style="height:60px; width:60px; font-size:30; border-radius:8px">
            <input type="button" value="-" onclick="btnsub()" style="height:60px; width:60px; font-size:30; border-radius:8px">
            <br>
            <input type="button" value="1" onclick="document.calculator.display.value+='1'" style="height:60px; width:60px; font-size:30; border-radius:8px; margin:3px">
            <input type="button" value="2" onclick="document.calculator.display.value+='2'" style="height:60px; width:60px; font-size:30; border-radius:8px">
            <input type="button" value="3" onclick="document.calculator.display.value+='3'" style="height:60px; width:60px; font-size:30; border-radius:8px">
            <input type="button" value="*" onclick="btnmul()" style="height:60px; width:60px; font-size:30; border-radius:8px">
            <br>
            <input type="button" value="0" onclick="document.calculator.display.value+='0'" style="height:60px; width:60px; font-size:30; border-radius:8px; margin:3px">
            <input type="button" value="%" onclick="btnmod()"style="height:60px; width:60px; font-size:30; border-radius:8px">
            <input type="button" value="." onclick="btndot()" style="height:60px; width:60px; font-size:30; border-radius:8px">
            <input type="button" value="/" onclick="btndiv()" style="height:60px; width:60px; font-size:30; border-radius:8px">
            <br>

            <input type="button" value="=" onclick="document.calculator.display.value=eval(document.calculator.display.value)" style="height:60px; width:124px; font-size:30; border-radius:8px; margin:3px">

            <input type="button" value="C" onclick="btnclear()" style="height:60px; width:124px; font-size:30; border-radius:8px">
        </form>
        <script>
            function btnplus()
                {
                    document.calculator.display.value+="+";
                    document.calculator.display.style.textAlign="right";
                }
            function btnsub()
                {
                    document.calculator.display.value+="-";
                    document.calculator.display.style.textAlign="right";
                }
            function btnmul()
                {
                    document.calculator.display.value+="*";
                    document.calculator.display.style.textAlign="right";
                }
            function btnmod()
                {
                    document.calculator.display.value+="%";
                    document.calculator.display.style.textAlign="right";
                }
            function btndot()
                {
                    document.calculator.display.value+=".";
                    document.calculator.display.style.textAlign="right";
                }
            function btndiv()
                {
                    document.calculator.display.value+="/";
                    document.calculator.display.style.textAlign="right";
                }
            function btnclear()
                {
                    document.calculator.display.value="";
                    document.calculator.display.style.textAlign="right";
                }
            
        </script>
        
        </center>
        
    </body>
</html>
