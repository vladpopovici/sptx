CONTENTS
========

1. [Export minimal data](export_minimal_data.ipynb)
This notebook implements a simple procedure to export a minimal set of data from a Visium v1 dataset. It also allows the visualization of the spots within the
tissue context, thus helping in ensuring the quality of the data.

2. [Alignement of Visium v1 spots with WSI (version 1)](map_visium_v1_spots-1.ipynb)
When a true whole slide image (WSI) is available, this notebook implements a procedure to align the Visium v1 spots with WSI. It registers the image from Visium dataset onto the corresponding part in WSI and generates a
pyramidal image of the tissue part, with spots as annotations.

3. [Alignement of Visium v1 spots with WSI (version 2)](map_visium_v1_spots-2.ipynb)
In some cases, the previous version fails. Then try this one, which implements a different registration procedure.