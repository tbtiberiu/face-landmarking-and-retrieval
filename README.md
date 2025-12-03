# Face landmark localization on the Siblings Database (retrieval)

Dataset: [SiblingsDB](https://cgvg.polito.it/siblingsDB.html)
This repository contains code for face landmark localization on the Siblings Database using a retrieval-based approach.

## Requirements
- Python 3.x
- OpenCV
- NumPy
- scikit-learn
- matplotlib

## Metrics
The performance of the landmark localization is evaluated using ME17 which is the mean distance between 17 internal facial points located by the search and the corresponding manually landmarked points, divided by the distance between the manual eye pupils. The landmark points chosen are the following: eye corners (4), eyelids (8), mouth corners (2), upper and lower lip points (2), and nose tip (1).

Comparison to methods used in the paper that introduces the Siblings Database [[1](#references)]:
- Milborrow, S.: Active shape models with Stasm. http://www.milbo.users.sonic.net/stasm/
- Milborrow, S., Nicolls, F. (2008). Locating Facial Features with an Extended Active Shape Model. In: Forsyth, D., Torr, P., Zisserman, A. (eds) Computer Vision – ECCV 2008. ECCV 2008. Lecture Notes in Computer Science, vol 5305. Springer, Berlin, Heidelberg. https://doi.org/10.1007/978-3-540-88693-8_37

## References
[1] [T.F. Vieira, A. Bottino, A. Laurentini, M. De Simone, Detecting Siblings in Image Pairs, The Visual Computer, 2014, vol 30, issue 12, p. 1333-1345, doi: 10.1007/s00371-013-0884-3](https://link.springer.com/article/10.1007/s00371-013-0884-3)