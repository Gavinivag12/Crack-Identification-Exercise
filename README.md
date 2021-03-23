# Crack-Identification-Exercise

This is a experiment to categorize cracking on RC beams and structural walls
using basic ML CNN with keras. Inspired by ImageNet examples.
Part of my training in HKUST DESR, given to me in 2020 Spring albeit have little work onto it.
Consider a POF only

V1: operational with limited accuracy ~80%, could be further improved by finding better fit parameters

Pretraining and V2: problems with pretraining weights, excptionally resource-hungry. Can only be run on institutional-server

Dataset could be provided on request at: wywuac@connect.ust.hk
Dataset:
	/train/
		../0/: 2000 IMAGES
	 	../1/: 2000 IMAGES
		../2/: 2000 IMAGES
		../3/: 2000 IMAGES
	/validation/
		../0/: 500 IMAGES
	 	../1/: 500 IMAGES
		../2/: 500 IMAGES
		../3/: 500 IMAGES
		
***CONCLUSION***
-An intrinsic deficient of the VGG16 network, two classes are recognized doubly as the features are similar
-Pretrain model in this case, albeit more complicated, performs less effectively as the simple pipline model

