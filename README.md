#Using the self-organizing map for prioritizing invasive species

The self-organizing map (SOM) is a computational-intelligence technique that can be used to identify, from a large list of potential hazards, <b>which species present the most risk to target areas with respect to their potential for establishment</b>. Furthermore, such analyses may indicate <b>donor and recipient regions for pest invasion</b> and can highlight previously unknown or ignored threats for further investigation.  

The SOM analysis consists of two parts:
<ul>
  <li type="disc">The SOM algorithm itself, which is essentially a clustering algorithm that can be used to prioritize species with respect to their potential for establishment in a target area
</li>
  <li type="disc">SOM validation and quantification of uncertainty</li>
</ul>
<br>


##Get SOM

The code used in our lab require to install the commercial software  <a href="http://au.mathworks.com">Matlab</a>, as well as the <a href="http://www.cis.hut.fi/somtoolbox">Matlab SOM Toolbox 2.0</a>.

SOM Toolbox 2.0, a software library for Matlab 5 implementing the Self-Organizing Map algorithm is Copyright (C) 1999 by Esa Alhoniemi, Johan Himberg, Jukka Parviainen and Juha Vesanto.

If you want a comprehensive introduction to Matlab, the MathWorks website <a href="http://au.mathworks.com/help/matlab/getting-started-with-matlab.html">Getting started with matlab</a> offers a number of introductory videos and a pdf tutorial entitled Getting Started with MATLAB. 
<br>


##Setup
<ol>
  <li> Download SOM Toolbox 2.0</li>
  <li>addpath(genpath('SOM-Toolbox'))</li>
</ol>
This will add SOM-Toolbox and all subfolders into matlab path.
<br>


##Documentation
<ul>
  <li type="disc">User guide – covers how to collect and format your data, configuration of SOM, running and analysis</li>
  <li type="disc">Cookbook – How to carry out various tasks that often come up in relation to SOM when used for a pest risk assessment</li>
</ul>

If you are interested in using SOM within the context of a pest risk assessment or for futur research, then feel free to contact <a href="mailto:Mariona.Roige@lincolnuni.ac.nz">Mariona Roige</a>. Depending on what you need, she might be able to assist you.


##Development
