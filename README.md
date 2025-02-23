# CS3570
Write a program for motion estimation (ME) using the block


Download Link : https://programming.engineering/product/write-a-program-for-motion-estimation-me-using-the-block/

Write a program for motion estimation (ME) using the block matching methods on the given video sequence. You have to implement two search algorithms to find motion vectors, the full search and the 2D logarithmic search method. The search range is ± pixels along horizontal and vertical directions. In this implementation, you should apply the ME to all non-overlapping macroblocks to evaluate the motion vectors, and the block matching measure is defined as sum of absolute differences (SAD), which is described in the slide (p.48).

    (70%) Try the two search ranges (p=8 and p=16) for two macroblock sizes (8×8 and 16×16) by using the two search methods. The reference image is 40.jpg, and the target image is 42.jpg.

        Show the predicted images by using the block matching with all the above combinations. (8 images)

        Show the motion vectors images for all the above combinations. (8 images)

        Show the residual images for all the above combinations. (8 images)

        Compute the total SAD values and PSNR for all the results. Discuss the motion-based image prediction quality for all the above settings.

    (10%) Try the full search method with search range p=8 and macroblock sizes = 8×8. The reference image is 40.jpg, and the target image is 51.jpg. Show the PSNR of the result. Compare and discuss the PSNR with the result of same search range and macroblock in question 1.

    (20%) Analyze the time complexity

        Measure the execution time required for the two search algorithms with the two different search range sizes (p=8 and p=16).

        Compare and discuss the execution time with the theoretical time complexity for the two search algorithms.

Reminder

You need to implement your own functions for computing SAD and PSNR between two images.

Your code should work correctly and the generated results must be consistent to your results in report.

In report, should contain at least all the results (predicted images, motion vectors images, residual images, total SAD values, PSNR values) mentioned in the problem, how you implement the methods, the discussion to the output results, and reference.

Please compress your code, input images, result images, report and in a zip file named HW3_{Student-ID}.zip and upload it to eeclass.

Please follow the file structure below:
