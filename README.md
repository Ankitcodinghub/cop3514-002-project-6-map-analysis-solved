# cop3514-002-project-6-map-analysis-solved
**TO GET THIS SOLUTION VISIT:** [COP3514.002 Project #6-Map analysis Solved](https://www.ankitcodinghub.com/product/cop3514-002-project-6-map-analysis-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100344&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COP3514.002 Project #6-Map analysis Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Project #6: Map analysis

</div>
</div>
<div class="layoutArea">
<div class="column">
Task description:

In this project, you must obtain different information about a mapped territory. The territory map is represented by a 2D matrix, and each cell in this matrix represents an area of one square mile (each side is one mile in length). These cells can be either land (L) or water (W), as illustrated in the figure below.

WWWWW WLLLL WLLLL WWLLL WWWWW

Your task is to create two files: “coast.txt” and “statistics.txt”. The file “coast.txt” must show the location of coast cells, which are land cells that share at least one side with a water cell. Coast cells must be marked with ‘Y’ and other cells with ‘N’. Please consider any space outside the mapped area as water. The coast cells for the map above are shown below.

NNNNN NYYYY NYNNY NNYYY NNNNN

Finally, the file “statistics.txt” must contain the total map area, the total land area, and the “wet perimeter” (i.e., the length of land in direct contact with the water). For the map above, the total map area is 25 square miles, the total land area is 11 square miles, and the wet perimeter is 14 miles.

Execution specification:

Your program will be run with one command-line argument, which defines the text file with the input map. For instance, a program named “a.out” will be executed as follows:

<pre>./a.out [input_file.txt]
</pre>
where “input_file.txt” will be replaced with the name of the map file.

Input specification:

The map file starts with one line with two integers R and C representing the number of rows and columns in the map (1 ≤ R,C ≤ 1000). Each of the next R lines contains C characters indicating the cell type: ‘W’ for water and ‘L’ for land. You must read the input from the file indicated as a command-line argument!

Output specification:

For the file “coast.txt”, print R lines, each containing C characters indicating if its respective cell in the input map is a coast cell or not. Use ‘Y’ to mark coast cells, and ‘N’ for any other cell. Do not forget the new-line character at the end of each row.

For the file “statistics.txt”, print three lines respectively showing the total map area, the total land area, and the wet perimeter. See the examples below to learn the expected format.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Example #1:

Command

<pre> ./a.out maps/1.txt
</pre>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input file: maps/1.txt

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Output file: coast.txt

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Output file: statistics.txt

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
55 LLLLL LWWWL WWWWW LWWWW LLWWL

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>YYYYY
YNNNY
NNNNN
YNNNN
YYNNY
</pre>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>TOTAL AREA: 25
TOTAL LAND AREA: 11
WET PERIMETER: 28
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Example #2:

Command

<pre> ./a.out maps/2.txt
</pre>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input file: maps/2.txt

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Output file: coast.txt

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Output file: statistics.txt

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
55 WWWLL WWWLL WWWLL WWWLL WWWLL

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>NNNYY
NNNYY
NNNYY
NNNYY
NNNYY
</pre>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>TOTAL AREA: 25
TOTAL LAND AREA: 10
WET PERIMETER: 14
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Example #3:

Command

<pre> ./a.out maps/3.txt
</pre>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Input file: maps/3.txt

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Output file: coast.txt

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Output file: statistics.txt

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>10 10
WWWWWWLLLL
WWWWWWLLLL
WWWWWWWLLL
LLWWWWWWLL
LLLLWWWWWL
WWWWWLLWWW
WWWWWLLLWW
WWWWWWLLWW
LLWWWWLLWW
LLLWWWLLWW
</pre>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>NNNNNNYYYY
NNNNNNYNNY
NNNNNNNYNY
YYNNNNNNYY
YYYYNNNNNY
NNNNNYYNNN
NNNNNYNYNN
NNNNNNYYNN
YYNNNNYYNN
YYYNNNYYNN
</pre>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>TOTAL AREA: 100
TOTAL LAND AREA: 36
WET PERIMETER: 56
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
