---
title: "Figures Included in the Botanical Homesis Testing Manuscript"
author: "Ying Jin"
date: "2026-05-13"
output: 
  html_document:
    number_section: true
    toc: true
    toc_depth: 3
    keep_md: true
---










```
## Joining with `by = join_by(sample_id)`
```

# Overall summarization


```
## 
##  Hormesis   U shape  Monotone Uncertain  No shape 
##       561       823       394        39      3043
```



![](ReportFigs/overall_sum_label-1.pdf)<!-- -->


## Scatterplot example of one assay


```
## Joining with `by = join_by(sample_id, sample_name, botanical_group,
## botanical_form, supplier, sample_lot, stock_form, `stock_solution_mg/ml`)`
```

![](ReportFigs/one_assay_scatter_exp-1.pdf)<!-- -->

![](ReportFigs/power_trans-1.pdf)<!-- -->

![](ReportFigs/log_trans-1.pdf)<!-- -->



## Table summary by botanical group (chemical) 

<table class="table" style="color: black; width: auto !important; margin-left: auto; margin-right: auto;">
<caption>Number of dose-response curves identified as hormesis, and percentage of hormesis curves out of all dose-reponse curves in each botanical group.</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Botanical Group </th>
   <th style="text-align:center;"> N (pct) </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Turmeric </td>
   <td style="text-align:center;"> 157 (58.15%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Ginkgo Biloba </td>
   <td style="text-align:center;"> 91 (18.72%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Goldenseal </td>
   <td style="text-align:center;"> 65 (12.04%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Gum Guggul </td>
   <td style="text-align:center;"> 53 (12.27%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Kava Kava </td>
   <td style="text-align:center;"> 39 (12.04%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Milk Thistle </td>
   <td style="text-align:center;"> 30 (6.17%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Resveratrol </td>
   <td style="text-align:center;"> 29 (17.9%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Grape Seed </td>
   <td style="text-align:center;"> 24 (11.11%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Annatto </td>
   <td style="text-align:center;"> 19 (2.93%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Citral </td>
   <td style="text-align:center;"> 13 (4.81%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Cedarwood Oil </td>
   <td style="text-align:center;"> 12 (11.11%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Chitosan </td>
   <td style="text-align:center;"> 12 (11.11%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Pine Bark </td>
   <td style="text-align:center;"> 6 (5.56%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Corn oil </td>
   <td style="text-align:center;"> 5 (4.63%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Comfrey Root </td>
   <td style="text-align:center;"> 2 (1.85%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Safflower oil </td>
   <td style="text-align:center;"> 2 (1.85%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Black Walnut </td>
   <td style="text-align:center;"> 1 (0.37%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Echinacea purpurea </td>
   <td style="text-align:center;"> 1 (1.85%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Olive oil </td>
   <td style="text-align:center;"> 0 (0%) </td>
  </tr>
</tbody>
</table>

## Table summary by assays




<table class="table" style="color: black; width: auto !important; margin-left: auto; margin-right: auto;">
<caption>Number of dose-response curves identified as hormesis, and percentage of hormesis curves out of all dose-reponse curves of each assay in each channel.</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Assay </th>
   <th style="text-align:left;"> luc </th>
   <th style="text-align:left;"> via </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> mixture-ahr-p1 </td>
   <td style="text-align:left;"> 16 (17.78%) </td>
   <td style="text-align:left;"> 10 (11.11%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-ar-mda-kb2-luc-agonist-p1 </td>
   <td style="text-align:left;"> 9 (10%) </td>
   <td style="text-align:left;"> 1 (1.11%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-ar-mda-kb2-luc-antagonist-p1 </td>
   <td style="text-align:left;"> 11 (12.22%) </td>
   <td style="text-align:left;"> 3 (3.33%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-aromatase-er-agonist-p1 </td>
   <td style="text-align:left;"> 9 (10%) </td>
   <td style="text-align:left;"> 8 (8.89%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-aromatase-er-antagonist-p1 </td>
   <td style="text-align:left;"> 18 (20%) </td>
   <td style="text-align:left;"> 5 (5.56%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-aromatase-er-aromatase-p1 </td>
   <td style="text-align:left;"> 20 (22.22%) </td>
   <td style="text-align:left;"> 8 (8.89%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-elg1-luc-agonist-p1 </td>
   <td style="text-align:left;"> 7 (7.78%) </td>
   <td style="text-align:left;"> 13 (14.44%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-er-luc-bg1-4e2-agonist-p1 </td>
   <td style="text-align:left;"> 7 (7.78%) </td>
   <td style="text-align:left;"> 4 (4.44%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-er-luc-bg1-4e2-antagonist-p1 </td>
   <td style="text-align:left;"> 7 (7.78%) </td>
   <td style="text-align:left;"> 4 (4.44%) </td>
  </tr>
</tbody>
</table>
<table class="table" style="color: black; width: auto !important; margin-left: auto; margin-right: auto;">
<caption>Number of dose-response curves identified as hormesis, and percentage of hormesis curves out of all dose-reponse curves of each assay in each channel.</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Assay </th>
   <th style="text-align:left;"> ratio </th>
   <th style="text-align:left;"> via </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> mixture-are-bla-p1 </td>
   <td style="text-align:left;"> 38 (42.22%) </td>
   <td style="text-align:left;"> 3 (3.33%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-hse-bla-p1 </td>
   <td style="text-align:left;"> 4 (4.44%) </td>
   <td style="text-align:left;"> 1 (1.11%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-mmp-p1 </td>
   <td style="text-align:left;"> 23 (25.56%) </td>
   <td style="text-align:left;"> 3 (3.33%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-p53-bla-p1 </td>
   <td style="text-align:left;"> 6 (6.67%) </td>
   <td style="text-align:left;"> 1 (1.11%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-pparg-bla-agonist-p1 </td>
   <td style="text-align:left;"> 2 (2.22%) </td>
   <td style="text-align:left;"> 8 (8.89%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-pparg-bla-antagonist-p1 </td>
   <td style="text-align:left;"> 6 (6.67%) </td>
   <td style="text-align:left;"> 9 (10%) </td>
  </tr>
</tbody>
</table>

<table class="table" style="color: black; width: auto !important; margin-left: auto; margin-right: auto;">
<caption>Number of dose-response curves identified as hormesis, and percentage of hormesis curves out of all dose-reponse curves of each assay at each time.</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Assay </th>
   <th style="text-align:left;"> 0h </th>
   <th style="text-align:left;"> 16h </th>
   <th style="text-align:left;"> 24h </th>
   <th style="text-align:left;"> 32h </th>
   <th style="text-align:left;"> 40h </th>
   <th style="text-align:left;"> 8h </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> mixture-rt-viability-hek293-flor-p1 </td>
   <td style="text-align:left;"> 9 (10%) </td>
   <td style="text-align:left;"> 9 (10%) </td>
   <td style="text-align:left;"> 10 (11.11%) </td>
   <td style="text-align:left;"> 11 (12.22%) </td>
   <td style="text-align:left;"> 13 (14.44%) </td>
   <td style="text-align:left;"> 9 (10%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-rt-viability-hek293-glo-p1 </td>
   <td style="text-align:left;"> 7 (7.78%) </td>
   <td style="text-align:left;"> 10 (11.11%) </td>
   <td style="text-align:left;"> 15 (16.67%) </td>
   <td style="text-align:left;"> 16 (17.78%) </td>
   <td style="text-align:left;"> 19 (21.11%) </td>
   <td style="text-align:left;"> 10 (11.11%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-rt-viability-hepg2-flor-p1 </td>
   <td style="text-align:left;"> 9 (10%) </td>
   <td style="text-align:left;"> 10 (11.11%) </td>
   <td style="text-align:left;"> 12 (13.33%) </td>
   <td style="text-align:left;"> 12 (13.33%) </td>
   <td style="text-align:left;"> 9 (10%) </td>
   <td style="text-align:left;"> 9 (10%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> mixture-rt-viability-hepg2-glo-p1 </td>
   <td style="text-align:left;"> 34 (37.78%) </td>
   <td style="text-align:left;"> 16 (17.78%) </td>
   <td style="text-align:left;"> 18 (20%) </td>
   <td style="text-align:left;"> 11 (12.22%) </td>
   <td style="text-align:left;"> 5 (5.56%) </td>
   <td style="text-align:left;"> 14 (15.56%) </td>
  </tr>
</tbody>
</table>


# Individual dose-response curves examples

- Hormesis: NCGC0037


```
## `geom_smooth()` using method = 'loess' and formula = 'y ~ x'
```

![](ReportFigs/shape_exp-1.pdf)<!-- -->


# Demonstration of how to use the scatterplot

## Subspace labels






![](ReportFigs/subspace-1.pdf)<!-- -->


## Chemical: Turmeric (lot 90H73) (NCGC00372872-01)

- ambigous: aromatase-er-aromatase-p1_luc
- no shape: elg1-luc-agonist-p1_luc
- hormesis, convex-increase: rt-viability-hek293-flor-p1_0h
- hormesis, concave-decrease: rt-viability-hepg2-glo-p1_0h
- U shape, concave: rt-viability-hek293-glo-p1_0h
- U shape, convex: 
- Monotone, increase: 
- Monoton decrease: mmp-p1_ratio

![](ReportFigs/scatter_demo_A-1.pdf)<!-- -->


```
## `geom_smooth()` using method = 'loess' and formula = 'y ~ x'
```

![](ReportFigs/scatter_demo_B-1.pdf)<!-- -->



# Examples of false negative due to insufficient dose grid






```
## iteration 1000
## iteration 1000
```


```
## iteration 1000
## iteration 1000
```

![](ReportFigs/false_negative-1.pdf)<!-- -->
