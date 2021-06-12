<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Summary</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>

  <link rel="stylesheet" href="style.css">
</head>

<body>

  <div>
    <div class="row">
      <div class="col col-6 homebtn">
        <a href="index.html">Lattitude</a>
      </div>
      <div class="col col-6 menubuttons divtop">


        <nav class="navbar navbar-expand-md navbar-light">
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo03"
            aria-controls="navbarTogglerDemo03" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
            <ul class="navbar-nav">
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-toggle="dropdown"
                  aria-haspopup="true" aria-expanded="false">
                  Plots
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                  <a class="dropdown-item" href="max_temp.html">Max Temperature</a>
                  <a class="dropdown-item" href="humidity.html">Humidity</a>
                  <a class="dropdown-item" href="cloudiness.html">Cloudiness</a>
                  <a class="dropdown-item" href="wind_speed.html">Wind Speed</a>
                </div>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="comparison.html">Comparison</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="data.html">Data</a>
              </li>
            </ul>
          </div>
        </nav>


      </div>
    </div>
  </div>
  <!-- start of main body -->
  <div class="container">
    <br>
    <div class="row">
      <!-- left side -->
      <div class="col col-12 col-md-8 divbdy">
        <br>
        <h1>Summary: Latitude vs. X</h1>
        <hr>
        <img src="Resources/assets/images/Fig1.png" alt="Latitude vs. Temperature" width="280" align="left">
        <p>The purpose of this project was to analyze how weather changes as you get closer to the equator. To
          accomplish this analysis, we first pulled data from the OpenWeatherMap API to assemble a dataset on over 500
          cities.</p>
        <p>After assembling the dataset, we used Matplotlib to plot various aspects of the weather vs. latitude. Factors
          we looked at included: temperature, cloudiness, wind speed, and humidity. This site provides the souce data
          and visualizations created as part of the analysis, as well as explanations and descriptions of any trends and
          correlations witnesseed.</p>
        <hr>
      </div>
      <!-- left side end -->
      <!-- rigth side -->
      <div class="col col-12 col-md-4 divbdy">
        <br>
        <h2>Visualizations</h2>
        <hr>
        <div class='row'>
          <div class="col col-3 col-md-6">
            <a href="max_temp.html"><img src="Resources/assets/images/Fig1.png" alt="Latitude vs. Temperature"></a>
          </div>
          <div class="col col-3 col-md-6">
            <a href="humidity.html"><img src="Resources/assets/images/Fig2.png" alt="Latitude vs. Humidity"></a>
          </div>
          <div class="col col-3 col-md-6">
            <a href="cloudiness.html"><img src="Resources/assets/images/Fig3.png" alt="Latitude vs. Cloudiness"></a>
          </div>
          <div class="col col-3 col-md-6">
            <a href="wind_speed.html"><img src="Resources/assets/images/Fig4.png" alt="Latitude vs. Wind Speed"></a>
          </div>
        </div>
      </div>
     
    </div>
  </div>

</body>

</html>
