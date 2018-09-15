<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <!-- Latest compiled and minified JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
    <!--<link rel="stylesheet" href="style.css">-->
    <title>Weather Analysis Visualization</title>
</head>
<body style="background-color: rgb(167, 212, 84)">
    
    <nav class="navbar navbar-default">
        <div class="container">
            <div class="navbar-header">
                <a class="navbar-brand logo" href="index.html"> 
                <span class="nav-color">Latitude</span></a>
            </div>

            <div class="nav navbar-nav navbar-right">
                <li class="dropdown"><a class="dropdown-toggle" data-toggle="dropdown">Plots<span class="caret"></span></a>
                    <ul class="dropdown-menu">
                        <li><a href="temp.html">Temperature</a></li>
                        <li><a href="humidity.html">Humidity</a></li>
                        <li><a href="cloudiness.html">Cloudiness</a></li>
                        <li><a href="wind.html">Wind Speed</a></li>
                    </ul>
                </li>
                <li><a href="comparison.html"> Comparison</a></li>
                <li><a href="data.html"> Data</a></li>                                           
            </div>
        </div>      
    </nav>

    <!--<div class = "container">-->
        <!--<div class="row">-->   
            <div class="col-md-8">
                <div class="panel panel-default">
                    <div class="panel-body">

                            <h2>Summary: Latitude vs Weather</h2>
                            <hr>
                            <!--<div class="row">-->
                                    <div class="col-sm-12">
                                        <img src="assets/images/Cloudiness.png" alt="Cloudiness">
                                        <img src="assets/images/Humidity.png" alt="Humidity">
                                        <img src="assets/images/Temperature.png" alt="Temperature">
                                        <img src="assets/images/WindSpeed.png" alt="WindSpeed">
                                        <p>
                                                The purpose of this project was to analyze how weather changes as you get 
                                                closer to the equator. To accomplish this analysis, we first pulled data 
                                                from the OpenWeatherMap API to assemble a dataset on over 500 cities.
                                                
                                                After assembling the dataset, we used Matplotlib to plot various aspects
                                                of the weather vs. latitude. Factors we looked at included: Temperature, 
                                                cloudiness, WindSpeed, and humidity. This site provides the source data and 
                                                visualizations created as part of the analysis, as well as explanations and 
                                                descriptions of any trends and correlatios witnessed. 
                                        </p> 
                    <br>        
                    </div>
              
            <div class="col-md-4">
                <div class="panel panel-default">
                        <div class="panel-body">                                   
                            <h2>Visualizations</h2>
                            <hr>

                            <div class="row" >
                                    <div class="col-lg-6 col-md-6 col-sm-6 col-xs-6"><a href="temp.html"><img class = "img img-responsive" src="assets/images/Temperature.png" style="width:100%" alt="Temperature"></a></div>
                                    <div class="col-lg-6 col-md-6 col-sm-6 col-xs-6"><a href="humidity.html"><img class = "img img-responsive" src="assets/images/Humidity.png" style="width:100%" alt="Humidity"></a></div>
                                </div>
                                <div class="row">
                                    <div class="col-lg-6 col-md-6 col-sm-6 col-xs-6"><a href="cloudiness.html"><img class = "img img-responsive" src="assets/images/Cloudiness.png" style="width:100%" alt="Cloudliness"></a></div>
                                    <div class="col-lg-6 col-md-6 col-sm-6 col-xs-6"><a href="wind.html"><img class = "img img-responsive" src="assets/images/WindSpeed.png" style="width:100%" alt="WindSpeed"></a></div>
                                </div>
                                
                        </div>
                </div>     
            </div>    
    </div>
</body>
</html>
