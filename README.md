# hackathon

## Team
Bridget Vincent @BridgetSquidget, Arielle Rothman, Saurin Rajesh Savla

## Notes and Brainstorming
- General interests
  - complex trait morphology and evolution
      - eyes
      - photophores/light organs 
- possible hackathon objectives
    - automated segmentation and feature recognition (i.e. taking a TEM image and getting back a map of what we see like mitochondria, cell membranes, golgi)
      - this is something I've wanted for my own work - not sure how feasible it is
      - example of someone else's paper with a similar goal: https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1013115
    - comparing images from multiple runs to give you an idea of major differences
      - kind of builds off the automated segmentation idea  
- data types and repositories
    - general repository links
        - https://idr.openmicroscopy.org/
        - https://beta.bioimagearchive.org/bioimage-archive/
    - CEM500K, a large-scale heterogeneous unlabeled cellular electron microscopy image dataset for deep learning: https://elifesciences.org/articles/65894
    - jellyfish FLIM - waiting to hear back if this is possible with the digital twin system but it's a dataset I have lying around
        - Bridget's google drive 
    - eye/visual system TEM - shamelessly adding it here bc whatever we make might be helpful for one of my chapters
        - not all microscopy BUT is a retina repository from one of the hackathon sponsors Hugging Face: https://huggingface.co/datasets/open-retina/open-retina
            - since they already have a companion package, it might give us something nice to work from or to enhance a microscopy-focused package
        - Volume electron microscopy of APEX2-DAB labeled thalamocortical projections in visual cortex L4: https://beta.bioimagearchive.org/bioimage-archive/study/EMPIAR-12513
    - reproductive system TEM (ovaries, testes, uteri, eggs, sperm) - I don't work with these but I kind of wish I did
    - photophore TEM images - also just specifically useful/interesting to me. Problem is that a lot of the data is pre-1990s so at best we'd have a screenshot of a TEM image.
         - cons: screenshot of a TEM image is not ideal
         - pro: a screenshot of a TEM image is what a lot of biologists have to work with (or have to combine that data with their new data)
    - cancer cells - there's gotta be tons of data out there. Also, cancer cells do interesting things
        - https://openorganelle.janelia.org/datasets/jrc_sum159-4    
