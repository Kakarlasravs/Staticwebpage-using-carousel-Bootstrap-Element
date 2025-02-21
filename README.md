# Staticwebpage-using-carousel-Bootstrap-Element
HTML
<!DOCTYPE html> 
<html> 
 
<head> 
    
</head> 
 
<body> 
    <div class="backgroundimage"> 
        <div class="heading"> 
            <h1>Detailed view</h1> 
        </div> 
        <div class="cardcontainer"> 
            <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel"> 
                <ol class="carousel-indicators"> 
                    <li data-target="#carouselExampleIndicators" data-slideto="0" class="active"></li> 
                    <li data-target="#carouselExampleIndicators" data-slideto="1"></li>                     <li data-target="#carouselExampleIndicators" data-slideto="2"></li> 
                </ol> 
                <div class="carousel-inner"> 
                    <div class="carousel-item active"> 
                        <img 
src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-staticwebsite/tajmahal-c1-img.png" class="d-block w-100" alt="..."> 
                    </div> 
                    <div class="carousel-item"> 
                        <img 
src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-staticwebsite/tajmahal-c2-img.png" class="d-block w-100" alt="..."> 
                    </div> 
                    <div class="carousel-item"> 
                        <img 
src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-staticwebsite/tajmahal-c3-img.png" class="d-block w-100" alt="..."> 
                    </div> 
                </div> 
                <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev"> 
                    <span class="carousel-control-prev-icon" ariahidden="true"></span> 
                    <span class="sr-only">Previous</span> 
                </a> 
                <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next"> 
                    <span class="carousel-control-next-icon" ariahidden="true"></span> 
                    <span class="sr-only">Next</span> 
                </a> 
            </div> 
            <div class="bottom"> 
                <h1>Tajmahal</h1> 
                <p>The Taj Mahal (/ˌtɑːdʒ məˈhɑːl, ˌtɑːʒ-/; lit. 'Crown of the Palace') is an ivory-white marble mausoleum on the right bank of the river Yamuna in Agra, Uttar Pradesh, India. It was commissioned in 1631 by the fifth Mughal emperor, Shah Jahan (r. 1628–1658) to house the tomb of his beloved wife, Mumtaz Mahal; it also houses the tomb of Shah Jahan himself. The tomb is the centrepiece of a 17hectare (42-acre) complex, which includes a mosque and a guest house, and is set in formal gardens bounded on three sides by a crenellated wall.</p> 
            </div> 
        </div> 
    </div> 
</body> 
 
</html> 
 
 
 
Css: 

.backgroundimage {     background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-staticwebsite/seabg.png");     background-size: cover;     height: 180vh; 
} 
 
.cardcontainer { 
    border-radius: 20px;     margin: 24px;     padding: 5px; 
} 
 
.bottom {     background-color: white;     border-bottom-left-radius: 10px;     border-bottom-right-radius: 10px;     padding: 10px; 
 
} 
 
.heading {     font-family: "Caveat";     font-weight: bold;     text-align: center;     color: white; 
