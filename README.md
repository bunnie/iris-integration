![logo](https://bunniefoo.com/iris/iris-logo-gh.png)

# IRIS Integration Recommendations

The purpose of this repository is to provide a set of recommendations and standards for building systems that are "IRIS-ready".

## What is IRIS?

IRIS stands for "Infra-Red, In-Situ". It is a method to establish evidence-based trust that a given silicon chip has been manufactured correctly. It uses infra-red light to "see through" the back side of chips that conform the the recommendations in this repository. With this technique we can reveal the patterns of metal that are in intimate contact with the transistors on a chip and thus establish that a significant portion of the chip is correctly constructed.

![IRIS quick demo](https://bunniefoo.com/iris/visible_to_ir_zoom.gif)

A basic IRIS inspection like the loop shown above can be done at home using simple, off-the-shelf parts easily purchased online. See [this video guide](https://bunniefoo.com/iris/iris_at_home.mp4) for an example of how to modify a camera to do IRIS.

A more precise version of IRIS can be done using a 3D motion platform to control a camera. You can [read more here](https://bunnie.org/iris).

## Why Are there Integration Recommendations?

Not all chips are inspectable by IRIS by default. Some chips *are* inspectable, but this is probably by coincidence. The purpose of the integration recommendations is to provide a set of guidelines for hardware manufacturers who wish to facilitate IRIS inspections.

## Specifications

* [Chip specifications](./chip-specifications.md)
* [System specifications](./system-specifications.md)

## Acknowledgements

This work was funded in part by NLnet’s [NGI0 Entrust](https://nlnet.nl/entrust/) fund, established with support from the European Commission’s Next Generation Internet Program, and my [Github Sponsors](https://github.com/sponsors/bunnie/).

![NLnet Logo](https://bunniefoo.com/iris/2024/nlnet-logos.png)