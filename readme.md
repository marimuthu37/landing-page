<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<style>

    body{
        background-color: #f4f4f9;
    }

    .container{
        max-width: 600px;
        margin: auto;
        background-color: #fff;
        padding: 25px;
        border-radius: 7px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); 
    }

    .inp-div{
        padding: 10px;
        margin: 10px;
    }

    label{
        display: block;
        margin-bottom: 5px;
    }

    h2{
        color:blue;
        text-align: center;
        margin-bottom: 20px;
    }

    input{
        width: 100%;
        padding: 10px;
        border: 1px solid #ccc;
        border-radius: 4px;
        font-size: 1em;
    }

    .submit{
        text-align: center;
    }

    button{
        width: 100%;
        padding: 10px;
        font-size: 1em;
        color:white;
        background-color: blue;
        border: none;
        border-radius: 5px;
        cursor: pointer;
    }

    a{
    text-decoration: none;
    color: white;
}

.head{
    display: flex;
    justify-content: space-between;
    margin-top: 1rem;
    margin-left: 1rem;
}

.title{
    text-align:left;
    font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    color:blue ;
    font-size: 3.5rem;
    margin-left: 20px;
    margin-top: 5px;
    position: relative;
}

.titles{
    color:blue ;
    font-size: 2.5rem;
    font-family: 'Poppins';
    margin-left: 140px;
    margin-bottom: 10px;
    position: absolute;
    top: 70px;
    left: 65px;
}

.nav{
    color: white;
    display: flex;   
}

.nav-div{
    margin-top: 2rem;
    margin-right: 1rem;
    font-size: 1.5rem;
}

li{
    list-style: none;
}

.list{
    margin-left: 20px;
}

</style>


<body>
    <div class="head">
        <h1 class="title">SUNDHARA</h1>
        <div class="nav-div">
            <ul class="nav">
                <li class="list">HOME</li>
                <a href="places.html"> <li class="list">PLACES</li> </a>
                <a href="book.html"> <li class="list">BOOKINGS</li></a>
                <a href="about.html"><li class="list">ABOUT</li></a>
            </ul>
        </div>
    </div>
    <h1 class="titles"> Travels </h1>
    <div class="container">
        <form action="#" >
            <h2>Travel Inquiry Form</h2>
            <div class="inp-div">
                <label >Name</label>
                <input type="text" name="Name">
            </div>
            <div class="inp-div">
                <label >Number</label>
                <input type="number" name="Number" min="0">
            </div>
            <div class="inp-div">
                <label >E-mail</label>
                <input type="email" name="E-mail">
            </div>
            <div class="inp-div">
                <label >Destination</label>
                <input type="text" name="Destination">
            </div>
            <div class="inp-div">
                <label>From Date</label>
                <input type="date" name="From Date">
            </div>
            <div class="inp-div">
                <label >To Date</label>
                <input type="date" name="To Date">
            </div>
            <div class="inp-div">
                <label>Number of Travelers</label>
                <input type="number" name="Number of Travelers" min="1">
            </div>
            <div class="submit">
                <button>SUBMIT</button>
            </div>
        </form>
    </div>
</body>
</html>



















