# CSE-4875 — Lab 1: Basic Image Operations (OpenCV + Pillow)

Local VS Code version. No Colab, no Google Drive mount.

## Run it

```bash
pip install -r requirements.txt
python make_samples.py          # creates images/ (only needed once)
```

Open `Lab_1_Image_Operations_VSCode.ipynb` in VS Code, select the Python kernel
(top-right), and run the cells in order.

## What is inside

| Section | Topic |
|---|---|
| 1 | imread flags, the None check, imwrite, JPEG quality |
| 2–3 | shape / dtype / size, pixel access, cropping, slices as views |
| 4 | grey, HSV, LAB, colour selection with `inRange` |
| 5 | split and merge channels |
| 6 | resize and interpolation, flip, rotate, warpAffine, warpPerspective |
| 7 | `cv2.add` vs `+`, `addWeighted`, bitwise masking |
| 8 | drawing shapes and text |
| 9 | global, Otsu and adaptive thresholding |
| 10 | histograms, `equalizeHist`, CLAHE |
| 11 | brightness/contrast, gamma, quantisation and false contouring |
| 12 | average, Gaussian, median, bilateral filters |
| 13 | sharpening, Sobel, Laplacian, Canny |
| 14 | contours: find, count and measure objects |
| 15–16 | Pillow: convert, crop, rotate, ImageEnhance, ImageFilter, ImageDraw; PIL ↔ OpenCV |
| 17 | batch processing a folder |
| 18 | `cv2.imshow` and webcam (local only) |
| 19–20 | common mistakes, four student tasks |

Sections 11 and 13 connect back to Lecture 3: false contouring and the Weber ratio,
and edge enhancement versus lateral inhibition.

## Using your own images

Drop your photos into `images/` and keep the same file names, or edit the file name in
the cell you want to change. Nothing else depends on the sample images.
