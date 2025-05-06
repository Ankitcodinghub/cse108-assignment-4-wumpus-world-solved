# cse108-assignment-4-wumpus-world-solved
**TO GET THIS SOLUTION VISIT:** [CSE108 Assignment 4-Wumpus World Solved](https://www.ankitcodinghub.com/product/cse108-assignment-4-wumpus-world-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96926&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE108 Assignment 4-Wumpus World Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<strong>Wumpus World</strong>

Wumpus world is a popular grid game. The grid is a 4×4 array of cells. The bottom left cell is [0,0] and the top right cell is [3,3]. In any of these 16 cells, there can be:

&nbsp;

<ol>
<li>Wumpus</li>
<li>Pit</li>
<li>Gold</li>
</ol>
&nbsp;

If you want to survive in this world, you have to get to the gold and hold it above your head to announce your victory. You do not know where the gold is. You may think scanning the whole grid would suffice to win, but the Wumpus and the Pit are there to stop you.

&nbsp;

There is a Wumpus in the grid. The Wumpus is a smelly blind creature that devours souls when someone is in the same cell with it. It gives away a terrible smell, and if you are right by its cell, you will experience a stench.

&nbsp;

There is a Pit in the grid. (The original version of the game can have any number of pits. For simplicity, we assume that there is only one pit). If you step in the Pit, you will have to rot there forever! However, you can always feel a breeze if you are right by the Pit.

&nbsp;

As a player, you start from [0,0], moving upwards. You have the following moves:

&nbsp;

<ol>
<li>Turn Right: Changes your moving direction</li>
<li>Turn Left: Changes your moving direction</li>
<li>Move Forward: Move to the next cell along the moving direction</li>
<li>Shoot: You have 3 arrows with you. You can shoot the arrow at your moving direction. If the Wumpus is in that direction, it will scream loudly in pain and die. But if it is behind you, you cannot touch it. You have to turn around before shooting to kill it.</li>
</ol>
&nbsp;

You are given a C++ skeleton code that (nearly) implements the above scenario. You have to complete the code.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<strong>Tasks:</strong>

&nbsp;

<strong>Part A:</strong>

&nbsp;

Study the given skeleton carefully before going into the following tasks.

&nbsp;

<ol>
<li>void Position::moveRight() : moves a certain position to the cell immediately to its right. Modify it so that the position cannot go beyond the grid.</li>
<li>void Position::moveLeft() : moves a certain position to the cell immediately to its left. Modify it so that the position cannot go beyond the grid.</li>
<li>void Position::moveUp() : moves a certain position to the cell immediately above it. Modify it so that the position cannot go beyond the grid.</li>
<li>void Position::moveDown() : moves a certain position to the cell immediately below it. Modify it so that the position cannot go beyond the grid.</li>
<li>bool Position::isAdjacent(Position p) : implement the function. It returns true if two are adjacent. Two cells are adjacent if they are side by side. Note that [0,0] and [1,1] are not adjacent.</li>
<li>bool isSamePoint(Position p) : implement the function. It returns true if two cells are the same.</li>
<li>Wumpus::Wumpus() : implement this default constructor of Wumpus class so that it initialized the position randomly within the grid, and sets it to alive.</li>
<li>Player::Player() : implement this default constructor of Player class. All necessary information are already given in the game description.</li>
<li>void Player::turnLeft() : implement this function. It changes the direction of the player as follows:</li>
</ol>
&nbsp;

<table width="576">
<tbody>
<tr>
<td width="288">Before</td>
<td width="288">After</td>
</tr>
<tr>
<td width="288">UP</td>
<td width="288">LEFT</td>
</tr>
<tr>
<td width="288">LEFT</td>
<td width="288">DOWN</td>
</tr>
<tr>
<td width="288">DOWN</td>
<td width="288">RIGHT</td>
</tr>
<tr>
<td width="288">RIGHT</td>
<td width="288">UP</td>
</tr>
</tbody>
</table>
&nbsp;

<ol>
<li>void Player::turnRight() : implement this function. Figure out how the direction is affected by yourself.</li>
</ol>
&nbsp;

<ol>
<li>void Player::moveForward() : implement this function. The player moves to the next cell along the direction.</li>
</ol>
&nbsp;

<ol>
<li>WumpusWorld::WumpusWorld() : implement this default constructor. It will initialize the Wumpus, the Pit and the Gold at random positions.</li>
</ol>
&nbsp;

<ol>
<li>WumpusWorld::WumpusWorld(int wumpus_x, int wumpus_y) : implement this parameterized constructor. This is like the default constructor, only the location of the Wumpus is provided here.</li>
</ol>
&nbsp;

<ol>
<li>WumpusWorld::WumpusWorld(int wumpus_x, int wumpus_y, int gold_x, int gold_y) : implement this constructor. Here, all information except that of the Pit is delivered.</li>
</ol>
&nbsp;

<ol>
<li>void WumpusWorld::shoot() : implement this function. This takes effect when a player shoots. Give proper messages if the player hits or misses.</li>
</ol>
&nbsp;

<strong>&nbsp;</strong>

<strong>Part B:</strong>

&nbsp;

This is more of a planning and implementing task. The code that you now have works just fine (given that you have implemented it properly), except for the part of the Pit. There is no Pit in the code now. Implement the concept of Pit in your code. Identify the functions that need to be modified to do so. Modify those functions. You must think in object-oriented way and implement in object-oriented way.

<strong>Restrictions:</strong>

&nbsp;

You cannot use any 2D array for the assignment. You cannot change the encapsulations that have been enforced in the given skeleton code.

&nbsp;

<strong><em><u>You must not copy anyone’s code. If copy is found, it will be made sure that you fail in the course.</u></em></strong>

&nbsp;

<strong>Input Specifications: </strong>

&nbsp;

Take input from a file. The file will have size integers, x and y positions of the Wumpus, the Gold and the Pit respectively. All six integers will be within (0..3) inclusive.

&nbsp;

Note: you must take input from a file. Simply using cin and cout will not suffice.

&nbsp;
