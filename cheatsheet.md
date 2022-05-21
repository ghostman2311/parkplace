## CSS Cheatsheet

### Applying background

background-image: url("../images/landing.png");
background-size: cover;
background-position: center;
background-repeat: no-repeat;

### Using Font Locally

font-family: "monserrat_regular";
src: url("/fonts/Montserrat-Regular.ttf");
font-weight: normal;
font-style: normal;

## Using Overlay Pseduoelement

content:"";
position: absolute;
display:block;
height:x px;
width: x px;
background: anything;
top: as per need;
left: as per need 


## Using background Pseudoelement
 #management::before{
    content: "";
    position: absolute;
    top:0;
    left:50%;
    display: block;
    height: 284px;
    width: 523px;
    background: url('../images/city.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    opacity: 1;
    transform: translateX(-50%) rotate(-1deg);
  }

