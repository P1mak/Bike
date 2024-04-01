# Bike
Bike Rental

>>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bike4Rent</title>
    <!-- <link rel="stylesheet" href="css/index.css"> -->
<style>
    *{
    padding:0;
    margin:0;
}
body{
    background-color:#f3efef;
}
.head{
    width:100%;
    background: black; 
}
a{
    text-decoration: none;
    color:white;
}
.head ul{
    display: flex;
    list-style: none;
    

}

.head ul li{
    color: white;
    font-size: 17px;
    padding:14px;
    margin:0px 10px;
    font-family: sans-serif;
    cursor: pointer;
}

.head ul li:hover{
    background-color: rgb(23, 219, 187);
}

.image_sec img{
    width:100%;
    height:600px;

}
.our_fleet{
width:90%;
margin: auto;
}

.bike_info{
    position: relative;
    width:300px;
    float: left;
    border:0px solid red;
    box-sizing:border-box;

}
.bike_info img{
width:210px;
height:210px;
margin-left: -70px;
}

.bike_info img:hover{
    margin-left: 10px;
    transition:0.2s ease-in-out;
}

.image_outer{
    width: 250px;
    height: 250px;
    border-radius: 100%;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: rgb(248, 248, 248);
    margin-left: 50px;
    margin-top: 50px;
}

.bike_info p{
    margin-bottom: 5px;
    display: flex; 
    align-items: center;
    justify-content: center;
}
.type{
    font-family: sans-serif;
    margin-top: 30px;
    font-size: 15px;
    color:#726f6f;
}

.pise{
    color:red;
    font-size: 19px;
    font-weight: bold;
    font-family: sans-serif;
}
.bike_info button
{
 width:130px;
 height:38px;
 border:0;
 outline: none;
 color:white;
 font-size: 18px;
 border-radius: 10px;
 margin-left:80px;
 background-color: rgb(13, 132, 179);
}
.bike_info button:hover{
    background-color:rgb(6, 55, 75) ;
}

.for_float{
    float:left;
}

.about_bike{
    width:100%;
    margin-top: 50px;
    display: flex;
    float:left;
}

.about_image{
    width:50%;
}
.about_image img{
    width:100%;
    height:100%;
}
.about_para{
    width:50%;
    padding:50px 30px;
    box-sizing: border-box;
    background-color: rgb(154, 154, 163);
}

.about_para .dan{
    font-size: 40px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
}

.about_para .dan1{
font-size: 17px;
color:white;
font-family: sans-serif;
line-height: 32px;
}

.contact{
    float: left;
    width:100%;
    background-image: url("https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/dark-wallpapers.jpg?q=50&fit=contain&w=767&h=384&dpr=1.5");
    background-size:cover;
    background-blend-mode:darken;
    box-sizing: border-box;
    color:white;
    display: flex;

}

.touch{
    width:50%;
}
.touch .touch_p1{
    font-size: 30px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 70px;
    margin-bottom: 25px;
}

.touch .touch_p2{
    width:80%;
    font-size: 20px;
    margin: auto;
    margin-bottom: 20px;
}
form label{
    font-size: 17px;
    margin-left: 40px;
}

form input{
    width:80%;
    height: 40px;
    border:0;
    padding:10px;
    border-radius: 10px;
    margin-left: 40px;
    box-sizing: border-box;
    margin-bottom: 10px;
    font-size: 18px;
}

form textarea{
    width:70%;
    margin-left: 40px;
    border-radius:6px;
    padding:10px;
}

.send-btn{
    width:120px;
    height:40px;
    border: 0;
    outline: none;
    border-radius: 7px;
    color: white;
    background-color: rgb(96, 96, 209);
    margin-left: 20px;
}
.send-btn:hover{
    background-color: rgb(58, 58, 143);
}
.reset-btn{
    width:120px;
    height:40px;
    border: 0;
    outline: none;
    border-radius: 7px;
    color: white;
    background-color: rgb(96, 96, 209);
}
.reset-btn:hover{
    background-color: rgb(58, 58, 143);
}
.map{
    width:50%;
}

