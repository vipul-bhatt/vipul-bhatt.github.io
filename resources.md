---
type: page
title:
use-site-title: true
---

<style>

.content {width: 940px }


/* Smartphones (portrait and landscape) ----------- */
@media only screen 
and (min-device-width : 320px) 
and (max-device-width : 480px) {
/* Styles */

.content {width :300px;  !important;}

}


/* ipad (portrait and landscape) ----------- */
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) {
/* Styles */

.content {width :700px;  !important;}

}


/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 20px;
}


 /* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}

.left {
  width: 45%;
}

.right {
  width: 55%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
	   /* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}



  container */
.responsive-two-column-grid {
    display:block;
}

/* columns */
.responsive-two-column-grid > * {
    padding:1rem;
}

/* tablet breakpoint */
@media (min-width:768px) {
    .responsive-two-column-grid {
        display: grid;
        grid-template-columns: 1fr 1fr;
    }
}


</style>
<div class="content">


 

  	  <h2> Economic Data Sources </h2>

	  Below you will find links to publicly avaialble data (mostly)  that I often utilize in my research and teaching. 
    
 <div class="row">
  <div class="column left">

 
 <h2>US</h2>

<ul>

<li> <a href="https://fred.stlouisfed.org/categories/" target="_blank"> FRED Economic Data</a> </li>

<li> <a href="https://www.ipums.org" target="_blank"> IPUMS</a> </li>

<li> <a href="https://www.bea.gov/data" target="_blank"> Bureau of Economic Analysis</a> </li>

 <li> <a href="https://www.bls.gov/data/" target="_blank"> Bureau of Labor Statistics</a> </li>

</ul>

<br>   <br>

<h2> India </h2>

<ul>


<li> <a href="https://esankhyiki.mospi.gov.in" target="_blank"> National Account Statistics</a> </li>


<li> <a href="https://rbi.org.in/Scripts/Statistics.aspx" target="_blank"> RBI Data Release</a> </li>


<li> <a href="https://rchiips.org/nfhs/" target="_blank"> National Family Health Survey (NFHS)</a> </li>

 
<li> <a href="https://ihds.umd.edu" target="_blank">India Human Development Survey (IHDS)</a> </li>

</ul>
</div>
  <div class="column right">

  <h2> International </h2>

<ul>


<li> <a href="https://www.rug.nl/ggdc/productivity/pwt/?lang=en" target="_blank"> Penn World Table</a> </li>

<li> <a href="https://ec.europa.eu/eurostat/web/main/data/database" target="_blank"> Eurostat	 </a> </li>

<li> <a href="https://stats.oecd.org" target="_blank"> OECDstat </a> </li>


<li> <a href="https://international.ipums.org/international/" target="_blank"> IPUMS International </a> </li>


<li> <a href="https://www.ibread.org/data-sets/" target="_blank"> BREAD </a> </li>


</ul>

	 <br>
<h2> China </h2>

<ul>


<li> <a href="https://www.stats.gov.cn/english/" target="_blank"> National Bureau of Statistics</a> </li>

<li> <a href="http://www.ciidbnu.org/chip/index.asp?lang=EN" target="_blank"> Chinese Household Income Project (CHIP) </a> </li>

<li> <a href="https://opendata.pku.edu.cn/dataverse/CFPS?language=en" target="_blank"> China Family Panel Studies</a> </li>

<li> <a href="https://www.cpc.unc.edu/projects/china" target="_blank"> China Health and Nutrition Survey (CHNS) </a> </li>


</ul>



</div>
</div>
