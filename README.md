# COMSOL-NitrogenElimination-Model

During deep sea diving, nitrogen dissolves into the bloodstream under high pressure and can form dangerous bubbles during decompression, causing conditions like decompression sickness. This study models the nitrogen transfer from the blood to the alveoli to estimate the nitrogen removal rate, which is crucial for diver safety. Doubling the breathing rate resulted in a 69% increase in nitrogen flow across the total lung alveolar surface, highlighting a potential way to reduce nitrogen-related health risks for divers.

<img src="Images\Nitrogen_diffusion.png" alt="Image" width="200" height="200"/>

A simple model is developed to study the process of diffusion of nitrogen from the blood stream to the alveolus through a thin layer of epithelial cells during deep sea diving. The problem is simplified by assuming that-

<img src="Images\Modeling.png" alt="Image" width="350" height="150"/>

• The entire network of blood vessels can be modeled as a layer of blood stream flowing over a thin layer of epithelial cells in 2D. 

• The network of blood vessels fully covers the alveoli surface. The simplified geometry used for the model is shown. The nitrogen is removed from the blood stream through the 
layer of cells into the air in the alveolus.

#### Observation of surface concentration of Nitrogen-

<img src="Images\Surface concentration.png" alt="Image" width="200" height="200"/>

#### Observation of normal total flux of Nitrogen-

<img src="Images\Normal total flux.png" alt="Image" width="200" height="200"/>

Flux is higher on the inlet side of the alveolus because the blood nitrogen concentration is at a maximum on that boundary. As nitrogen diffuses out, the blood concentration decreases and the drive for nitrogen also decreases, resulting in a steadily declining flux along the length of the alveolus. Hence, the rate of nitrogen removal from the bloodstream decreases as the blood nitrogen concentration decreases. 

The results of this study indicate that recreational divers who cannot decompress at a sufficiently slow rate, should breathe deeply upon surfacing to aid in nitrogen elimination and prevent serious illness from the bends. 
