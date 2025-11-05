# menu
<!DOCTYPE html>
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
background-image: url('https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=400&q=80');
background-size: cover;
background-repeat: no-repeat;          /* Unique property for breakfast */
background-position: center center;
}
.lunch {
background-image: url('https://images.unsplash.com/photo-1516684669134-de6f26d2b54b?auto=format&fit=crop&w=400&q=80');
background-size: cover;
background-repeat: repeat-y;          /* Unique property for lunch */
background-position: left top;
}
.dinner {
background-image: url('https://images.unsplash.com/photo-1519864600265-abb23847ef01?auto=format&fit=crop&w=400&q=80');
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
<li>Classic Pancakes</li>
<li>Eggs Benedict</li>
<li>Bacon & Sausage Platter</li>
<li>Fresh Fruit Bowl</li>
<li>Croissants & Pastries</li>
</ul>
</div>
<div class="menu lunch">
<h2>Lunch</h2>
<ul>
<li>Grilled Chicken Sandwich</li>
<li>Caesar Salad</li>
<li>Turkey Club Wrap</li>
<li>Vegetable Quiche</li>
<li>Soup of the Day</li>
</ul>
</div>
<div class="menu dinner">
<h2>Dinner</h2>
<ul>
<li>Seared Salmon Filet</li>
<li>Herb Roasted Chicken</li>
<li>Pasta Primavera</li>
<li>Grilled Ribeye Steak</li>
<li>Garlic Mashed Potatoes</li>
</ul>
</div>
</div>
</body>
</html>