.map-pic{
    width:600px;
    height:450px;
    margin-top: 50px;
    border-radius: 5px;
    background-blend-mode:darken;
}
.sidebar{
    height: 100px;
background-color: rgb(184, 176, 176);
}

@media screen and (max-width:500px)
{

    .head ul li{
        display: none;
    }
    .about_bike{
        display: inline;

    }
    
    .about_image{
        position: absolute;
        width:100%;
        height: 165%;
        background-color: black;
    }

    .about_para{
        width:100%;
        padding:50px 30px;
        box-sizing: border-box;
        color:red;
        background-color: rgb(154, 154, 163);
    }

    .about_para .dan1{
        position: relative;
        font-size: 17px;
        color:red;
        font-family: sans-serif;
        line-height: 32px;
        opacity: 1;
        }
        
        .contact{
          
           
            display: inline;
        
        }

        .our_fleet{
            width:100%;
            margin: 10px;
            }
        
            .bike_info img{
                width:160px;
                height:160px;
                margin-left: -70px;
                }

                .image_outer{
                    width: 200px;
                    height: 200px;
                } 
                
                .type{
                    font-family: sans-serif;
                    margin-top: 30px;
                    font-size: 13px;
                    color:#726f6f;
                }
                
                .pise{
                    color:red;
                    font-size: 17px;
                    font-weight: bold;
                    font-family: sans-serif;
                }
                .bike_info button
                {
                 width:100px;
                 height:30px;
                 font-size: 17px;           
                 margin-left:100px;
                }
.touch .touch_p2{
    width:90%;
    font-size: 15px;
    margin: auto;
    margin-bottom: 20px;
}
form label{
    font-size: 15px;
    margin-left: 10px;
}

form input{
    width:100%;
    height: 30px;
    border:0;
    padding:10px;
    border-radius: 5px;
    margin-left: 10px;
    box-sizing: border-box;
    margin-bottom: 10px;
    font-size: 18px;
}

form textarea{
    width:80%;
    margin-left: 10px;
    border-radius:6px;
    padding:10px;
}

.send-btn{
    width:60px;
    height:30px;
    border: 0;
    outline: none;
    border-radius: 7px;
    color: white;
    background-color: rgb(96, 96, 209);
    margin-left: 10px;
}


.reset-btn{
    width:60px;
    height:30px;
    border: 0;
    outline: none;
    border-radius: 7px;
    color: white;
    background-color: rgb(96, 96, 209);
}

.map-pic{
    width:360px;
    height:450px;
    margin-top: 50px;
    background-blend-mode:darken;
}
}
</style>
</head>

