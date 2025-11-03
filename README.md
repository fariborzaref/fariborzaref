<div align="center">

<h1>Dr. Fariborz Aref</h1>
<h3>Sociologist | Computational Methods | Research Methodologist</h3>

United States  |  🌐 <a href="https://fariborzaref.com">fariborzaref.com</a>  |  📧 <a href="mailto:fariborz.aref@gmail.com">fariborz.aref@gmail.com</a>

<br/>

<a href="https://orcid.org/0000-0001-6622-1824">
  <img alt="ORCID" src="https://img.shields.io/badge/ORCID-0000--0001--6622--1824-4caf50?logo=orcid&logoColor=white&labelColor=2e7d32&style=flat-square">
</a>

<br/><br/>

<a href="#profile">Profile</a> •
<a href="#methods">Methods</a> •
<a href="#featured-repositories">Featured Repositories</a> •
<a href="#reproducibility">Reproducibility</a> •
<a href="#background">Background</a> •
<a href="#metrics">Metrics</a>

</div>

<hr/>

<h3 id="profile">Profile</h3>
<p>
I study how inequality evolves within and across societies by combining sociological theory, computational modeling, and careful empirical design.  
My work turns complex data into transparent, replicable evidence that informs theory, teaching, and policy.
</p>

<hr/>

<h3 id="methods">Methods</h3>

<b>Analytical toolkit</b><br/>
• Generalized Estimating Equations  • Linear Mixed Models  • Panel Time Series  • Multilevel and Longitudinal Analysis  • Confirmatory Factor and Structural Equation Modeling

<b>Software and computation</b><br/>
• R  • Python  • Stata  • SPSS  • SQL  • LaTeX  • Markdown  • OJS  • Git

<b>Substantive domains</b><br/>
• Global inequality  • Social policy  • Education and labor markets  • Computational sociology  • Quantitative and qualitative integration

<details>
<summary><b>Toolchain details</b></summary>
<br/>
<b>R stacks</b><br/>
geepack • lme4 • lmerTest • lavaan • semTools • panelvar • fixest • data.table • ggplot2<br/><br/>
<b>Reproducibility</b><br/>
Project oriented repos with session info, version pins, and saved artifacts for full replication.
</details>

<hr/>

<h3 id="featured-repositories">Featured Repositories</h3>

<table>
<tr>
<td width="50%" valign="top">
<b><a href="https://github.com/fariborzaref/R_GEE">R_GEE</a></b><br/>
Population average models for clustered social data using GEE. Includes diagnostics, robust SEs, and example notebooks.
</td>
<td width="50%" valign="top">
<b><a href="https://github.com/fariborzaref/LMM">LMM</a></b><br/>
Random effects models for cross national inequality trajectories with tidy pipelines and visual checks.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<b><a href="https://github.com/fariborzaref/CFA_SEM">CFA_SEM</a></b><br/>
Latent structure modeling for income, health, and labor outcomes with lavaan templates and fit audit helpers.
</td>
<td width="50%" valign="top">
<b><a href="https://github.com/fariborzaref/TSM">TSM</a></b><br/>
Time series and panel VAR utilities for comparative social research, shock response, and stability analysis.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<b><a href="https://github.com/fariborzaref/Models">Models</a></b><br/>
A compact library of advanced social science model patterns with minimal reproducible examples.
</td>
<td width="50%" valign="top">
<b><a href="https://github.com/fariborzaref/GEE_Plot">GEE_Plot</a></b><br/>
Publication grade plots and diagnostics for geeglm outputs with clean defaults.
</td>
</tr>
</table>

<hr/>

<h3 id="reproducibility">Reproducibility</h3>

<p><b>Minimal quick start in R</b></p>

```r
# clone one of the repos, then inside the project:
pkgs <- c("geepack","lme4","lmerTest","lavaan","semTools","panelvar","fixest","data.table","ggplot2")
to_install <- setdiff(pkgs, rownames(installed.packages()))
if (length(to_install)) install.packages(to_install)
source("scripts/00_setup.R")
rmarkdown::render("analysis/01_demo.Rmd")



