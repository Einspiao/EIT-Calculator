# EIT-Response-Calculator

## Abstract

This is a package enabling user to calculate EIT response of a 4-level system (atomic ensemble and a coupling qubit in an interacting Rydberg state), and compare it to a 3-level system (atomic ensemble without such a coupling qubit). This is the main outcome of a semester project under [Prof. Wenchao Xu](https://iqe.phys.ethz.ch/people/person-detail.Wenchao-Xu.html) 's supervision.

## User Manual

To use the package, first install it through

```pip install Rydberg-EIT-Calculator```

in the terminal. Then import with

```from Rydberg-EIT-Calculator import start```.

To this time the package is available to use. Just execute

```start()```

and the calculator interface will appear. To use the interface:

* In the first interface, please set the parameters with the dashboard in the lower-right corner. Drag the indicator to set the parameters. Then click "set parameters" button to draw the EIT response.

* After having the EIT response drawn on the canvas, the user is allowed to select a measuring point by just click on the canvas. Then a simulation of photon distribution is shown in the second interface. To re-select a measuring point, close the second interface and repeat the first step.
