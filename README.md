# BlenderQuipu
Repo for blender training data 


# Cleaning
I'm experimenting with using [unstructured](https://unstructured-io.github.io/unstructured/) for the readthedocs cleaning. 
I'm installing via
`pip3 install unstructured`
And then maybe I might do `pip3 install "unstructured[rtf,epub]"` if I want to not use the html for some reason?





### Scrap

```
https://scribe.rip/@jerryjliu98/how-unstructured-and-llamaindex-can-help-bring-the-power-of-llms-to-your-own-data-3657d063e30d
https://colab.research.google.com/drive/1W9jCOGbIrE43f7fHMUSn3g3xXhOIjx_v#scrollTo=l3NkMnQtHZkY
https://unstructured-io.github.io/unstructured/core/partition.html#partition-html
https://unstructured-io.github.io/unstructured/metadata.html
https://unstructured-io.github.io/unstructured/introduction/overview.html
https://github.com/Unstructured-IO/unstructured/blob/a583d47b841bdd426b9058b7c34f6aa3ed8de152/unstructured/partition/html.py
https://github.com/Unstructured-IO/unstructured/blob/6af660405794f8bcd7e305bf6c25e578739b418d/unstructured/documents/html.py#L128
https://github.com/Unstructured-IO/unstructured/blob/a583d47b841bdd426b9058b7c34f6aa3ed8de152/unstructured/documents/elements.py#L260
```


```
cd my-broken.epub
 # iTunes/Books seems to add a file 'iTunesMetadata.plist', and it produces a warning.
 # May also contain private data, so better delete it.
 rm iTunesMetadata.plist 
 zip -X -r ../fixed.epub mimetype *
```

