<!--HTML2_Website_Wire_1-1-2-->

<!DOCTYPE html>>
<html lang="en">
<h1>NOAA</h1>
<h2>National Weather Service</h2>

  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!--Icons-->
    <link rel="shortcut icon" href="C:\Users\Meghan Carr\Desktop\Meghan - ALL til OneDrive\CodeCrew\HTML2_Website_Wire_1-1-2\Footprints_GBHeron_cat_human.JPG" type="image/x-icon">
    <!--<div class="navbar-header">
            <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#top-nav">
                <span class="sr-only">Toggle navigation</span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
            </button>
        </div>
        -->
    <!--<script>-->
    <!--<style>-->
  </head>

  <body> 
    <h1 class="custom-header">HTML Day 2</h1>
    <p> Today we are learning some additional html elments used to structure content on a page. We will make ordered lists, unordered lists, and a table. </p>
    <img alt="TBD Weather image" src="">

    <h4> Dili needs groceries</h4>
    <ol>
        <li> Eggs </li> 
        <li> Fruits </li>
        <li> Bread </li>
        <li> Cat Food </li>
    </ol>
    <h4> Stores</h4>
    
    <ul>
        <li>Walmart</li>
        <li>Panera</li>
        <li>Sam's Club</li>
        <li>Hollywood Feed</li>
    </ul>

    <table style="border: 1px solid black;">
        <caption style="border: 1px solid black;"> Animals </caption>
        <tr>
            <th>Mammal</th>
            <th>Reptile</th>
            <th>Bird</th>
            <th>Amphibian</th>
        </tr>
        <tr>
            <td>Cats</td>
            <td>Lizard<td>
            <td>Ostrich</td>
            <td>Frog</td>
        </tr>
    </table>

    <body>
    <div style="display: flex;">

        <div style="flex:20%">
            <ul style="list-style-type: none;">
                <li style="display: block; width:40px">
                    <a style="display: block; width:40px" href="">Home</a>
                </li>
                <li style="display: block; width:40px">
                    <a style="display: block; width:40px" href="">Weather</a>
                </li>
                <li style="display: block; width:40px">
                    <a style="display: block; width:40px" href="">Climate</a>
                </li>
                <li style="display: block; width:40px">
                    <a style="display: block; width:40px" href="">Ocean</a>
                </li>
            </ul>
        </div>

        <div style="flex:80%">
            <div>
                <ul>
                    <li style="display: inline;">
                        <a href=""> 76 degrees, Memphis</a>
                    </li>
                    <li style="display: inline;"><a href="">News</a></li>
                    <li style="display: inline;"><a href="">Tools</a></li>
                    <li style="display: inline;"><a href="">About</a></li>
                </ul>
            </div>

        
            <div style="background-image: url(images.jpg); background-repeat: no-repeat;">
                <img src="images.jpg" alt="Penguins on top of an Iceberg" width="80%">
            </div>

            <div class="panel-heading">
              <b>Extended Forecast for</b>
              <h2 class="panel-title">
                3 Miles NW Memphis TN    </h2>
            </div>

  
    <div class="panel-body" id="seven-day-forecast-body">
            <div id="seven-day-forecast-container"><ul id="seven-day-forecast-list" class="list-unstyled"><li class="forecast-tombstone"><div class="tombstone-container"><p class="period-name">Today</p><p><img class="forecast-icon" src="newimages/medium/sct.png" alt="Today: Mostly sunny, with a high near 89. Calm wind becoming northeast around 5 mph in the afternoon. " title="Today: Mostly sunny, with a high near 89. Calm wind becoming northeast around 5 mph in the afternoon. "></p><p class="temp temp-high">High: 89 °F</p><p class="short-desc" style="height: 54px;">Mostly Sunny</p></div></li><li class="forecast-tombstone"><div class="tombstone-container"><p class="period-name">Tonight</p><p><img class="forecast-icon" src="newimages/medium/nfew.png" alt="Tonight: Mostly clear, with a low around 71. East northeast wind around 5 mph becoming calm  in the evening. " title="Tonight: Mostly clear, with a low around 71. East northeast wind around 5 mph becoming calm  in the evening. "></p><p class="temp temp-low">Low: 71 °F</p><p class="short-desc" style="height: 54px;">Mostly Clear</p></div></li><li class="forecast-tombstone"><div class="tombstone-container"><p class="period-name">Wednesday</p><p><img class="forecast-icon" src="newimages/medium/few.png" alt="Wednesday: Sunny, with a high near 92. Calm wind becoming northeast around 5 mph in the afternoon. " title="Wednesday: Sunny, with a high near 92. Calm wind becoming northeast around 5 mph in the afternoon. "></p><p class="temp temp-high">High: 92 °F</p><p class="short-desc" style="height: 54px;">Sunny</p></div></li><li class="forecast-tombstone"><div class="tombstone-container"><p 
            
            class="tombstone-container"><p> title="Friday Night...">Clear</p></div></li><li 
            
            class="forecast-tombstone"><div class="tombstone-container"><p class="period-name">Saturday</p><p><img class="forecast-icon" src="newimages/medium/few.png" alt="Saturday: Sunny, with a high near 94." title="Saturday: Sunny, with a high near 94."></p><p class="temp temp-high">High: 94 °F</p><p class="short-desc" style="height: 54px;">Sunny</p></div></li></ul></div>
<script type="text/javascript">
// equalize forecast heights
$(function () {
    var maxh = 0;
    $(".forecast-tombstone .short-desc").each(function () {
        var h = $(this).height();
        if (h > maxh) { maxh = h; }
    });
    $(".forecast-tombstone .short-desc").height(maxh);
});
</script>    </div>
</div>


  </body>
</html>
