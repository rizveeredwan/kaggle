Kaggle link: https://www.kaggle.com/dhruvildave/english-handwritten-characters-dataset

## Architecture
- 1 Conv2d (5 * 5 * 6)
- 1 Max Pool (2 * 2)
- 1 Conv2D (5 * 5 * 16)
- 1 Conv2D (3 * 3 * 20)
- 1  FC (12 * 7 * 20, 120)
- 1 FC (120, 75)

## Resources
- https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html
- https://www.pluralsight.com/guides/importing-image-data-into-numpy-arrays
- https://pytorch.org/docs/stable/generated/torch.nn.Conv2d.html