<body>
    <section class="head">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#ourfleet">Our Feel</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#get-in-touch">Contact</a></li>
            <li><a href="#">Login/SignUp</a></li>
        </ul>
    </section>
    <section class="image_sec">
        <img src="http://www.argusacademy.com/tribhuwan/4.jpg">
    </section>

    <section class="our_fleet" id="ourfleet">
        <h1>Our</h1>
        <div class="bike_info">
            <div class="image_outer">
                <img src="http://www.argusacademy.com/tribhuwan/b2.png">
            </div>
            <p class="type">Harley-Davidson-Iron-883-98</p>
            <p class="pise">₹ 550/day</p>
            <button>Book</button>

        </div>

        <div class="bike_info">
            <span class="image_outer">
                <img src="http://www.argusacademy.com/tribhuwan/b3.png">
            </span>
            <p class="type">Harley-Davidson-Roadster-33</p>
            <p class="pise">₹ 530/day</p>
            <button>Book</button>

        </div>

        <div class="bike_info">
            <span class="image_outer">
                <img src="http://www.argusacademy.com/tribhuwan/b4.png">
            </span>
            <p class="type">Harley-Davidson-Iron-883-98</p>
            <p class="pise">₹ 450/day</p>
            <button>Book</button>

        </div>

        <div class="bike_info">
            <span class="image_outer">
                <img src="http://www.argusacademy.com/tribhuwan/b5.png">
            </span>
            <p class="type">Harley-Davidson-Street-750-32</p>
            <p class="pise">₹ 500/day</p>
            <button>Book</button>

        </div>

        <div class="bike_info">
            <span class="image_outer">
                <img src="http://www.argusacademy.com/tribhuwan/b6.png">
            </span>
            <p class="type">KTM-RC-200-39</p>
            <p class="pise">₹ 400/day</p>
            <button>Book</button>

        </div>

        <div class="bike_info">
            <span class="image_outer">
                <img src="http://www.argusacademy.com/tribhuwan/b7.png">
            </span>
            <p class="type">KTM-Duke-390-45</p>
            <p class="pise">₹ 380/day</p>
            <button>Book</button>

        </div>

        <div class="bike_info">
            <span class="image_outer">
                <img src="http://www.argusacademy.com/tribhuwan/b8.png">
            </span>
            <p class="type">KTM-Duke-200-57</p>
            <p class="pise">₹ 350/day</p>
            <button>Book</button>

        </div>

        <div class="bike_info">
            <span class="image_outer">
                <img src="http://www.argusacademy.com/tribhuwan/b9.png">
            </span>
            <p class="type">Royal-Enfield-Classic---350-2</p>
            <p class="pise">₹ 480/day</p>
            <button>Book</button>

        </div>



    </section>
    <div class="for_float"></div>
    <section class="about_bike" id="about">
        <div class="about_image">
            <img
                src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTsiZpgDe57iogGoW2LDCFY8lk1_6g-yydNmQ&usqp=CAU">
        </div>

        <div class="about_para" >
            <p class="dan">About</p>
            <p class="dan1">Bike 4 Rent started up in 2016 when we noticed the passion and craze people possessed
                towards bikes and touring especially with the Royal Enfield.
                Ever since, Bike 4 Rent, has been true to its core beliefs in building a biking community across the
                globe with highly maintained bikes.
                We never believed in competition hence opened the doors for others by procuring the first license in
                North India. Unlike others we also do not carry just one make or model, all our locations feature a wide
                variety appropriate for exploring, touring and commuting.
                Our locations are a one stop solution for all your biking needs. Our brand is built on 2 words –
                ‘Quality’ and ‘Brotherhood’. We do not provide motorcycles but an experience to cherish.
                Our motto, ‘We do not compete, we care’ is evident from the growing number of Franchise with us. All our
                locations share the same enthusiasm and excitement to give the customer an amazing experience.
                From the start to the end of your trip, Bike 4 Rent will work around the clock to give you an experience
                to remember.
            </p>
        </div>

    </section>

    <section class="contact" id="get-in-touch">
        <div class="touch">
            <p class="touch_p1">Get In Touch</p>
            <p class="touch_p2">Address : Lalpur, Ranchi / Ph no. : 7978564349 / Email id : trikr3456@gmail.com</p>
            <form>
                <label>Name:</label><br>
                <input type="text"><br>

                <label>Phone No:</label><br>
                <input type="text"><br>

                <label>Email:</label><br>
                <input type="text"><br>

                <label>Message:</label><br>
                <textarea rows="7" cols="25" placeholder="write Message here"></textarea><br>
                <button class="send-btn">Send</button>
                <button class="reset-btn">Reset</button>
            </form>

        </div>
        <div class="map">
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d234447.11326020389!2d85.18123822131419!3d23.343457743750946!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39f4e104aa5db7dd%3A0xdc09d49d6899f43e!2sRanchi%2C%20Jharkhand!5e0!3m2!1sen!2sin!4v1632590769772!5m2!1sen!2sin"
                style="border:0;" allowfullscreen="" loading="lazy" class="map-pic"></iframe>
        </div>
    </section>

    <section class="sidebar">
        
    </section>
</body>

</html>
