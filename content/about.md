---
title: "About StoX"
description: ""
draft: false
---

## An open source approach to acoustic and swept area survey calculations.

StoX is an open source software developed at IMR, Norway to calculate survey estimates from acoustic and swept area surveys.

The program is a stand-alone application built in Java for easy sharing and further development in cooperation with other institutes. The underlying high resolution data matrix structure ensures future implementations of e.g. depth dependent target strength and high resolution length and species information collected with camera systems. 

Despite the complexity, the execution of an index calculation can easily be governed from a user interface with an interactive GIS module, or by accessing the Java function library and parameter set using external software like R. Accessing StoX projects from R is an efficient way of processing time series or performing boot-strapping on one dataset, where for each run, the content of the parameter dataset is altered.

{{< figure src="/img/stox_map.jpg#center" title="StoX map interface" >}}
