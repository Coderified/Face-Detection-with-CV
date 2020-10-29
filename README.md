# Face Detection - Haar Cascade vs MTCNN

This is a comparison between the classic Haar Cascade Face Detection and the Newer and much advanced MTCNN (Multi-task Cascaded Convolutional Neural Networks) by Kaipeng Zhang et.al

MTCNN being more advanced achieved state of the art results.

It uses three models viz. P-Net ,R-Net ,O-Net.

After every step, there comes a process called NMS(non-maximum suppression), which filters out bounding boxes which has no resemblance to facial features.

This reduces the complexity of the already complex process.
