# projectone.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="home.css">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.6.3/css/all.css" integrity="sha384-UHRtZLI+pbxtHCWp1t77Bi1L4ZtiqrqD80Kn4Z8NTSRyMA2Fd33n5dQ8lWUE00s/" crossorigin="anonymous">
    <title>Fashion Top 1</title>
    <link rel="shortcut icon" href="img/iconfinder_robot_3285302.png">
</head>
<body>
    <button onclick="topFunction()" id="myBtn" title="Lên đầu trang"><i class="fas fa-caret-up"></i></button>
    <header class="header">
        <div class="container-header">
            <ul class="header-ul">
              <li class="header-li"><i class="fas fa-sign-in-alt " style="margin-right: 7px;font-size: 14px;color:aqua;" ></i><a href="signin.html">Sign In</a></li>
              <li class="header-li"><i class="fas fa-user-plus" style="margin-right: 7px;font-size: 14px;color:aqua;" ></i><a href="signup.html">Sign Up</a></li>
              <li class="header-li" onclick="myFunction()"><i class="fas fa-phone" style="margin-right: 7px;font-size: 14px;color:aqua;" ></i><a href="">Call: 0932054281</a></li>
              <li class="header-li" ><i class="fas fa-envelope" style="margin-right: 7px;font-size: 14px;color:aqua;"></i><a href="#">fashiontop1@gmail.com</a></li>
            </ul>
        </div>
    </header>
    <header class="header-bot">
       <div class="container-header-bot">
           <div class="box-header-bot">
               <div class="search">
                   <input type="text" id="myInput" placeholder=" Search here...">
               </div>
               <div class="icon-search">
                 <a href="#"><i class="fas fa-search" style="color: white;font-size: 30px;padding: 15px;"></i></a>
               </div>
           </div>
           <div class="box-header-bot">
               <div class="E-left"><span><a href="home.html">F</a></span></div>
               <div class="E-right"><span style="cursor: pointer; letter-spacing: 1px;">ashion Top One</span></div>
           </div>
           <div class="box-header-bot">
               <div class="share-left"><span>Share on : </span></div>
               <div class="share-right">
                   <div class="icon-share" style="color: #3B5998;"><i class="fab fa-facebook-square"></i></div>
                   <div class="icon-share" style="color: #55ACEE;"><i class="fab fa-twitter-square"></i></div>
                   <div class="icon-share" style="color: orangered"><i class="fas fa-camera"></i></div>
                   <div class="icon-share" style="color: brown"><i class="fab fa-invision"></i></div>
               </div>
           </div>
       </div>
    </header>
    <nav class="nav">
        <div class="container-nav">
            <div class="nav-left">
               <ul class="nav-left-ul r">
                   <li class="hover-botton"><a href="home.html">Home</i></a>
                       <div class="border-w3"></div>
                   </li>
                   <li class="hover-botton"><a href="about.html">About</a>
                    <div class="border-w3"></div>
                   </li>
                   <li class="hover-botton"><a href="#">Men's wear <i class="fas fa-caret-down"></i></a>
                      <ul class="men-ul" style="width: 170px;">
                          <li class="men-li"><a href="donghonam.html">Đồng hồ nam</a></li>
                          <li class="men-li">Dày dép nam</li>
                          <li class="men-li">Áo sơ mi nam</li>
                          <li class="men-li">Ví nam</li>
                          <li class="men-li">Ba lô nam</li>
                          <li class="men-li">Mắt kính nam</li>
                      </ul>
                      <div class="border-w3"></div>
                   </li>
                   <li class="hover-botton"><a href="#">Women'wear <i class="fas fa-caret-down"></i></a>
                    <ul class="men-ul">
                        <li class="men-li"><a href="donghonu.html">Đồng hồ nữ</a></li>
                        <li class="men-li">Dày dép nữ</li>
                        <li class="men-li">Áo</li>
                        <li class="men-li">Váy</li>
                        <li class="men-li">Ví</li>
                        <li class="men-li">Ba lô</li>
                        <li class="men-li">Mắt kính nữ</li>
                    </ul>
                    <div class="border-w3"></div>
                </li>
                   <li class="hover-botton" style="width: 178px;"><a href="#">Short codes <i class="fas fa-caret-down"></i></a>
                    <ul class="men-ul">
                        <li class="men-li">Codes 1</li>
                        <li class="men-li">Codes 2</li>
                        
                    </ul>
                    <div class="border-w3"></div>
                </li>
                    
                </li>
                   <li class="hover-botton"><a href="contact.html">Contact</a>
                    <div class="border-w3"></div>
                </li>
               </ul>
            </div>
            <div class="nav-right">
                <div class="icon-nav-right">
                    <i class="fas fa-cart-arrow-down"></i>
                    <a href="#"></a>
                </div>
            </div>
        </div>
    </nav>
    
    <div class="slide-show">
        <div class="card-slide-show">
            <img class="fade" src="imgmen/banner1.jpg">
        </div>
        <div class="card-slide-show">
            <img class="fade" src="imgmen/banner2.jpg">
        </div>
        <div class="card-slide-show">
            <img class="fade" src="imgmen/banner3.jpg">
        </div>
        <div class="card-slide-show">
            <img class="fade" src="imgmen/banner4.jpg">
        </div>
        <div class="card-slide-show">
            <img class="fade" src="imgmen/banner5.jpg">
        </div>
        <!-- <div class="button-left"></div>
        <div class="button-right"></div> -->
        <div class="show-top">THE BIGGEST <span>SALE</span></div>
        <div class="show-center"><span>Special for today</span></div>
        <button class="show-button"><span><a href="donghonam.html">Shop Now</a></span></button>
        <!-- <div class="show-cham">
            <div class="show-cham-1"></div>
            <div class="show-cham-1"></div>
            <div class="show-cham-1"></div>
            <div class="show-cham-1"></div>
            <div class="show-cham-1"></div>
        </div> -->
    </div>
    <div class="banner">
        <div class="container-banner">
            <div class="banner-left">
                <img src="imgmen/banner1.jpg">
                <div class="ahead" style="font-size:1.7em;letter-spacing:5px;color:#fff;text-transform:uppercase;font-family: Arial, Helvetica, sans-serif"><span style="font-size:1.7em;letter-spacing:5px;color:#e71f30;font-weight: 800">F</span>ALL AHEAD</div>
                <div class="new-ahead" style="letter-spacing:12px;font-size:1.2em; color: #fff;">New Arrivals</div>
                <div class="border-ahead"></div>
                <div class="border-detail"></div>
            </div>
            <div class="banner-right">
                <img src="imgmen/banner2.jpg">
                <div class="ahead" style="font-size:1.7em;letter-spacing:5px;color:#fff;text-transform:uppercase;font-family: Arial, Helvetica, sans-serif"><span style="font-size:1.7em;letter-spacing:5px;color:#e71f30;font-weight: 800">F</span>ALL AHEAD</div>
                <div class="new-ahead" style="letter-spacing:12px;font-size:1.2em;color: #fff;">New Arrivals</div>
                <div class="border-ahead"></div>
                <div class="border-detail"></div>
            </div>
        </div>
    </div>
    <div class="schedule">
        <div class="schedule-left">
            <img src="img/schedule.jpg">
        </div>
        <div class="schedule-right">
            <div class="save-up">
                <div class="save-up-title" style="font-family:Arial, Helvetica, sans-serif;font-weight: 700; font-size:1.4em;text-tranform:uppercase;color:#212121;letter-spacing: 3px;">SAVE UP TO <span style="color:#e71f30">50%</span> IN THIS WEEK</div>
                <div class="save-up-content" style="font-size:0.9em;letter-spacing:1px;font-family:'Open Sans', sans-serif;word-spacing: 1px;color:#333;line-height: 30px;">Suspendisse varius turpis efficitur erat laoreet dapibus. Mauris sollicitudin scelerisque commodo.Nunc dapibus mauris sed metus finibus posuere.</div>
                <div class="save-icon">
                    <div class="save-icon-detail">
                        <i class="fas fa-user-alt"></i>
                        <div class="save-icon-detail-text" style="letter-spacing:1px;font-family: Arial, Helvetica, sans-serif;margin-left: 12%;"><span>CUSTOMERS</span></div>
                        <div class="save-icon-detail-content">653</div>
                    </div>
                    <div class="save-icon-detail">
                        <i class="fas fa-calendar-week"></i>
                        <div class="save-icon-detail-text" style="letter-spacing:1px;font-family: Arial, Helvetica, sans-serif; margin-left: 30%;"><span>EVENT</span></div>
                        <div class="save-icon-detail-content">823</div>
                    </div>
                    <div class="save-icon-detail">
                        <i class="fas fa-shield-alt"></i>
                        <div class="save-icon-detail-text" style="letter-spacing:1px;font-family: Arial, Helvetica, sans-serif;padding-left: 30%;"><span>AWARS</span></div>
                        <div class="save-icon-detail-content">57</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="sale">
        <div class="sale-title">
            <div class="sale-title-content" style="font-family: 'Open Sans', sans-serif;">WHAT'S <span style="font-weight:100;color:#333">TRENDING</span></div>
        </div>
        <div class="container-sale">
            <div class="sale-left">
                <img src="img/18.jpg">
                <div class="sale-left-content-1"><span style="color:#e71f30">S</span>ale</div>
                <div class="sale-left-content-2">Up to 55%</div>
                <div class="sale-left-border-container"></div>
                <div class="sale-left-border-content"></div>
            </div>
            <div class="sale-right">
                <div class="sale-right-detail " >
                    <img src="imgmen/banner5.jpg">
                    <div class="sale-right-content-1"><span style="color:#e71f30">S</span>ale</div>
                    <div class="sale-right-content-2">Up to 55%</div>
                    <div class="sale-right-border-container"></div>
                    <div class="sale-right-border-content"></div>
                </div>
                <div class="sale-right-detail ">
                    <img src="imgmen/banner4.jpg">
                    <div class="sale-right-content-1"><span style="color:#e71f30">S</span>ale</div>
                    <div class="sale-right-content-2">Up to 55%</div>
                    <div class="sale-right-border-container"></div>
                    <div class="sale-right-border-content"></div>
                </div>
            </div>
        </div>
    </div>
    <div class="couple-sale">
        <div class="couple-sale-left">
            <img src="img/Women-Clothing.jpg">
            <div class="couple-flat">Flat <span style="color: aqua;font-weight:700">50%</span> offer</div>
            <div class="back-down-left"></div>
        </div>
        <div class="couple-sale-right">
            <img src="img/club_monaco_blazer_suiting.0.jpg">
            <div class="couple-flat">Flat <span style="color: aqua;font-weight:700">50%</span> offer</div>
            <div class="back-down-right"></div>
        </div>
    </div>
    <div class="new-arrivals">
        <div class="form-add-to-car" id="myForm">
            <div class="container-form-pupup">
                <div class="add-shop-1">Sản phẩm 1
                    <input type="text" placeholder="Số lượng">
                    <input class="submit-add"  type="submit" value="Đặt hàng" style=" cursor: pointer;background-color: #fc636b">
                    <div class="xoasanpham">Xóa</div>
                </div>
                <div class="add-shop-2">Sản phẩm 2
                    <input type="text" placeholder="Số lượng">
                    <input class="submit-add" type="submit" value="Đặt hàng" style=" cursor: pointer;background-color: #fc636b">
                    <div class="xoasanpham">Xóa</div>
                </div>
                <div class="add-shop-2">Sản phẩm 3
                    <input type="text" placeholder="Số lượng">
                    <input class="submit-add" type="submit" value="Đặt hàng" style=" cursor: pointer;background-color: #fc636b">
                    <div class="xoasanpham">Xóa</div>
                </div>
                <div class="add-shop-2">Sản phẩm 4
                    <input type="text" placeholder="Số lượng">
                    <input class="submit-add" type="submit" value="Đặt hàng" style=" cursor: pointer;background-color: #fc636b">
                    <div class="xoasanpham">Xóa</div>
                </div>
                <div class="close-form-add-shop" onclick="closeForm()">X</div>
            </div>
            <button class="check-out" ><span>Check Out With</span></button>
        </div>
        <div class="new-arrivals-title">
            <div class="new-arrivals-content">NEW <span style="font-weight:200; color:#333">ARRIVALS</span></div>
        </div>
        <div class="new-arrivals-container">
            <div class="nav-arrivals ">
               <div class="arrivals-menu active-arrivals">MEN'S<i class="fas fa-caret-down active-caret-down" id="a1"></i></div>
               <div class="arrivals-menu">WOMENT'S<i class="fas fa-caret-down" id="a2"></i></div>
               <div class="arrivals-menu">BAGG<i class="fas fa-caret-down" id="a3"></i></div>
               <div class="arrivals-menu">FOOTWEAR<i class="fas fa-caret-down" id="a4"></i></div>
            </div>
            <div class="mens" id="m1">
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                        <img src="img/men1.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                        <p class="p-arr-1">Formal Blue Shirt</p>
                        <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                        <img src="img/men2.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$78.99  <span><del style="color:gray;">$50.23</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/men3.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/men4.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/men5.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/men6.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1"w>
                            <img src="img/men7.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                        <img src="img/men1.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
             </div>

             <div class="mens" id="m2" style="display: none">
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                        <img src="img/women1.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                        <p class="p-arr-1">Formal Blue Shirt</p>
                        <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                        <img src="img/women2.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$78.99  <span><del style="color:gray;">$50.23</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/women3.png">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/women4.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/women5.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/women6.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/women7.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">4
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                        <img src="img/women8.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
             </div>
             <div class="mens" id="m3" style="display: none">
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                        <img src="img/bagg1.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                        <p class="p-arr-1">Formal Blue Shirt</p>
                        <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                        <img src="img/bagg2.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$78.99  <span><del style="color:gray;">$50.23</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/bagg3.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/bagg4.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/bagg5.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/bagg6.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/bagg7.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">4
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                        <img src="img/bagg8.webp">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
             </div>
             <div class="mens" id="m4" style="display: none">
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                        <img src="img/footwear1.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                        <p class="p-arr-1">Formal Blue Shirt</p>
                        <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                        <img src="img/footwear2.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$78.99  <span><del style="color:gray;">$50.23</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/footwear3.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view"><a href="singlepgage.html">QUICK VIEW</a></div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/footwear4.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view">QUICK VIEW</div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/footwear5.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view">QUICK VIEW</div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/footwear6.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view">QUICK VIEW</div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                            <img src="img/footwear7.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view">QUICK VIEW</div>
                    </div>
                    <div class="card-arrivals-2">4
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
                <div class="arrivals-new-mens">
                    <div class="card-arrivals-1">
                        <img src="img/footwear8.jpg">
                        <div class="card-arrivals-1-new">New</div>
                        <div class="card-arrivals-1-view">QUICK VIEW</div>
                    </div>
                    <div class="card-arrivals-2">
                            <p class="p-arr-1">Formal Blue Shirt</p>
                            <p class="p-arr-2">$45.99  <span><del style="color:gray;">$69.71</del></span></p>
                    </div>
                    <div class="card-arrivals-3">
                        <div class="card-arrivals-3-detail" onclick="openForm()">ADD TO CAR</div>
                    </div>
                </div>
             </div>
        </div>
    </div>



    <div class="discount">
        <img src="imgmen/banner3.jpg">
        <div class="discount-content">We Offer Flat <span style="color: aqua">40%</span> Discount</div>
        <div class="discount-button">Shop Now</div>
    </div>

    <div class="coupon">
        <div class="coupon-container">
            <div class="coupon-card">
                <div class="coupon-card-left"><i class="fas fa-truck"></i></div>
                <div class="coupon-card-right">
                    <p class="coupon-text-top">FREE SHIPPING</p>
                    <p class="coupon-text-button">Lorem ipsum dolor sit amet, consectetur</p>
                </div>
            </div>
            <div class="coupon-card">
                <div class="coupon-card-left"><i class="fas fa-headphones"></i></div>
                <div class="coupon-card-right">
                    <p class="coupon-text-top">24/7 SUPPORT</p>
                    <p class="coupon-text-button">Lorem ipsum dolor sit amet, consectetur</p>
                </div>
            </div>
            <div class="coupon-card">
                <div class="coupon-card-left"><i class="fas fa-shopping-bag"></i></div>
                <div class="coupon-card-right">
                    <p class="coupon-text-top">MONEY BACK GUARANTEE</p>
                    <p class="coupon-text-button">Lorem ipsum dolor sit amet, consectetur</p>
                </div>
            </div>
            <div class="coupon-card">
                <div class="coupon-card-left"><i class="fas fa-gift"></i></div>
                <div class="coupon-card-right">
                    <p class="coupon-text-top">FREE GIFT COUPONS</p>
                    <p class="coupon-text-button">Lorem ipsum dolor sit amet, consectetur</p>
                </div>
            </div>
        </div>
    </div>

    <div class="footer">
        <div class="container-footer">
            <div class="footer-left">
                <div class="container-footer-left">
                    <div class="footer-left-left">
                        <div class="footer-left-left-title"><span>F</span>ashion Top One</div>
                        <div class="footer-left-left-content">Lorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora.</div>
                        <div class="footer-left-left-icon">
                            <div class="footer-left-left-icon-detail" style="color: rgb(10, 10, 243);"><i class="fab fa-facebook-square"></i></div>
                            <div class="footer-left-left-icon-detail" style="color: rgba(79, 79, 230, 0.993);"><i class="fab fa-twitter-square"></i></div>
                            <div class="footer-left-left-icon-detail" style="color: orangered"><i class="fas fa-camera"></i></div>
                            <div class="footer-left-left-icon-detail" style="color: brown"><i class="fab fa-invision"></i></div>
                        </div>
                    </div>
                    <div class="footer-left-right">
                        <div class="footer-left-right-title"><span style="font-weight: 800">OUR</span> INFORMATION</div>
                        <div class="menu-footer">
                            <ul>
                                <li>Home</li>
                                <li>Men's Wear</li>
                                <li>Woment's wear</li>
                                <li>About</li>
                                <li>Short Codes</li>
                                <li>Contact</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer-right">
                <div class="container-footer-right">
                    <div class="footer-right-left">
                        <div class="footer-right-left-title">STORE <span>INFORMATION</span></div>
                        <div class="container-footer-right-left">
                        <div class="footer-right-left-detail">
                            <div class="footer-right-left-detail-icon"><i class="fas fa-phone"></i></div>
                            <div class="footer-right-left-detail-content">
                                <p class="footer-right-left-detail-content-top">Phone Number</p>
                                <p class="footer-right-left-detail-content-button">+84 932 054 281</p>
                            </div>
                        </div>
                        <div class="footer-right-left-detail">
                            <div class="footer-right-left-detail-icon"><i class="fas fa-envelope"></i></div>
                            <div class="footer-right-left-detail-content">
                                <p class="footer-right-left-detail-content-top">Email Address</p>
                                <p class="footer-right-left-detail-content-button">Email : <span style="color: #2fdab8">fashion@gmail.com</span></p>
                            </div>
                        </div>
                        <div class="footer-right-left-detail">
                            <div class="footer-right-left-detail-icon"><i class="fas fa-map-marker-alt"></i></div>
                            <div class="footer-right-left-detail-content">
                                    <p class="footer-right-left-detail-content-top">Location</p>
                                    <p class="footer-right-left-detail-content-button">Broome St, NY 10002,California, USA.</p>
                            </div>
                        </div>
                        </div>
                    </div>
                    <div class="footer-right-right">
                        <div class="footer-right-right-title">FLICKR <span>POSTS</span></div>
                        <div class="grid-footer-right-right"><img src="img/grid.jpg"></div>
                        <div class="grid-footer-right-right"><img src="img/gird-1.jpg"></div>
                        <div class="grid-footer-right-right"><img src="img/grid-3.jpg"></div>
                        <div class="grid-footer-right-right"><img src="img/grid-3.jpg"></div>
                        <div class="grid-footer-right-right"><img src="img/grid-2.jpg"></div>
                        <div class="grid-footer-right-right"><img src="img/grid-3.jpg"></div>
                        <div class="grid-footer-right-right"><img src="img/grid.jpg"></div>
                        <div class="grid-footer-right-right"><img src="img/gird-1.jpg"></div>
                        <div class="grid-footer-right-right"><img src="img/grid-3.jpg"></div>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer-sign-up">
            <div class="footer-sign-up-left">SIGN UP FOR NEWSLETTER !</div>
            <div class="footer-sign-up-right">
                <div class="footer-sign-up-right-left">
                    <input type="text" placeholder="Enter your email...">
                </div>
                <div class="footer-sign-up-right-right">SUBMIT</div>
            </div>
        </div>
        <div class="footer-button"></div>
    </div>
</body>
<script src="home.js"></script>
</html>