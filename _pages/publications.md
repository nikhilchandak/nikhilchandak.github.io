---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---



<style>

table {
  margin-bottom: 1rem;
  width: 100%;
  font-size: 85%;
  border: 0px solid $border-color;
  border-collapse: collapse;
}

td,
th {
  padding:  1rem .25rem;
  border: 0px solid $border-color;
}

th {
  text-align: left;
}

tbody tr:nth-child(odd) td,
tbody tr:nth-child(odd) th {
  background-color: transparent;
}

.message {
  /* background-color: transparent; */
  background-color: #f8f8f8; /* Light grey background */
  border-left: 4px solid #2c3e50; /* Vertical line to the left */
  padding: 15px; /* Adds space inside the borders */
  margin: 10px 0; /* Adds space outside the borders */
}

paper {
 color: #; 
 font-weight:bold;
}


/* #bibtex-chandak2023informed */
.bibtex {
  display: none; /* Keeps the BibTex hidden by default */
  background-color: #f9f9f9; /* Light background for the BibTex block */
  border: 1px solid #ddd; /* Adds a border around the BibTex block */
  padding: 10px; /* Adds space inside the BibTex block */
  margin-top: 10px; /* Adds space above the BibTex block */
  white-space: pre-wrap; /* Preserves formatting and wraps text */
  font-family: "Courier New", monospace; /* Sets font to monospace for code-like appearance */
}
/*
#bibtex-chandak2023informed pre {
  margin: 5px; /* Removes default margin from pre tag */
}
*/

</style>


You can also find my articles on my
<a href="https://scholar.google.com/citations?user=8_lfEOsAAAAJ&hl=en"> Google Scholar profile</a>.

<!--
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->


{% include base_path %}

## <a name="year2024"></a> 2024  

* [Proportional Aggregation of Preferences for Sequential Decision Making](https://arxiv.org/abs/2306.14858).     
    **Nikhil Chandak**, Shashwat Goel, Dominik Peters.\
      <i>AAAI Conference on Artificial Intelligence (AAAI)</i>, (in print), 2024.\
      <span style="color: red;"> Outstanding Paper Award </span> (Top 3 out of 12000+)
    <details>
                <summary>Abstract |  <a href="https://arxiv.org/abs/2306.14858">Arxiv</a> | <a href="https://youtu.be/kjZG89iDzuU">Video</a> | <a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('Bibtex') } else { $('#' + id).show('fast'); $(target).text('Bibtex▲') } })(this, 'bibtex-chandak2023proportional');">Bibtex</a> </summary>   
                  <p class="message">
                  We study the problem of fair sequential decision making given voter preferences. In each round, a decision rule must choose a decision from a set of alternatives where each voter reports which of these alternatives they approve. Instead of going with the most popular choice in each round, we aim for proportional representation. We formalize this aim using axioms based on Proportional Justified Representation (PJR), which were proposed in the literature on multi-winner voting and were recently adapted to multi-issue decision making. The axioms require that every group of α% of the voters, if it agrees in every round (i.e., approves a common alternative), then those voters must approve at least α% of the decisions. A stronger version of the axioms requires that every group of α% of the voters that agrees in a β fraction of rounds must approve β⋅α% of the decisions. We show that three attractive voting rules satisfy axioms of this style. One of them (Sequential Phragmén) makes its decisions online, and the other two satisfy strengthened versions of the axioms but make decisions semi-online (Method of Equal Shares) or fully offline (Proportional Approval Voting). The first two are polynomial-time computable, and the latter is based on an NP-hard optimization, but it admits a polynomial-time local search algorithm that satisfies the same axiomatic properties. We present empirical results for these rules based on synthetic data and U.S. political elections. We also run experiments using the moral machine dataset about ethical dilemmas. We train preference models on user responses from different countries and let the models cast votes. We find that aggregating these votes using our rules leads to a more equal utility distribution across demographics than making decisions using a single global preference model.
                  </p>
              </details>           
    <!-- [[arXiv](https://arxiv.org/abs/2306.14858)] -->
    <!-- [<a href="https://arxiv.org/abs/2306.14858">Arxiv</a> | <a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('bibtex') } else { $('#' + id).show('fast'); $(target).text('bibtex▲') } })(this, 'bibtex-chandak2023proportional');">bibtex</a>] --> 
    <!-- [[code](https://github.com/lunjohnzhang/warehouse_env_gen_nca_public)]   -->  
<div id="bibtex-chandak2023proportional" class="bibtex" style="display:none">
<pre>@article{chandak2023proportional,
  title={Proportional Aggregation of Preferences for Sequential Decision Making},
  author={Chandak, Nikhil and Goel, Shashwat and Peters, Dominik},
  journal={arXiv preprint arXiv:2306.14858},
  year={2023}
}
</pre></div>

## <a name="year2023"></a> 2023  

* [Informed Steiner Trees: Sampling and Pruning for Multi-Goal Path Finding in High Dimensions](https://ieeexplore.ieee.org/abstract/document/10243500/).          
   **Nikhil Chandak**, Kenny Chour, Sivakumar Rathinam, R. Ravi.            
    <i>IEEE Transactions on Automation Science and Engineering (T-ASE)</i>, 2023.   
    ICAPS PlanRobo Workshop 2023.
    <details>
                <summary>Abstract | <a href="https://arxiv.org/abs/2205.04548">Arxiv</a> | <a href="https://github.com/nikhilchandak/InformedSteinerTrees">Code</a> | <a href="https://youtu.be/-IcSHw5EfaU">Video</a> | <a href="javascript:void(0)" onclick="(function(target, id) { if ($('#' + id).css('display') == 'block') { $('#' + id).hide('fast'); $(target).text('Bibtex') } else { $('#' + id).show('fast'); $(target).text('Bibtex▲') } })(this, 'bibtex-chandak2023informed');">Bibtex</a> </summary>   
                  <p class="message">
                  We interleave sampling based motion planning methods with pruning ideas from minimum spanning tree algorithms to develop a new approach for solving a Multi-Goal Path Finding (MGPF) problem in high dimensional spaces. The approach alternates between sampling points from selected regions in the search space and de-emphasizing regions that may not lead to good solutions for MGPF. Our approach provides an asymptotic, 2-approximation guarantee for MGPF. We also present extensive numerical results to illustrate the advantages of our proposed approach over uniform sampling in terms of the quality of the solutions found and computation speed. 
                  </p>
    </details>

<div id="bibtex-chandak2023informed" class="bibtex" style="display:none">
<pre>@article{chandak2023informed,
  title={Informed steiner trees: Sampling and pruning for multi-goal path finding in high dimensions},
  author={Chandak, Nikhil and Chour, Kenny and Rathinam, Sivakumar and Ravi, Ramamoorthi},
  journal={IEEE Transactions on Automation Science and Engineering},
  year={2023},
  publisher={IEEE}
}
</pre>
</div>

<!--
    [[arXiv](https://arxiv.org/abs/2205.04548)]
    [[code]()]
    [[ICAPS 2023 PlanRobo Workshop - Oral Talk](https://youtu.be/-IcSHw5EfaU)]        
    <!-- [[publisher](https://doi.org/10.1007/s10514-023-10148-y)] --> 
