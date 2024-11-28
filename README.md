*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'poppins',sans-serif;
}
body{
    color: #ededed;
}
.header{
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 20px 10%;
    background: transparent;
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}
.logo{

    position: relative;
    font-size: 25px;
    color: #fff;
    text-decoration: none;
    font-weight: 600;
}
.navbar a{
    display: inline-block;
    font-size: 25px;
    color: #fff;
    text-decoration: none;
    font-weight: 500;
    margin-left: 35px;
    transition: .3s;
}
.navbar a:hover{
    color: #0ef;
}
.home{
     position: relative;
     width: 100%;
     justify-content: space-between;
     height: 100vh;
     background:  #0e5c67;
     background-size: cover;
     background-position: center;
     display: flex;
     align-items: center;
     padding: 70px 10% 0;
} 
.home-content h3{
    font-size: 32px;
    font-weight: 700;
}
.home-content h1{
    font-size: 56px;
    font-weight: 700;
    margin: -3px 0;
}
.home-content p{
    font-size: 20px;
}
.home-sci a{
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 40px;
    height: 40px;
    background: transparent;
    border: 2px solid #0ef;
    border-radius: 50%;
    font-size: 20px;
    color: #0ef;
    text-decoration: none;
    margin: 30px 15px 30px 0;
}
.home-sci a:hover{
    background: #0ef;
    color: #081b29;
    box-shadow: 0 0 20px #0ef;
}
.btn-box{
    display: inline-block;
    padding: 12px 28px;
    background: #0ef;
    border-radius: 40px;
    font-size: 16px;
    color: #081b29;
    letter-spacing: 1px;
    text-decoration: none;
    font-weight: 600;
}
.btn-box:hover{
    box-shadow: 0 0 5px cyan,
    0 0 25px cyan, 0 0 50px cyan,
    0 0 100px cyan, 0 0 200px cyan
}
.photo{
    border-radius: 50%;
    justify-content: right;
    display: inline-flex;
    align-items: center;
    width: 400px;
    height: 400px;
    background: transparent;
    border: 2px solid #0ef;
    border-radius: 50%;
    font-size: 20px;
    color: #0ef;
    text-decoration: none;
    margin: 30px 15px 30px 0;
}
