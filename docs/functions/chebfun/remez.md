---
title: "remez"
layout: function-reference-item
class_name: "chebfun"
function_name: "remez"
snippet: "Best polynomial or rational approximation."
qualifiers: ""
return_type: "varargout"
arguments: "(rhs1)"
---

<html>
   <head>
      <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
   
      <link rel="stylesheet" href="file:////Applications/MATLAB_R2013a.app/toolbox/matlab/helptools/private/helpwin.css">
      <title>MATLAB File Help: chebfun/remez</title>
   </head>
   <body>
      <!--Single-page help-->
      <table border="0" cellspacing="0" width="100%">
         <tr class="subheader">
            <td class="headertitle">MATLAB File Help: chebfun/remez</td>
            <td class="subheader-left"><a href="matlab:edit chebfun/remez">View code for chebfun/remez</a></td>
            <td class="subheader-right"><a href="matlab:helpwin">Default Topics</a></td>
         </tr>
      </table>
      <div class="title">chebfun/remez</div>
      <div class="helptext"><pre><!--helptext --> <span class="helptopic">remez</span>   Best polynomial or rational approximation.
    P = <span class="helptopic">remez</span>(F, M) computes the best polynomial approximation of degree M to
    the CHEBFUN F in the infinity norm using the Remez algorithm.
 
    [P, Q] = <span class="helptopic">remez</span>(F, M, N) computes the best rational approximation P/Q of type
    (M, N) to the CHEBFUN F using the Remez algorithm.
 
    [P, Q, R_HANDLE] = <span class="helptopic">remez</span>(F, M, N) does the same but additionally returns a
    function handle R_HANDLE for evaluating the rational function P/Q.
 
    [...] = <span class="helptopic">remez</span>(..., 'tol', TOL) uses the value TOL as the termination
    tolerance on the increase of the levelled error.
 
    [...] = <span class="helptopic">remez</span>(..., 'display', 'iter') displays output at each iteration.
 
    [...] = <span class="helptopic">remez</span>(..., 'maxiter', MAXITER) sets the maximum number of allowable
    iterations to MAXITER.
 
    [...] = <span class="helptopic">remez</span>(..., 'plotfcns', 'error') plots the error after each iteration
    while the algorithm executes.
 
    [P, ERR] = <span class="helptopic">remez</span>(...) and [P, Q, R_HANDLE, ERR] = <span class="helptopic">remez</span>(...) also returns
    the maximum error ERR.
 
    [P, ERR, STATUS] = <span class="helptopic">remez</span>(...) and [P, Q, R_HANDLE, ERR, STATUS] = <span class="helptopic">remez</span>(...)
    also return a structure array STATUS with the following fields:
       STATUS.DELTA  - Obtained tolerance.
       STATUS.ITER   - Number of iterations performed.
       STATUS.DIFFX  - Maximum correction in last trial reference.
       STATUS.XK     - Last trial reference on which the error equioscillates.
 
    This code is quite reliable for polynomial approximations but rather
    fragile for rational approximations.  Better results can often be obtained
    with CF(), especially if f is smooth.
 
  References:
 
    [1] Pachon, R. and Trefethen, L. N.  "Barycentric-Remez algorithms for best
    polynomial approximation in the chebfun system", BIT Numerical Mathematics,
    49:721-742, 2009.
 
    [2] Pachon, R.  "Algorithms for Polynomial and Rational Approximation".
    D. Phil. Thesis, University of Oxford, 2010 (Chapter 6).</pre></div><!--after help --><!--seeAlso--><div class="footerlinktitle">See also</div><div class="footerlink"> <a href="matlab:helpwin chebfun/cf">cf</a>.
</div>
      <!--Method-->
      <div class="sectiontitle">Method Details</div>
      <table class="class-details">
         <tr>
            <td class="class-detail-label">Access</td>
            <td>public</td>
         </tr>
         <tr>
            <td class="class-detail-label">Sealed</td>
            <td>false</td>
         </tr>
         <tr>
            <td class="class-detail-label">Static</td>
            <td>false</td>
         </tr>
      </table>
   </body>
</html>
