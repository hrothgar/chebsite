---
title: "get"
layout: function-reference-item
class_name: "chebfun"
function_name: "get"
snippet: "GET method for the CHEBFUN class"
qualifiers: ""
return_type: "out"
arguments: "(f, prop)"
---

<html>
   <head>
      <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
   
      <link rel="stylesheet" href="file:////Applications/MATLAB_R2013a.app/toolbox/matlab/helptools/private/helpwin.css">
      <title>MATLAB File Help: chebfun/get</title>
   </head>
   <body>
      <!--Single-page help-->
      <table border="0" cellspacing="0" width="100%">
         <tr class="subheader">
            <td class="headertitle">MATLAB File Help: chebfun/get</td>
            <td class="subheader-left"><a href="matlab:edit chebfun/get">View code for chebfun/get</a></td>
            <td class="subheader-right"><a href="matlab:helpwin">Default Topics</a></td>
         </tr>
      </table>
      <div class="title">chebfun/get</div>
      <div class="helptext"><pre><!--helptext --> <span class="helptopic">get</span>   <span class="helptopic">get</span> method for the CHEBFUN class
    P = <span class="helptopic">get</span>(F, PROP) returns the property P specified in the string PROP from
    the CHEBFUN F. Valid entries for the string PROP are:
        'DOMAIN'         - The domain of definintion of F.
        'FUNS'           - The piecewise smooth components of F.
        'VSCALE'         - Vertical scale of F.
        'VSCALE-LOCAL'   - Local vertical scales of F.
        'HSCALE'         - Horizontal scale of F.
        'HSCALE-LOCAL'   - Local horizontal scales of F.
        'ISHAPPY'        - Is F happy?
        'EPSLEVEL'       - Approximate accuracy estimate of F.
        'EPSLEVEL-LOCAL' - Approximate accuracy estimate of F's components.
        'LVAL'           - Value(s) of F at lefthand side of domain.
        'RVAL'           - Value(s) of F at righthand side of domain.
        'LVAL-LOCAL      - Value(s) of F's FUNs at left sides of their domains.
        'RVAL-LOCAL'     - Value(s) of F's FUNs at right sides of their domains.
        'EXPS'           - Exponents in a CHEBFUN, a two vector.
        'EXPONENTS'
        'DELTAS'         - Return the locations and magnitude of delta functions
        'DELTAFUNS'        as a single matrix with the first row corresponding to
        'DELTAFUNCTIONS'   the locations of the delta functions, and the
                           magnitudes appended below the first row.
        'IMPS'           - Same as DELTAS, supported for backward compatability.
    The following are also supported for backward compatabiilty, and really only
    make sense when the CHEBFUN is represented by a CHEBTECH-type object. Note
    that in these cases a cell is always returned, even if the Chebfun has only
    a sngle FUN.
        'POINTS'         - The Chebyshev grid used to represent F.
        'VALUES'         - The values of the CHEBFUN on the grid above.
        'COEFFS'         - The corresponding Chebyshev coefficients.</pre></div><!--after help -->
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