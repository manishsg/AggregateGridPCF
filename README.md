# Aggregate Grid PCF
PCF control grid to find aggregate of selected column directly from SubGrid

Nomrally we have to export to excel to  find aggregates of numeric columns in a subgrid, Now with this PCF control you can do this directly from Subgrids.
# Steps
1. Import control solution.

2. Enable Aggregate Grid for rquired subgrids.

![alt text](https://github.com/nijos/AggregateGridPCF/blob/master/Grid.JPG)

3. Done select columns to view SUM, Count, Avg.

![alt text](https://github.com/nijos/AggregateGridPCF/blob/master/ezgif.com-gif-maker.gif).

Only numeric and currency fields are considered.

 # Note:
 This is not a  production ready control and has not follweed all the best practices, consider this as POC only.
 you are always welcome to commit enhancements to this repo.
 
 Known bugs.
 1. Count is considering null values also.
 2. NAN error on some scenarios.
 
 CSS and Design Courtesy: Hovering details list by Power Maveric: https://github.com/Power-Maverick/PCF-Controls/tree/master/HoverDetailsList



If this helped you, consider supporting my PCF freebies [![Support via PayPal](https://cdn.rawgit.com/twolfson/paypal-github-button/1.0.0/dist/button.svg)](https://paypal.me/nijojosephraju?locale.x=en_GB)
