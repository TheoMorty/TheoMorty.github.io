---
title: Running a shop
layout: post
author: theo.mortensen
permalink: /running-a-shop/
source-id: 1oCrs5Np6shN7Eh3BDnxNMUthFpbIyEmIYM339UfLHzA
published: true
---
Recently on google sheets I have been running a shop. We have had to use interesting coding to find out what we want to get and a sale price. For this we used vlookup and functions like sum. As well as data validation to have an inside search bar. For the coding of vlookup

, =iferror(VLOOKUP(G12,$A$2:$B$19,2, FALSE), ) ,

This allows if any problems occur it just comes up with nothing. For the sales you will need to use tons of coding. It will come out like this =if(J21>=J22,SUM(J19)*(1-K19),J19)

This come out with the sale price. And this is my result far:

