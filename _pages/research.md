---
permalink: /research/
title: "Research Topics"
---
## Machine Learning


<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Helvetica, sans-serif;
}

/* The actual timeline (the vertical ruler) */
.timeline {
  position: relative;
  max-width: 1200px;
  margin: 0 auto;
}

/* The actual timeline (the vertical ruler) */
.timeline::after {
  content: '';
  position: absolute;
  width: 6px;
  background-color: #a0c3ff;
  top: 0;
  bottom: 0;
  left: 10%;
  margin-left: -3px;
}

/* Container around content */
.container {
  padding: 10px 40px;
  position: relative;
  background-color: inherit;
  width: 70%;
}

/* The circles on the timeline */
.container::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 25px;
  right: -17px;
  background-color: white;
  border: 4px solid #ff8984;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

/* Place the container to the left */
.left {
  left: 0;
}

/* Place the container to the right */
.right {
  left: 10%;
}

/* Add arrows to the left container (pointing right) */
.left::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  right: 30px;
  border: medium solid white;
  border-width: 10px 0 10px 10px;
  border-color: transparent transparent transparent white;
}

/* Add arrows to the right container (pointing left) */
.right::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  left: 30px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent white transparent transparent;
}

/* Fix the circle for containers on the right side */
.right::after {
  left: -16px;
}

/* The actual content */
.content {
  padding: 20px 30px;
  background-color: #f5f5f5;
  position: relative;
  border-radius: 6px;
}

/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 600px) {
  /* Place the timelime to the left */
  .timeline::after {
  left: 31px;
  }
  
  /* Full-width containers */
  .container {
  width: 100%;
  padding-left: 70px;
  padding-right: 25px;
  }
  
  /* Make sure that all arrows are pointing leftwards */
  .container::before {
  left: 60px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent white transparent transparent;
  }

  /* Make sure all circles are at the same spot */
  .left::after, .right::after {
  left: 15px;
  }
  
  /* Make all right containers behave like the left ones */
  .right {
  left: 0%;
  }
}
</style>
</head>
<body>

<div class="timeline">
  <div class="container right">
    <div class="content">
      <h2>2017</h2>
      <p>Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua dignissim per, habeo iusto primis ea eam.</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2016</h2>
      <p>Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua dignissim per, habeo iusto primis ea eam.</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2015</h2>
      <p>Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua dignissim per, habeo iusto primis ea eam.</p>
    </div>
  </div>
  


</body>
</html>

We improve the peformance and scalability of machine learning algorithms on parallel high performance and cloud computing platforms.Our approach targets both theoretical aspects and systems engineering. 


* ASYNC ([pdf](http://www.paramathic.com/wp-content/uploads/2019/10/ASYNC.pdf "pdf"), [code](https://github.com/ASYNCframework/ASYNCframework "code")): A novel framework to support asycnhronous optimization on hetergenous platforms.

* DAve-QN ([pdf](http://www.paramathic.com/wp-content/uploads/2019/09/Dave-QN.pdf "pdf"), [code](https://github.com/DAve-QN/source "code")): the first asynchronous quasi-newton method with superlinear convergence.

* EFF-RES ([pdf](http://www.paramathic.com/wp-content/uploads/2019/09/Eff-res.pdf "pdf")): efficient distributed
algorithms for computing effective resistances in undirected networks.

* CA-SFISTA ([pdf](http://www.paramathic.com/wp-content/uploads/2019/09/CA-FISTA.pdf "pdf"), [code](https://github.com/saeedsoori/CA-Methods "code")): communication-avoiding algorithms for high performance computing. 


## Approximate Matrix Algorithms
Kernel methods in statistical learning and scientific computing can cause challenges such as inverting large matrices or solving an high dimensional linear system. We develop efficient frameworks to approximate these computations while satisfying user-specific accuracies.

* MatRox ([pdf](http://www.paramathic.com/wp-content/uploads/2019/10/MatRox.pdf "pdf"), [code](https://github.com/kobeliu85/MatRox_RU "code")): high-performance framework to efficiently compress and approximate matrix computations.


## Quantized Deep Learning

We develop scalable optimization algorithms for training deep neural networks on distributed platforms. We design novel quantizated stochastic algorithms to reduce the communication cost of transferred bits among GPUs in a cluster. We adpot data parallelism and MPI communication to build an effiecient message passing while preserving convergence rates.




