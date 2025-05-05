# java-lab-3-solved
**TO GET THIS SOLUTION VISIT:** [Java Lab 3 Solved](https://www.ankitcodinghub.com/product/java-lab-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95414&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Java Lab 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Lab 3

[valid 2020-2021]

The Tourist Trip Planning Problem

A tourist is about to visit a city. In this city, there are various locations such as tourism sites, hotels and restaurants, parks, etc. Locations have names and may have other common properties (such as a description, an image, coordinates, etc). Dependin g on its type, each location has various specific properties. However, if the location is

a visitable, it must have opening hours. If the location is payable, it must have the entry fee (the price of the ticket). If the location is classifiable, it must have a classification (a rank).

The time (in minutes) required to go from one location to another is known. The tourist has also preferences regarding the order in which he (or she) would like to visit some locations.

Example: locations are: v1 (Hotel) v2 (Museum A) v3 (Museum B) v4 (Church A) v5 (Church B) v6 (Restaurant).

From-ToCost

v1→v2 10 v1→v3 50 v2↔v3 20 v2→v4 20 v2→v5 10 v3→v4 20 v4↔v5 30 v4→v6 10 v5→v6 20

The main specifications of the application are:

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Compulsory (1p)

<ul>
<li>Create an object-oriented model of the problem. You should have at least the following classes City, Hotel, Museum, Church, Restaurant. The natural ordering of their objects is given by their names.</li>
<li>Create the interfaces Visitable, Payable, Classifiable. The classes above must implement these interfaces accordingly.</li>
<li>The City class will contain a List of locations.</li>
<li>Each location will contain a Map representing the times required to go from
this location to others.
</li>
<li>Create all the objects given in the example.
Optional (2p)
</li>
</ul>
<ul>
<li>In the City class, create a method to display the locations that are visitable and are not payable, sorted by their opening hour.</li>
<li>Create default methods in the interface Visitable, with the opening hour 09:30 and the closing hour 20:00.</li>
<li>Create a static method getVisitingDuration,in the interface Visitable, that returns a Duration object, representing how long a location is opened during a day.</li>
<li>Create the class TravelPlan. An instance of this class will contain a city and the preferences regarding the visiting order.</li>
<li>Implement an efficient agorithm to determine the shortest path between two given locations, conforming to the preferences.
Bonus (2p)
</li>
</ul>
<ul>
<li>Suppose that the tourist has a specific number of days available to visit the city and every day he (or she) has the same number of minutes available for visiting.</li>
<li>Suppose that there is a special start location (the hotel) – the tourist must start and end a daily trip in this location.</li>
<li>Implement an algorithm that will create a plan (a trip for each day), such that the tourist visits as many locations as possible.</li>
<li>Test your algorithm using JUnit or other framework.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Resources

<ul>
<li>The Java Tutorials: Interfaces</li>
<li>The Java Tutorials: Collections ( Know Thy Complexities! )</li>
<li>The Java Tutorials: Generics</li>
<li>The Date-Time package
Objectives
</li>
</ul>
<ul>
<li>Create interfaces to describe specifications.</li>
<li>Create multiple implementations of an interface.</li>
<li>Understand the differences between abstract classes and interfaces.</li>
<li>Use packages to organize the classes and intefaces of the application.</li>
<li>Use collections and generics.</li>
<li>Use lambda-expressions and streams.</li>
<li>Understand the space-time tradeoff of various types of collections.</li>
</ul>
</div>
</div>
</div>
