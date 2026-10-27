# Introduction to SPSS

Materials for NC State University Libraries' SPSS session (Data Science Services), a general
introduction we can teach in any class. Students reach SPSS through the Virtual Computing Lab (VCL), check the variables in a
sample employee survey, and run descriptive statistics, a crosstab with a chi-square test, a
correlation, a one-way ANOVA and a simple linear regression, then export their output.

The guide is online at https://go.ncsu.edu/dss-intro-spss (which redirects to
https://ncsu-libraries.github.io/intro-spss/spss-workshop.html).

- `spss-workshop.qmd`: the guide we work from in the session. Steps to do in SPSS, the VCL or the
  browser are in blue boxes; everything else is explanation. `spss-workshop.html` is the rendered,
  self-contained page.
- `data/TeachingData.sav`: the sample data, ABC Insurance's employee survey (936 employees,
  9 variables): simulated company data from SAGE Research Methods, modified for this session
  (see Data source below).
- `data/SPSS Codebook.xlsx`: the codebook: each variable's name, type, label, values and measure.
  The guide's codebook section (section 2) has the same content, so students don't download it.

Render the guide with `quarto render spss-workshop.qmd`.

All pictures in `images/` are our own screenshots of SPSS and the VCL.

## Data source

The sample data is adapted from:

Arseneault, R. (2023). *Learn to use descriptive statistics in SPSS to interrogate large employee
HR data sets with simulated company data*. In *Sage Research Methods: Business*. SAGE Publications
Ltd. https://doi.org/10.4135/9781529629477

We modified the original dataset and adapted its codebook for this session, so
`data/TeachingData.sav` and `data/SPSS Codebook.xlsx` aren't identical to the versions on SAGE.
