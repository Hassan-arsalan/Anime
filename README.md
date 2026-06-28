# Anime
A modern anime website where fans can explore trending anime, discover new series, read updates, and enjoy a clean and user-friendly experience.
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#111;
    color:white;
}

header{
    background:#ff3d00;
    padding:20px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:10px;
    font-weight:bold;
}

.hero{
    text-align:center;
    padding:50px 20px;
}

.hero input{
    padding:10px;
    width:250px;
    border:none;
    border-radius:5px;
}

.hero button{
    padding:10px 20px;
    background:#ff3d00;
    color:white;
    border:none;
    border-radius:5px;
    cursor:pointer;
}

.cards{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:20px;
    padding:20px;
}

.card{
    background:#222;
    width:220px;
    border-radius:10px;
    overflow:hidden;
    text-align:center;
}

.card img{
    width:100%;
}

.card h3{
    padding:10px;
}
