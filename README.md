# menu
<DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Breakfast, Lunch, and Dinner Menus</title>
<style>
.menu-container {
display: flex;
justify-content: center;
gap: 30px;
margin-top: 50px;
}
.menu {
width: 400px;
height: 550px;
color: #fff;
border-radius: 18px;
box-shadow: 0 6px 22px rgba(0,0,0,0.18);
padding: 35px 30px;
margin: 0 10px;
display: flex;
flex-direction: column;
align-items: flex-start;
}
.breakfast {
background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQhaAK8sRVCUPCl_M30Z8BYyztBLxdLz4bJmA&s');
background-size: cover;
background-repeat: no-repeat;          /* Unique property for breakfast */
background-position: center center;
}
.lunch {
background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTjuvQ3QecvAKKE-TUH4bsmUtg5b3Vv4GyF3w&s');
background-size: cover;
background-repeat: repeat-y;          /* Unique property for lunch */
background-position: left top;
}
.dinner {
background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSR5XEJg4Z6bKfbLNNvHAk27sH9uKqUoU8rkA&s');
background-size: cover;
background-repeat: no-repeat;
background-position: right bottom;    /* Unique property for dinner */
}
.menu h2 {
margin-top: 0;
margin-bottom: 18px;
font-size: 2em;
letter-spacing: 1.2px;
background: rgba(0,0,0,0.38);
padding: 8px 16px;
border-radius: 9px;
}
.menu ul {
padding-left: 20px;
margin-bottom: 0;
}
.menu li {
background: rgba(0,0,0,0.2);
margin-bottom: 12px;
padding: 8px 14px;
border-radius: 7px;
font-size: 1.12em;
}
</style>
</head>
<body>
<div class="menu-container">
<div class="menu breakfast">
<h2>Breakfast</h2>
<ul>
<li>Pancakes</li>
<li>bacon and eggs</li>
<li>biscuts and gravy</li>
<li>omelette</li>
<li>hashbrowns with eggs</li>
</ul>
</div>
<div class="menu lunch">
<h2>Lunch</h2>
<ul>
<li>cheese burger</li>
<li>california burger</li>
<li>philly cheese steak</li>
<li>hot beef</li>
<li>roast beef platter</li>
</ul>
</div>
<div class="menu dinner">
<h2>Dinner</h2>
<ul>
<li>porterhouse steak</li>
<li>prime rib</li>
<li>ribeye steak</li>
<li>avacodo burger</li>
<li>cheese burger</li>
</ul>
</div>
</div>
</body>
</html>
