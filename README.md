# Intermediality Hackathon Vienna
Resources for the breakout session at the Intermediality and Computational Humanities Hackathon (November 2024, Vienna).

The current version of the curated image dataset can be downloaded at: (https://1drv.ms/f/c/869f28ab041d44d9/EgdruPCmHK5NvF9WXfaGWqMBtten1fykJaouRm7vim32JA?e=XaViUi)

The notebook for interacting with the CLIP model is available at (https://github.com/ONiT-project/open_clip_finetune/blob/main/image_retrieval.ipynb)

Fine-tuning of openCLIP code shared here: (https://github.com/ONiT-project/open_clip_finetune/blob/main/open-CLIP-finetune.ipynb)

## Some notes

Added value of multimodal retrieval approaches (combining text and image data):
- Combining text and image data improves image retrieval by projecting images into a semantic vector space
- Searching for text and and images representing same content: retrieval with same prompt in both text and image embeddings & show combined output (maybe matched to pages close to each other?)
- Embedding the full page instead of only the image on the page: multimodal LLM can extract more contextual information
- Use retrieval system to support curation and annotation system: pre-sorting, suggesting similar contents
- Sense-making: you need contextual knowledge; how to use the results to make more sense
- If text is paraphrasing, how to find relation between text & image? (emblem books could be an interesting use case to explore)
- --> poster idea: clustering of images; clustering of texts; clustering of multi-modal embeddings
- Retrieval of images should be complemented with additional contextual information to be useful for historical research, i.e. book title, author, page, description of image
- Linking to other resources (knowledge graph) --> how much can be automated in a meaningful way? How much manual curation is required to achieve good quality?
- Reading/understanding of complex systems

Distant reading vs. close reading:
- You need to have a clear idea how you reached the resulting heuristics & how model works (parameters leading to the produced order)
- Finding patterns (distant reading) vs. starting from a specific detail/analysis
- Scalable reading: go from distance to close reading to explore patterns & inspect contextual details
- Having interoperable standard is needed: you have to know what you are looking for; what is noise; does big picture pattern match the individual use case/analysis
- Tacit knowledge vs. evidence-based decisions: Be aware of how human reasoning works to create systems/visualisations that are useful
