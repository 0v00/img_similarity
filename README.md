Simple example of image similarity search using embeddings with PyTorch and ResNet 50.

Print out filepaths of images and their original index in `image_paths` ranked by similarity (most similar to less similar):

```bash
Most similar images: [('./images/image_5.jpg', 4), ('./images/image_2.jpg', 1), ('./images/image_3.jpg', 2), ('./images/image_1.jpg', 0), ('./images/image_4.jpg', 3)]
```

## how to run
1. create a venv
2. `pip install -r requirements.txt`
3. `python main.py`