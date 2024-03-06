# Lines between boxes

## The Problem

We need to identify which boxes are connected by roughly straight, hand drawn lines.

For example, in the image `Lines-Between-Boxes.png` lines have been drawn between the following boxes:

- Aspirin and Foxglove
- Digitalis and Willow

### Numering


Columns are identified by L for Left and R for Right.

Boxes are numbered from top to bottom. So, the top box would be 1, the second would be 2, etc.

To identify a box, we'd use the column followed by the box number.

For example, in the image `Lines-Between-Boxes.png`, on the left they would be:

- L1
- L2

and on the right they would be:

- R1
- R2
- R3
- R4



## The Solution

Needs to return the identification of the boxes that are connected by lines. These identifications should be separated by a hyphen.

For example, in the image `Lines-Between-Boxes.png` the solution should return:

- L1-R1
- L2-R4


### Test data

The solution should work for

- `Lines-Between-Boxes.png`

The next stage of the solution would be to generalise to the remaining test data. E.g. `data/1-1_1-4.jpg`


