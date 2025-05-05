# ee451-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [EE451 Assignment 1 Solved](https://www.ankitcodinghub.com/product/ee451-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100466&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE451 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
EE 451

1. Examples

<ul>
<li>A matrix-vector multiplication example code, “example.c”, which multiplies a mat-rix with a vector is provided. To compile “example.c”,
1 gcc -O3 -o run example.c
</li>
<li>A matrix-matrix multiplication example code framework “problem1.c”; you can either insert your codes into it or write the whole program by yourself. To compile “problem1.c”,1 gcc -O3 -o run example.c</li>
<li>To run the compiled program in hpc,1 srun -n1 ./run</li>
<li>Initialize the matrices: A[i][j] = i, B[i][j] = i + j, C[i][j] = 0, for any 0 ≤ i, j &lt; n. Programming homework</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
After the computation, print out the value of C[100][100]. Refer to “problem1.c”. 2. Naive Matrix Multiplication

</div>
</div>
<div class="layoutArea">
<div class="column">
• Native Matrix Multiply

Implement the naive matrix multiplication to multiply two matrices of dimension 4K ×

</div>
</div>
<div class="layoutArea">
<div class="column">
4K.IRmeporltetmhe exnectutCion=timAe (inBns)(aAnd,pBer,foCrmanrce (nin FLnOPmS).atrixes)

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
for i = 1 to n

for j = 1 to n

for k = 1 to n

C(i,j) = C(i,j) + A(i,k)  B(k,j)



</div>
</div>
<div class="layoutArea">
<div class="column">
C(i,j)

</div>
</div>
<div class="layoutArea">
<div class="column">
=

</div>
</div>
<div class="layoutArea">
<div class="column">
A(i,:)

</div>
</div>
<div class="layoutArea">
<div class="column">
B(:,j)

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: Naive Matrix Multiplication

12

3. Block Matrix Multiplication

A matrix can be viewed to be constructed by bigger blocks. Assume an n × n matrix is

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Programming homework

</div>
</div>
<div class="layoutArea">
<div class="column">
partitioned into m × m blocks and each block is a b × b matrix ,where b = mn , b is called

</div>
</div>
<div class="layoutArea">
<div class="column">
the block size. As shown in Figure 2, a 4×4 (n = 4) matrix can be viewed as a 2×2

(m = 2) block matrix; each block matrix is a 2 × 2 (b = 2) matrix. • Blocked Matrix Multiply

</div>
</div>
<div class="layoutArea">
<div class="column">
The matrix can be partitioned into four 2×2 blocks Figure 2: Block Matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
Programming homework The partitioned matrix can then be written as

</div>
</div>
<div class="layoutArea">
<div class="column">
• Blocked Matrix Multiply

Block matrix multiplication computes the output block by block. Figure 3 depicts

</div>
</div>
<div class="layoutArea">
<div class="column">
the principle of Block Matrix Multiplication. Here, the algorithm has m iterations C = A  B, Consider A,B,C to be N-by-N matrices of b-by-b

</div>
</div>
<div class="layoutArea">
<div class="column">
as oppose to n3 iterations for Naive Matrix Multiplication; the computation of each sub-blocks, where b=n / N is called the block size

</div>
</div>
<div class="layoutArea">
<div class="column">
iteration is based on blocks rather than a single element for Naive Matrix Multiplication.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 3: Block Matrix Multiplication

Use block matrix multiplication to solve the previous problem with block size b = 4,8,16 respectively. Report the execution time (in ns) and performance (in FLOPS) respectively. Compare the result against the result obtained by using naive matrix multiplication. Report your observation.

4. Submission

• Two .c/.cpp files: ‘problem1a.c’ for naive matrix multiplication; ‘problem1b.c’ for

block matrix multiplication. Make sure your program is runnable. (10+20 pts) • Screenshot of the execution time and performance on hpc.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
for i = 1 to m for j = 1 to m

</div>
<div class="column">
13

</div>
</div>
<div class="layoutArea">
<div class="column">
for k = 1 to m //do a matrix multi. on blocks C’(i,j) = C’(i,j) + A’(i,k) * B’(k,j)



</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
A’(i,:)

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td colspan="1" rowspan="4"></td>
<td></td>
<td colspan="1" rowspan="4">
<div class="layoutArea">
<div class="column">
B’(:,j)

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
C’(i,j)

</div>
</div>
<div class="layoutArea">
<div class="column">
=

</div>
</div>
</div>
</div>
</div>
