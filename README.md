# practiceFlexBox

#part 1 (بخش اول فلکس باکس)
<!DOCTYPE html>
<html>
<body>
<style>
body{
background:lightblue;
padding:0;
margin:0;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
}
.container{
background:teal;
width:260px;
height:100vh;
display:flex;
justify-content:start;
align-items:start;
flex-direction:column

}

.container > div {width:100%}
.content {
background:#62d115;
flex:.7
}
.header , .footer {
background:gold;
flex:.15
}
.header{display:flex}
.header > div{
display:flex;
justify-content:center;
align-items:center
}
.pic{
background:dodgerblue;;padding:10px;border-radius:50px;
color:white
}
.headerTitle{
display:flex;
justify-content:center;
align-items:center;
flex:0.7


}
.headerTitle > span{

background:dodgerblue;
padding:5px 10px;
color:white
}
</style>

<div class="container">

    <div class="header">
    	<div style=";flex:0.3">
        <div class="pic">pic</div>
        </div>
        <div class="headerTitle" >
        <span>alireza</span>
        <span>anvari</span>
        </div>
    </div>
    <div class="content">header</div>
    <div class="footer">header</div>

</div>


</body>
</html> 
