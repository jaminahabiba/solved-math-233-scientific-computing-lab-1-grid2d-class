Download Link: https://assignmentchef.com/product/solved-math-233-scientific-computing-lab-1-grid2d-class
<br>
<ol>

 <li>Create a new C++ project.</li>

 <li>In this new project, create a new class named Grid2D. It will be used to represent 2dimensional grids with <em>N </em>× <em>M </em>points uniformly distributed over [<em>x</em><sub>min</sub><em>,x</em><sub>max</sub>] × [<em>y</em><sub>min</sub><em>,y</em><sub>max</sub>]. Nodes will be numbered according to the standard ”z-ordering”. ∆<em>x,</em>∆<em>y </em>will be the spatial resolutions.</li>

 <li>In which file should that class be defined? (hint: modularity ……)</li>

 <li>In the Grid2D class, define <em>N,M,x</em><sub>min</sub><em>,x</em><sub>max</sub><em>,y</em><sub>min</sub><em>,y</em><sub>max</sub><em>,</em>∆<em>x,</em>∆<em>y </em>as private variables. What types should they be? Why should they be private?</li>

 <li>Implement a constructor Grid2D(N<em>,</em>M<em>,</em>x<sub>min</sub><em>,</em>x<sub>max</sub><em>,</em>y<sub>min</sub><em>,</em>y<sub>max</sub>]) that initialize the grid with the prescribed parameters and initialize the resolutions ∆<em>x,</em>∆<em>y</em>.</li>

 <li>Write two public functions ifromn(int n) and jfromn(int n) that take the index n of a grid point and return its logical coordinates (i<em>,</em>j) on the grid.</li>

 <li>Write the reverse function nfromij(int i<em>,</em>int j)<em>.</em></li>

 <li>Write a function xfromn(int n), that take the index of a node and return its position in the direction. Write the same function for the y-direction.</li>

 <li>Use the outputVTK<em>.</em>txt file to implement two functions initializeVTKfile and printQuantityintoVTKfile that create a vtk file with the grid information and output the values of a given quantity (defined on that grid) in a specified vtk file.</li>

 <li>Install paraview.</li>

 <li>Write a main file that

  <ul>

   <li>Create a Grid2D with your choice of parameters</li>

   <li>Create a vector of size <em>N </em>× <em>M </em>representing the function cos(<em>x</em>)cos(<em>y</em>) over the grid.</li>

   <li>Output the grid and the vector into one .vtk file</li>

  </ul></li>

 <li>Open your file in paraview. Does it look right?</li>

 <li>(Further reading) what is the difference between a class and a struct?</li>

</ol>