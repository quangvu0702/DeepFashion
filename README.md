# DeepFashion
Localize items in images and query visual similarity items from a dataset.

- Paper:
  - [ModaNet: A Large-scale Street Fashion Dataset with Polygon Annotations. a big dataset with bounding boxes. Get image from PaperDoll dataset -> select images with a single person -> select high quality images -> annotation.](https://arxiv.org/pdf/1807.01394.pdf)
  - [Paper Doll Parsing: Retrieving Similar Styles to Parse Clothing Items. Using spatial descriptors for style representation -> KNN to predicts tags -> Parsing images (learn from similar images): global, nn, transferred.](http://tamaraberg.com/papers/paperdoll.pdf)
  - [Where to buy it: Martching Street Clothing Photos in Online Shops: Finding bounding boxes of items in images -> Find the similars of bounding box base on: FC6 of network or learn the similarity using sampling method](http://acberg.com/papers/wheretobuyit2015iccv.pdf)
  - [Pinterest automatic object detection](https://medium.com/@Pinterest_Engineering/introducing-automatic-object-detection-to-visual-search-e57c29191c30)
  - [Pinterest visual len](https://medium.com/cracking-the-data-science-interview/pinterests-visual-lens-how-computer-vision-explores-your-taste-47d591b42d7c)

- Data set:
  - https://github.com/eBay/modanet (annotation)
  - https://github.com/kyamagu/paperdoll/tree/master/data/chictopia (images)
