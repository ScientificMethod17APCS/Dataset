Dump1: All the photos in one folder
Dump2: From Dump1, face is cropped using Viola Jones then eyes are cropped using fixed ratio
Dump3: From Dump2, turned into grayscale
Dump4: From Dump3, binary threshold is applied
Dump5: From Dump4, mean adaptive threshold is applied
Dump6: From Dump5, eroded then dilated, twice
Dump7: From Dump3, Gaussian adaptive threshold is applied