# Digital Image Processing

## Assignment 0: Basic Image Transformations

<table>
    <tr>
        <td align="center"><img src="a0/media/monkey.png" width="200"></td>
        <td align="center"><img src="a0/output/monkey_added_brightness.jpg" width="200"></td>
        <td align="center"><img src="a0/output/monkey_multiplied_brightness.jpg" width="200"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Increased Brightness</td>
        <td align="center">Scaled Brightness</td>
    </tr>
    <tr>
        <td align="center"><img src="a0/media/fog.jpg" width="200"></td>
        <td align="center"><img src="a0/output/fog_contrast.jpg" width="200"></td>
        <td align="center"><img src="a0/output/fog_contrast_1.jpg" width="200"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Stretched Contrast (Min-Max)</td>
        <td align="center">Stretched Contrast (Outlier Removal)</td>
    </tr>
    <tr>
        <td align="center"><img src="a0/media/rose.jpg" width="200"></td>
        <td align="center"><img src="a0/output/rose_grayscale_33.jpg" width="200"></td>
        <td align="center"><img src="a0/output/rose_grayscale_70.jpg" width="200"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Grayscale (Equal Weights)</td>
        <td align="center">Grayscale (Green Biased)</td>
    </tr>
    <tr>
        <td align="center"><img src="a0/media/feather.jpg" width="200"></td>
        <td align="center"><img src="a0/output/feather_grayscale.jpg" width="200"></td>
        <td align="center"><img src="a0/output/feather_brightness_adjusted.jpg" width="200"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Grayscale</td>
        <td align="center">Pseudo Colored</td>
    </tr>
    <tr>
        <td align="center"><img src="a0/media/tajmahal.jpg" width="200"></td>
        <td align="center"><img src="a0/media/greenbox-director.jpg" width="200"></td>
        <td align="center"><img src="a0/output/chroma_keying.jpg" width="200"></td>
    </tr>
    <tr>
        <td align="center">Background</td>
        <td align="center">Foreground</td>
        <td align="center">Chroma Keying Output</td>
    </tr>
</table>

## Assignment 1: Bit Plane Operations, Histogram Equalization, Piecewise Linear Transformations

<table>
    <tr>
        <td align="center"><img src="a1/out_img/lenna_4.png" width="200"></td>
        <td align="center"><img src="a1/out_img/lenna_2.png" width="200"></td>
        <td align="center"><img src="a1/out_img/lenna_1.png" width="200"></td>
    </tr>
    <tr>
        <td align="center">4-bit Quantization</td>
        <td align="center">2-bit Quantization</td>
        <td align="center">1-bit Quantization</td>
    </tr>
    <tr>
        <td align="center"><img src="a1/out_img/bit_8.png" width="200"></td>
        <td align="center"><img src="a1/out_img/bit_6.png" width="200"></td>
        <td align="center"><img src="a1/out_img/bit_4.png" width="200"></td>
    </tr>
    <tr>
        <td align="center">Bit Plane 8</td>
        <td align="center">Bit Plane 6</td>
        <td align="center">Bit Plane 4</td>
    </tr>
    <tr>
        <td align="center"><img src="a1/src_img/painting.jpg" width="200"></td>
        <td align="center"><img src="a1/out_img/painting_equalized.png" width="200"></td>
        <td align="center"><img src="a1/out_img/painting_channel_equalized.png" width="200"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Histogram Equalized</td>
        <td align="center">Per-Channel Histogram Equalized</td>
    </tr>
    <tr>
        <td align="center"><img src="a1/src_img/image.jpg" width="200"></td>
        <td align="center"><img src="a1/out_img/image_transformed.png" width="200"></td>
        <td align="center"><img src="a1/out_img/image_mod_transformed.png" width="200"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Per-Channel Transform 1</td>
        <td align="center">Per-Channel Transform 2</td>
    </tr>
</table>

## Assignment 2: Convolutional Filters, Edge Detection, Morphological Operations

