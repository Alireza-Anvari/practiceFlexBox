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
    <div class="content">content</div>
    <div class="footer">content</div>

</div>


</body>
</html> 




# part 2 (بخش دوم فلکس باکس)
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
box-sizing: border-box;
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
flex:.7;
display:flex;
flex-direction:column;
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

.content > div{


background:white;
flex:.4;
display:flex;
column-gap:5px
}
.avatar{flex:.35;display:flex;
justify-content:center;
align-items:center;}
.avatar > div {
background:blue;
padding:20px;
border-radius:50px
}
.comment{flex:.75;display:flex;
justify-content:center;
align-items:start;flex-direction:column}
.comment>div {}
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
    <div class="content">
    <div >
    <div class="avatar">
    	 <div>pic</div>
    </div>
     <div class="comment">
     
     <div style="flex:.3;;width:100%;font-weight:bold">accountName : </div>
     <div style="flex:.5;width:100%"><span style="font-weight:bold">comment:</span> jksdhfkj kjsdhf k,jghsdf jks fsdbfjks ...</div>
     </div>
     </div>
   
  
    
    
    
    
    </div>
    <div class="footer">footer</div>

</div>


</body>
</html> 


