# Lab 11 - Numpy Arrays

Author: *Kassie Bradshaw*

Collaborators: *Glenn Clark*, *Garfield Grant*

[Link to GitHub PR]

[Link to Google Colab]

## Overview

Today we'll be constructing chess boards like it's 1980. No prebuilt images, just the power of arrays and pixel art.

## Feature Tasks & Requirements

Your job is to render out chess boards with red and blue queens on them.

We're keeping it really basic here so the only pieces are queens and each queen is represented by a blue or a red square.

Chess board is an 8 by 8 grid of alternating black and white squares. The queens are red and blue squares.

Each board will have one red and one blue queen at different coordinates. In addition to displaying the board you'll need to identify if the queens are "under attack" based on their coordinates.

### Implementation Notes

* [x] Define a `ChessBoard` class - should contain an 8x8 grid - each cell in grid should have a color represented in RGB format.
  * [x] Should have an `add_red` method that accepts a row and column as input which colors the corresponding cell.
  * [x] Should have an `add_blue` method that accepts a row and column as input which colors the corresponding cell.
  * [x] Should have a `render` method that displays the chess board on screen with red and blue shown in correct locations
  * [x] Should have an `is_under_attack` method that returns boolean if red is under attack by a blue piece horizontally, vertically, or diagonally

### User Acceptance Tests

* [x] Queens on same row should be "under attack"
* [x] Queens on same column should be "under attack"
* [x] Queens on same diagonal should be "under attack"
* [x] Queens with any other coordinates should NOT be "under attack"

**Note**: Include `assert` statements directly in your notebook verifying the behavior above.

### Stretch Goal

* [ ] Enlarge the chessboard to allow for pixel art drawn pieces. 16x16 ought to be enough
* [ ] Add more attacking queens
* [ ] Add opacity to cell colors
