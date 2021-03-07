House Prices in Rural NY (Stat2Data)
========================================================
author: Ignacio Medina de Andres
date: 07/03/2021
autosize: true
font-import: https://fonts.googleapis.com/css2?family=Abel&display=swap
font-family: 'Abel'
css: custom.css



<center><img src="https://www.neurosciencemarketing.com/wp-content/uploads/2008/04/home_for_sale_price.jpg" width="625" height="400"></center>


Data description
========================================================
transition: fade
transition-speed: slow
This Houses dataset is obtained from the Stat2Data package (more information clicking: [link](<https://cran.r-project.org/web/packages/Stat2Data/Stat2Data.pdf>))

It represents the estimated house prices for a sample of 53 houses (~~*observations*~~) in Canton NY (a small town in upstate NY). The corresponding data frame would be composed with the following five columns (~~*variables*~~).

<li class="fragment fade-in">**Price**: Estimated price (in $1,000 s)</li>
<li class="fragment fade-in">**Beds**: Number of bedrooms</li>
<li class="fragment fade-in">**Baths**: Number of bathrooms</li>
<li class="fragment fade-in">**Size**: Floor area of the house (in 1,000 square feet)</li>
<li class="fragment fade-in">**Lot**: Size of the lot (in acres)</li>


Slide With Code
========================================================
type: prompt 
incremental: false
transition: zoom




```r
summary(data)
```

```
     Price            Beds           Baths            Size      
 Min.   : 38.5   Min.   :2.000   Min.   :1.000   Min.   :0.712  
 1st Qu.: 82.7   1st Qu.:3.000   1st Qu.:1.500   1st Qu.:1.296  
 Median :107.0   Median :3.000   Median :2.000   Median :1.528  
 Mean   :113.6   Mean   :3.396   Mean   :1.858   Mean   :1.678  
 3rd Qu.:141.0   3rd Qu.:4.000   3rd Qu.:2.000   3rd Qu.:2.060  
 Max.   :197.5   Max.   :6.000   Max.   :3.500   Max.   :3.100  
      Lot        
 Min.   :0.0000  
 1st Qu.:0.2700  
 Median :0.4200  
 Mean   :0.7985  
 3rd Qu.:1.1000  
 Max.   :3.5000  
```


Plot section 
=========================
type: sub-section
incremental: true

In this ~~sub-section~~ we are representing each variable versus the variable we want to study, **Price**.


Price - Size
========================================================
css: custom.css





<style>
  .p_iframe iframe {
    width:100%;
    height:700px;
}
</style>

<div class="p_iframe">
<iframe frameborder="0" seamless='seamless' scrolling=no src="plotly.html"></iframe>
</div>

Price - Beds
========================================================
incremental: true





<div class="p_iframe">
<iframe frameborder="0" seamless='seamless' scrolling=no src="plotly2.html"></iframe>
</div>


Price - Baths
========================================================
incremental: true





<div class="p_iframe">
<iframe frameborder="0" seamless='seamless' scrolling=no src="plotly3.html"></iframe>
</div>










