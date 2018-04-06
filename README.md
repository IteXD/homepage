## Homepage
![enter image description here](https://github.com/IteXD/homepage/blob/master/screenshot.PNG?raw=true)
This is just a simple homepage that you can set on your browser it's very simple.

**Features**

 - Clock
 - DuckDuckGo search bar
 - Weather

**How to configure the weather**
So there is a weather widget on this homepage. You normally would have to go and get an API key but I made it more simplier and just left mine. The only thing you will have to change is your location

So on the line 66 you will have this

    var weatherapi = 'http://api.openweathermap.org/data/2.5/weather?q=Chisinau&appid=29b112c2e5fcf21a0af82b395f355219'; //CHANGE this with your api and your city
So instead of putting **Chisinau** you can change it to your city so let's say you live in Paris the code will look like this

    var weatherapi = 'http://api.openweathermap.org/data/2.5/weather?q=Paris&appid=29b112c2e5fcf21a0af82b395f355219'; //CHANGE this with your api and your city
You can also mention a specific country by doing something like this `Paris,FR` instead of just having `Paris` it's very simple.
If you need more help you can go [here](http://openweathermap.org/current)

