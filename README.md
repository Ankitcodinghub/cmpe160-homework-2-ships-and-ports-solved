# cmpe160-homework-2-ships-and-ports-solved
**TO GET THIS SOLUTION VISIT:** [CMPE160 Homework 2-Ships and Ports Solved](https://www.ankitcodinghub.com/product/cmpe160-homework-2-ships-and-ports-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93980&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPE160 Homework 2-Ships and Ports Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="section">
<div class="layoutArea">
<div class="column">
&nbsp;

1. Description

<pre>Hi, there. Welcome to the second project where you will be learning
the fundamentals of OOP. In this project, you are required to
implement a simulation of a port management system. The main objective
is to analyze the requests provided in input and carry out the
necessary actions.
</pre>
<pre>There are ports, and ships are sailing between them. Ships are
carrying the following types of containers: basic, heavy,
refrigerated, liquid, and each of them should be handled differently.
Containers in a port can be loaded to ships, and, conversely, they can
be unloaded from a ship to port.  Ships need a certain amount of fuel
to sail from one port to another.
</pre>
<pre>Note that there is no user interaction during the execution, the
program parses the input file composed of the sequential operations.
</pre>
<pre>Also, as a significant remark, the signature of the methods and the
field names that you are going to implement should be identical to the
ones that are specified in this document. If a specific method
signature is not enforced by the project description, you can feel
free to implement it in your way (i.e. you can implement extra methods
considering your own design choice). However, you should also consider
the proper usage of access modifiers for preserving the desired
visibility and accessibility throughout the project. In other words,
you should not define everything as “public”, which results in a
penalty if done so.
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
2. Class Hierarchy and Details

You are already provided with the following interfaces: ● IShip.java

● IPort.java

<pre>Do not modify the code in these files! You are responsible for all the
compilation errors that originated from the changes made in any of
these classes including the addition or removal of libraries.
</pre>
<pre>In addition, you are given a part of the Main class. You are required
to complete the Main class with the instructions given later in this
document. The other files are just empty. Using the fundamentals of
the object-oriented programming methodology and the inheritance
principles, you are expected to fill in these files in a suitable
manner to complete the project. Do not forget that you are free to
create new packages, classes, or interfaces. However, the class names
and properties that are given below should be exactly the same in your
projects. Please note that, if you fail to follow this instruction,
you do not get any points as your projects will be automatically
graded.
</pre>
<pre>Before CMPE 160, there was a single source file and all the functions
were implemented in that file. However, in this project, there will be
multiple classes that interact with each other during execution.
Therefore, before starting the implementation, you are advised to
allocate some time to understand the main logic behind the design and
the relation among the code pieces.
</pre>
<pre>Within the scope of this project, you are expected to implement these
classes (which will be explained in detail in the rest of this
document):
</pre>
1. Main.java

2. Port.java

3. Ship.java

4. Container.java

5. BasicContainer.java

6. HeavyContainer.java

7. RefrigeratedContainer.java 8. LiquidContainer.java

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>The class hierarchy that you must consider during the implementation
is illustrated in the class diagram below:
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Main.java

<pre>The main method simply reads an input file that is composed of
sequential commands related to the operations. You can use this class
to test your code. Scanners for input and output files and the array
lists defined below are given for you.
</pre>
<pre>You are required to read from an input file and print to an output
file, names of which are passed to your program as arguments. Apart
from unit tests to test your code and class structure, we will use the
Main class to test your code for various inputs and outputs.
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
Input Format

In the first line, there is a number N, which represents the total number of events that occur during the simulation.

In the following N lines, the actions are specified in their customized format as described below. In other words, each distinct line represents an event with a specific action in the port management system. Please note that the test cases will not cover any erroneous input with regards to the format.

<pre>The possible actions are encoded through separate numbers:
</pre>
<ol>
<li>Creating a container</li>
<li>Creating a ship</li>
<li>Creating a port</li>
<li>Loading a container to a ship</li>
<li>Unloading a container from a ship</li>
<li>Ship sails to another port</li>
<li>Ship is refueled</li>
</ol>
1. When creating a container, three or four inputs are given depending on the type of container. The first input represents the id of the port where that container should be placed initially. Note that there will not be a test case where a port of that id has not been created yet. The next input is a non-zero positive integer, denoting the weight of that container. Depending on the weight you need to decide the type of container:

● Weight&lt;=3000:BasicContainer

● Otherwise:HeavyContainer

The special type of heavy container is given as “R” or “L”, which stand for Refrigerated and Liquid, respectively. There may or may not be an “R” or “L” after weight. It is important to note that Refrigerated and Liquid Containers are special types of HeavyContainer, meaning that input lines that contain “R” or “L” should always create the respective type of container regardless of the weight. The ID of a container is determined by the simulation and should be unique to each container. In other words, no two containers can have the same ID, even if one of them is a basic one and the other a heavy/refrigerated/liquid one. Successive numbers should be assigned as IDs according to the

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
order of adding them to the simulation by starting indexing from 0, such that the first container must have the ID 0 and the second 1 and so on.

Example:

<pre>   1 0 500 means that a 500kg BasicContainer(500&lt;=3000) should be
   placed at the 0th port
   1 1 3500 R means that a 3500kg RefrigeratedContainer(3500&gt;3000)
   should be placed at 1st port
</pre>
<ol start="2">
<li>When creating a ship six positive integers are given:
<ul>
<li>● &nbsp;TheIDoftheportwheretheshipinitiallyis</li>
<li>● &nbsp;Maximumweightofallcontainersinthatship
(nonzero)
</li>
<li>● &nbsp;Maximumnumberofallcontainersinthatship (counting all types of containers) (maybe zero)</li>
<li>● &nbsp;Maximumnumberofheavycontainersinthatship (counting refrigerated and liquid containers) (maybe zero)</li>
<li>● &nbsp;Maximumnumberofrefrigeratedcontainersinthatship (maybe zero)</li>
<li>● &nbsp;Maximumnumberofliquidcontainersinthatship (maybe zero)
A nonzero positive double is the 7th input denoting the fuel consumption per km of that ship.

Example:

2 0 10000 10 5 3 4 50.00 means that a ship should be created at the 0th port that can hold at most 10 containers (regardless of type), 5 heavy, 3 refrigerated, and 4 liquid containers. This ship also spends 50.00 fuel per km while it travels from one port to another.

Note that there will not be a test case like this: 2 0 10000 10 0 3 4 because if there can be no heavy containers, there cannot be any refrigerated/liquid ones either.

2 0 10000 10 0 0 0 30.00 means that this ship may contain only BasicContainers (at most 10). This ship also spends 30.00 fuel per km while it travels from one port to another.
</li>
</ul>
</li>
<li>When creating a port, two double inputs are given, which are the x and y coordinates of the port. The IDs of the ports are also determined by the simulation.

Example:

<pre>   3 40.00 50.00 means that a port should be created with the
   coordinates (40.00, 50.00)
</pre>
</li>
</ol>
</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
<ol start="4">
<li>When loading a container into a ship, IDs of ship and container are given. A container with that ID will always exist but may or may not be in the port where the ship currently is. Ship with the given ID will always exist. If the container is currently in the port, it may or may not be loaded into the ship depending on the restrictions of that ship.
Example:

<pre>   The ship with ID 0 was created with the following line
   2 0 14000 10 5 4, and currently has 2 BasicContainers, 3
   HeavyContainers, 2 RefrigeratedContainers, 0 LiquidContainers.
   The sum of all containers above is 11500 kg.
   4 0 1 means that container 1 should be loaded into the ship 0.
   Consider the following cases about container 1:
</pre>
<ul>
<li>● &nbsp;ItisaHeavyContainer:Loadingisnotpossible,asthere are already 5 heavy containers (3 + 2 + 0).</li>
<li>● &nbsp;ItisaRefrigeratedContainer:Loadingisnotpossible,as there are already 5 heavy containers (3 + 2 + 0).</li>
<li>● &nbsp;ItisaLiquidContainer:Loadingisnotpossible,asthere are already 5 heavy containers (3 + 2 + 0).</li>
<li>● &nbsp;ItisaBasicContainer:Loadingpossibleifweightisless than or equal to 2500 (14000 – 11500 = 2500)</li>
</ul>
</li>
<li>When unloading a container from a ship, IDs of ship and container are given. A container with that ID will always exist but may or may not be on the ship. Ship with the given ID will always exist. If a container with the given ID exists in a ship, it will be placed into the storage of the port where the ship currently is. Example:
<pre>   Ship 0 is in port 3 and contains containers 1,2,3.
   5 0 1 means that container 1 should be unloaded from ship 0. In
   this case, this is possible, as container 1 exists in ship 0.
   Thus, container 1 will now be located in the storage of port 3.
</pre>
</li>
<li>When ships travel from one port to another, IDs of the ship and destination port are given. Fuel consumption of the ship consists of the value that was given in the creation stage and consumption of containers. We will provide more information about how fuel consumption is calculated in the following sections. In short, if a ship has enough fuel it will sail to the destination port. Example:
<pre>   6 0 1 means that ship 0 should travel to port 1 if it has enough
   fuel.
</pre>
</li>
</ol>
</div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
7. When fuel is added to a ship, the ID of the ship and amount of fuel is given. The fuel amount is a nonzero positive double. Example:

7 0 30.20 means 30.2 amount of fuel should be added to existing fuel of ship 0.

Output Format

<pre>You must print the ships in the ports list in the main class with
their attributes. Please note that the double values should have 2
digits after the fraction point. The output format should be ordered
in ascending order of the port IDs, while in each port, the ships
should be also ordered according to their IDs. A port should be
printed as “Port ID: (x, y)”, followed by IDs of containers located in
the port: “{BasicContainer, HeavyContainer, RefrigeratedContainer,
LiquidContainer}: [IDLIST]”. You should also list all ships located in
that port as “Ship ID: FUEL_LEFT”. Additionally, containers in each
ship should be listed too. Please, refer to example output for a
better understanding of output format. Note that port and ship
contents are indented with 2 whitespaces. Order of containers types
matter and should be as follows: Basic, Heavy, Refrigerated, Liquid.
</pre>
<pre>Example Output:
</pre>
<pre>Port 0: (100.00, 200.00)
  BasicContainer: 13 14
  HeavyContainer: 12
  LiquidContainer: 23
  Ship 1: 370.74
</pre>
<pre>    BasicContainer: 1 2
    HeavyContainer: 0
    RefrigeratedContainer: 3
    LiquidContainer: 4
</pre>
<pre>  Ship 2: 150.54
    BasicContainer: 5 6 7
    HeavyContainer: 8 9
    LiquidContainer: 10 11
</pre>
<pre>Port 1: (120.60, 250.00)
  BasicContainer: 15 16 17 18
  LiquidContainer: 20 21
  Ship 0: 260.00
</pre>
<pre>    BasicContainer: 19
    RefrigeratedContainer: 22
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>I have replaced whitespaces with # to illustrate them. The correct
output obviously should not contain #s.
</pre>
<pre>Port 0: (100.00, 200.00)
##BasicContainer: 13 14
##HeavyContainer: 12
##LiquidContainer: 23
##Ship 1: 370.74
####BasicContainer: 1 2
####HeavyContainer: 0
####RefrigeratedContainer: 3
####LiquidContainer: 4
##Ship 2: 150.54
####BasicContainer: 5 6 7
####HeavyContainer: 8 9
####LiquidContainer: 10 11
Port 1: (120.60, 250.00)
##BasicContainer: 15 16 17 18
##LiquidContainer: 20 21
##Ship 0: 260.00
####BasicContainer: 19
####RefrigeratedContainer: 22
</pre>
Port.java

<pre>Port class should have the following variables, exactly named as
below:
</pre>
<ul>
<li>● &nbsp;intID</li>
<li>● &nbsp;doubleX</li>
<li>● &nbsp;doubleY</li>
<li>● &nbsp;ArrayList&lt;Container&gt;containers</li>
<li>● &nbsp;ArrayList&lt;Ship&gt;history:keepstrackofeveryshipthathas
visited
</li>
<li>● &nbsp;ArrayList&lt;Ship&gt;current:keepstrackoftheshipscurrentlyhere
<pre>Port must implement the IPort interface and the methods it requires.
The class should have the following methods, exactly as named below:
</pre>
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="section">
<div class="layoutArea">
<div class="column">
<ul>
<li>● &nbsp;Aconstructorwiththreeparameters,ID,X,andY.</li>
<li>● &nbsp;Amethodthatcalculatesthedistancebetweentheobjectitself
<pre>     and another Port, double getDistance(Port other)
</pre>
<pre>Additionally, the choice of defining the variables as private,
protected, or public may require additional getter and setter methods.
This applies to all other classes as well, unless specified otherwise.
</pre>
Ship.java

<pre>Ship class should have the following variables, exactly named as
below:
</pre>
● intID

● doublefuel

● PortcurrentPort

<pre>Ship must implement the IShip interface and the methods it requires.
The class should have the following methods, exactly as named below:
</pre>
</li>
</ul>
<ul>
<li>● &nbsp;publicShip(intID,Portp,inttotalWeightCapacity,int maxNumberOfAllContainers, int maxNumberOfHeavyContainers, int maxNumberOfRefrigeratedContainers, int maxNumberOfLiquidContainers, double fuelConsumptionPerKM)</li>
<li>● &nbsp;ArrayList&lt;Container&gt;getCurrentContainers():shouldreturnthe list of all containers currently in the ship sorted by ID.
Container.java

Container is an abstract class and should have the following fields: ● intID

● intweight

<pre>It should have the following methods:
</pre>
</li>
</ul>
<ul>
<li>● &nbsp;AconstructorwithparametersID,weight</li>
<li>● &nbsp;doubleconsumption():shouldreturnfuelconsumptionrequiredby
<pre>     the container
</pre>
</li>
<li>● &nbsp;booleanequals(Containerother):checktype,IDandweightofa
<pre>     container. If they are the same, return true, otherwise return
     false.
</pre>
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="section">
<div class="layoutArea">
<div class="column">
BasicContainer.java and HeavyContainer.java

<pre>They should extend the Container class. They should have a constructor
with two inputs like a Container.
</pre>
● WeightofaBasicContainer&lt;=3000

● WeightofaHeavyContainer:otherwise

Fuel consumption is as follows:

● BasicContainer:2.50perunitofweight ● HeavyContainer:3.00perunitofweight

RefrigeratedContainer.java and LiquidContainer.java

<pre>They are special types of HeavyContainer and should extend the
HeavyContainer class. They should have a constructor with two inputs
like a HeavyContainer.
</pre>
Fuel consumption is as follows:

● RefrigeratedContainer:5.00perunitofweight ● LiquidContainer:4.00perunitofweight

3. Interface Details

IPort.java

<pre>You are already provided with this interface. Do not modify the code
in this file! It contains the following method:
</pre>
● voidincomingShip(Ships):shouldaddthisshiptocurrent ArrayList.

● voidoutgoingShip(Ships):shouldaddthisshiptohistory ArrayList.

Note that there should not be any duplicates in the current and history ArrayLists (i.e. do not add the same ship to history if it has already visited that port before)

IShip.java

<pre>You are already provided with this interface. Do not modify the code
in this file! It contains the following method:
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="section">
<div class="layoutArea">
<div class="column">
<ul>
<li>● &nbsp;booleansailTo(Portp):returnstrueifashipsuccessfully sailed to the destination port</li>
<li>● &nbsp;voidreFuel(doublenewFuel):addsfueltoaship</li>
<li>● &nbsp;booleanload(Containercont):returnstrueifacontainerwas
<pre>     successfully loaded to a ship
</pre>
</li>
<li>● &nbsp;booleanunLoad(Containercont):returnstrueifacontainerwas
<pre>     successfully unloaded from a ship
</pre>
</li>
</ul>
</div>
</div>
</div>
</div>
