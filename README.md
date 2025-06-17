This code calculates FT (alpha ejection) corrections (assuming an averaging stopping distance based on average abundances of U and Th) for rectangular prism hematite plates with one input z-length an infinite horizontal plane (FTcorr2d_3d.ipynb) or with three input lengths (x, y, z) (ftifalldir.ipynb).
Output FT assumes loss is balanced on one z-direction side and FTneither assumes loss on both sides.
Published in the supplemental material of "Hematite accommodated shallow, transient Pleistocene slow slip in the exhumed southern San Andreas fault system, California, USA", Geology, 2022; https://doi.org/10.1130/G50489.1


TB fixed
under the line that defines nvec --> the number is set to the default of 75, but it should be hg - the FT correction from both sides will not be correct without this update