<table>
    <tr>
        <td align="center"><img src="a2/images/IMG2.jpg" width="200"></td>
        <td align="center"><img src="a2/output/IMG2_gaussian.png" width="200"></td>
        <td align="center"><img src="a2/output/IMG2_bilateral.png" width="200"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Gaussian Filter</td>
        <td align="center">Bilateral Filter</td>
    </tr>
    <tr>
        <td align="center"><img src="a2/images/IMG3.jpeg" width="200"></td>
        <td align="center"><img src="a2/output/IMG3_sobel.png" width="200"></td>
        <td align="center"><img src="a2/output/IMG3_prewitt.png" width="200"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Sobel Filter</td>
        <td align="center">Prewitt Filter</td>
    </tr>
    <tr>
        <td align="center"><img src="a2/output/IMG3_roberts.png" width="200"></td>
        <td align="center"><img src="a2/output/IMG3_laplacian.png" width="200"></td>
        <td align="center"></td>
    </tr>
    <tr>
        <td align="center">Roberts Cross Operator</td>
        <td align="center">Laplacian Operator</td>
        <td align="center"></td>
    </tr>
    <tr>
        <td align="center"><img src="a2/images/IMG4.png" width="200"></td>
        <td align="center"><img src="a2/output/IMG4_unsharp.png" width="200"></td>
        <td align="center"><img src="a2/output/IMG4_highboost.png" width="200"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Unsharp Masking</td>
        <td align="center">Highboost Filter</td>
    </tr>
    <tr>
        <td align="center"><img src="a2/images/IMG8.png" width="200"></td>
        <td align="center"><img src="a2/output/IMG8_power_law.png" width="200"></td>
        <td align="center"><img src="a2/output/IMG8_enhanced.png" width="200"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Power Law Transformation</td>
        <td align="center">Stretched Contrast</td>
    </tr>
    <tr>
        <td align="center"><img src="a2/images/original_13_1.png" width="200"></td>
        <td align="center"><img src="a2/output/original_13_1_skeleton.png" width="200"></td>
        <td align="center"></td>
    </tr>
    <tr>
        <td align="center">Original Signature</td>
        <td align="center">Skeleton</td>
        <td align="center"></td>
    </tr>
    <tr>
        <td align="center"><img src="a2/images/forgeries_13_1.png" width="200"></td>
        <td align="center"><img src="a2/output/forgeries_13_1_skeleton.png" width="200"></td>
        <td align="center"><img src="" width="200"></td>
    </tr>
    <tr>
        <td align="center">Forged Signature</td>
        <td align="center">Skeleton</td>
        <td align="center"></td>
    </tr>
</table>

## Assignment 3: Frequency Domain Processing

<table>
    <tr>
        <td align="center"><img src="a3/src/plots/cart_artifact_removal.png" width="600"></td>
    </tr>
    <tr>
        <td align="center">Lowpass Filter</td>
    </tr>
    <tr>
        <td align="center"><img src="a3/src/plots/fingerprint_enhancement.png" width="600"></td>
    </tr>
    <tr>
        <td align="center">Highpass Filter</td>
    </tr>
    <tr>
        <td align="center"><img src="a3/src/plots/fingerprint2_enhancement.png" width="600"></td>
    </tr>
    <tr>
        <td align="center">Gabor Filter</td>
    </tr>
</table>

## Assignment 4: Thresholding, Hough Transform, Harris Corner Detector

<table>
    <tr>
        <td align="center"><img src="a4/images/sudoku.jpg" width="275"></td>
        <td align="center"><img src="a4/src/output/sudoko_binary.png" width="275"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Binary Thresholding</td>
    </tr>
    <tr>
        <td align="center"><img src="a4/src/output/sudoko_adaptive.png" width="275"></td>
        <td align="center"><img src="a4/src/output/sudoko_otsu.png" width="275"></td>
    </tr>
    <tr>
        <td align="center">Adaptive Thresholding</td>
        <td align="center">Otsu's Thresholding</td>
    </tr>
    <tr>
        <td align="center"><img src="a4/images/sudoku.jpg" width="275"></td>
        <td align="center"><img src="a4/src/output/sudoku.png" width="275"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Hough Line Transform</td>
    </tr>
    <tr>
        <td align="center"><img src="a4/images/caps.png" width="275"></td>
        <td align="center"><img src="a4/src/output/caps.png" width="275"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Hough Circle Transform</td>
    </tr>
    <tr>
        <td align="center"><img src="a4/images/chessboard.jpg" width="275"></td>
        <td align="center"><img src="a4/src/output/chessboard.png" width="275"></td>
    </tr>
    <tr>
        <td align="center">Original Image</td>
        <td align="center">Harris Corner Detector</td>
    </tr>
</table>
