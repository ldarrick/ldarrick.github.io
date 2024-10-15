---
layout: default
indent: false
permalink: /
---


<!-- <head>
<style>
.repara {
    display: inline-block;
    margin-left: auto;
    margin-right: auto;
    width: 30.0%;
    @include media-query($small-screen) {
      width: 80.0%;
    };
   	padding: 20px;
}

.path {
    display: inline-block;
    margin-left: auto;
    margin-right: auto;
   	width: 13.5%;
   	padding: 20px;
}

#images{
    text-align:center;
}
</style>
</head> -->


### About {#about}
I am currently a [Chancellor's Fellow](https://www.ed.ac.uk/human-resources/job/chancellors-fellowships) in the [School of Mathematics](https://www.maths.ed.ac.uk/school-of-mathematics) at the University of Edinburgh. Previously, I was a postdoc in the Mathematical Institute at the University of Oxford as part of the [CIMDA-Oxford collaboration](https://cimda-oxford.datasig.ac.uk/) with [Harald Oberhauser](https://people.maths.ox.ac.uk/oberhauser/) and a postdoc in the [Laboratory for Topology and Neuroscience](https://www.epfl.ch/labs/hessbellwald-lab/) at EPFL with [Kathryn Hess](https://www.epfl.ch/labs/hessbellwald-lab/hessbellwald/). I received my PhD in [Applied Mathematics and Computational Sciences (AMCS)](https://www.amcs.upenn.edu/) in 2021 at the University of Pennsylvania working under [Rob Ghrist](https://www.math.upenn.edu/~ghrist/). Before that, I received my Bachelor of Applied Sciences at the University of British Columbia in 2016, where I majored in [Engineering Physics](http://www.engphys.ubc.ca/) with an Electrical Engineering specialization and minored in Mathematics. 

I received a [Fulbright Canada student award](https://www.fulbright.ca/programs/canadian-students/traditional-awards.html) for 2016-2017 and a [NSERC PGS-D scholarship](http://www.nserc-crsng.gc.ca/Students-Etudiants/PG-CS/BellandPostgrad-BelletSuperieures_eng.asp) for 2018-2021.

My CV is [here]({{site.url}}/cv/CV.pdf).


<!------------------------------------------------------------------------------------------------>

### Research {#research}

I am interested in developing mathematics at the interface of topology, geometry, and analysis in order to build novel tools to study functional data. Currently, most of my work revolves around applications and generalizations of the path signature from a topological and geometric point of view. 

For 2024-2025, Sjoerd Beentjes, Emily Roff and I are organizing the [Applied Geometry, Algebra, and Topology in Edinburgh (AGATE) seminar](https://agatedinburgh.github.io/).  


<!------------------------------------------------------------------------------------------------>

<!-- # Research Interests {#research}
I am broadly interested in algebraic topology and category theory, particularly in how these fields motivate a different point of view on approaching problems in data science.

More specifically, I study <b>Chen's iterated integral cochain model</b> for path spaces and how these cochains may be considered as the semantics of multivariate time series data by providing interpretable and computable features. The 0-cochains in this model for the path space of $\mathbb{R}^n$ form a collection of functions called <b>path signatures</b>, which offer a <b>reparametrization-invariant</b> characterization of paths. I am interested in further developing tools derived from path signatures, understanding how higher cochains may be leveraged, and considering how generalizations of Chen's cochain model to mapping spaces may provide methods to study more complex parametrized data.

A motivating example of path signatures is provided below, and a more complete survey can be found in my [expository paper](https://arxiv.org/abs/1811.03558) with [Chad Giusti](http://www.chadgiusti.com/).

### Path Signatures - A Motivating Example

For example, suppose we wish to detect leading/lagging relationships between two different time series, denoted $\gamma_1(t)$ (dark colors) and $\gamma_2(t)$ (light colors). A classical technique is the unbiased [cross-correlation](https://en.wikipedia.org/wiki/Cross-correlation) $r\[\gamma_1, \gamma_2\](t_d)$, where $t_d$ denotes the time delay. The cross-correlation can readily detect such behavior when the time series are of the same form (the blue curves on the left represent two sine waves off by a time delay) by locating the local maxima of the cross-correlation near the origin (circled point in blue on the right). The fact that the local maximum occurs at a negative time delay $t_d$ implies that $\gamma_1$ is leading $\gamma_2$. However, this indicator disappears once the time series are reparametrized (the animations depict a family of reparametrizions (left) and the corresponding cross-correlations (right) in red).
<div id="images">
    <img class="repara" alt="Time Series" src="{{ site.url }}/img/rp_ts.gif"/>
    <img class="repara" alt="Cross Correlation" src="{{ site.url }}/img/rp_xcorr.gif"/>
</div>​
A reparametrization-invariant leading indicator is the <b>signed area</b> enclosed by the path defined by the time series (the ellipse on the right). The signed area is the area bounded by the curve, taking into account the multiplicity of the area (in this case, 4), and the orientation (in this case, counterclockwise, corresponding to a positive signed area). A positive signed area can be interpreted as an indicator that $\gamma_1$ is leading $\gamma_2$. Note that since reparametrization of the path does not change the image of the path, the signed area is reparametrization-invariant. Additionally, the signed area can be calculated as a linear combination of path signature terms.
<div id="images">
    <img class="repara" alt="Time Series" src="{{ site.url }}/img/rp_tspath.gif"/>
    <img class="timeseries" alt="Cross Correlation" src="{{ site.url }}/img/rp_path.gif"/>
</div>​
For general multivariate time series, we compute the signed area for every pair of time series to obtain pairwise leading/lagging indicators. This was originally studied by [Y. Baryshnikov and E. Schlafly](https://ieeexplore.ieee.org/document/7798498).  -->


<!------------------------------------------------------------------------------------------------>
### Preprints
0. [Ergodic trajectory optimization on generalized domains using maximum mean discrepancy](https://arxiv.org/abs/2410.10599), C. Hughes, H. Warren, <b>D. Lee</b>, F. Ramos, I. Abraham    
(preprint) (2024)    
0. [The surface signature and rough surfaces](https://arxiv.org/abs/2406.16857), <b>D. Lee</b>    
(preprint) (2024)    
0. [Random surfaces and higher algebra](https://arxiv.org/abs/2311.08366), <b>D. Lee</b> and H. Oberhauser    
(preprint) (2023)
0. [The signature kernel](https://arxiv.org/abs/2305.04625), <b>D. Lee</b> and H. Oberhauser    
(preprint of book chapter) (2023)
0. [Path signatures on Lie groups](https://arxiv.org/abs/2007.06633), <b>D. Lee</b> and R. Ghrist   
(preprint) (2020)
0. [A methodology for morphological feature extraction and unsupervised cell classification.](https://www.biorxiv.org/content/10.1101/623793v1)  D. Bhaskar, <b>D. Lee</b>, H. Knútsdóttir, C. Tan, M. Zhang, P. Dean, C. Roskelley, and L. Edelstein- Keshet  
(preprint) (2019)



### Publications {#publications}

0. [A topological approach to mapping space signatures](https://www.sciencedirect.com/science/article/pii/S0196885824001192), C. Giusti, <b>D. Lee</b>, V. Nanda, and H. Oberhauser    
Advances in Applied Mathematics. (2025) [[arXiv]](https://arxiv.org/abs/2202.00491)
0. [Stein variational ergodic search](https://arxiv.org/abs/2406.11767), <b>D. Lee</b>, C. Lerch, F. Ramos, I. Abraham    
Robotics: Science and Systems (2024)
0. [Signatures, Lipschitz-free spaces, and paths of persistence diagrams](https://epubs.siam.org/doi/10.1137/22M1528471), C. Giusti and <b>D. Lee</b>    
SIAM Journal on Applied Algebra and Geometry. (2023) [[arXiv]](https://arxiv.org/abs/2108.02727)
0. [Signature methods for brain-computer interfaces](https://www.nature.com/articles/s41598-023-41326-8), X. Xu, <b>D. Lee</b>, N. Drougard, and R. N. Roy    
Scientific Reports. (2023)
0. [Convex hulls of curves: volumes and signatures](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_45), C. Améndola, <b>D. Lee</b>, and C. Meroni    
In: Nielsen, F., Barbaresco, F. (eds) Geometric Science of Information. GSI 2023. Lecture Notes in Computer Science, vol 14071. Springer, Cham. (2023) [[arXiv]](https://arxiv.org/abs/2301.09405)
0. [Capturing graphs with hypoelliptic diffusions](https://openreview.net/pdf?id=KtDdr1zUE_1), C. Toth, <b>D. Lee</b>, C. Hacker, and H. Oberhauser    
Advances in Neural Information Processing Systems (NeurIPS) (2022) [[arXiv]](https://arxiv.org/abs/2205.14092)
0. [Iterated integrals and population time series analysis](https://link.springer.com/chapter/10.1007/978-3-030-43408-3_9), C. Giusti and <b>D. Lee</b>  
In Nils A. Baas, Gunnar E. Carlsson, Gereon Quick, Markus Szymik, and Marius Thaule, editors, Topological Data Analysis, Abel Symposia, pages 219–246 (2020) [[arXiv]](https://arxiv.org/abs/1811.03558)
0. [Structure of vortex-bound states in spin singlet chiral superconductors](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.93.064522), <b>D. Lee</b> and A. Schnyder  
Physical Review B. 93: 064522 (2016) [[arXiv]](https://arxiv.org/abs/1508.05331)
0. [Localization for transversally periodic random potentials on binary trees](https://www.ems-ph.org/journals/show_abstract.php?issn=1664-039X&vol=6&iss=3&rank=4), R. Froese, <b>D. Lee</b>, C. Sadel, W. Spitzer, and G. Stolz  
Journal of Spectral Theory. 6: 557-600 (2016) [[arXiv]](https://arxiv.org/abs/1408.3961)
{: reversed="reversed"}



<!------------------------------------------------------------------------------------------------>

### Teaching {#teaching}

#### EPFL
* <b>Fall 2021</b> TA for MATH 220: Metric and Topological Spaces

#### University of Pennsylvania
* <b>August 2020</b> Co-Instructor for Pre-Freshman Program 
* <b>Spring 2018</b> TA for MATH 241: Calculus IV (Partial Differential Equations)  
* <b>Fall 2017</b> TA for MATH 360:  Advanced Calculus (Real Analysis)  
<span style="font-size:90%">Math Department Good Teaching Award</span>

