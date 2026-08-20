# Fiber-Level Vision

A visual case study of my bachelor thesis on high-precision fiber-optic liquid-level signal processing.

The project uses CCD imaging and an explainable OpenCV pipeline to detect fiber end faces, establish stable channel references, recognize brightness changes and recover the extinction order of the sensing array.

## Results

- 103 fiber end faces located in the calibration image
- 100 active channels ordered across the recorded process
- 3 non-participating channels identified
- Processing latency below 100 ms under the final test setup

## Method

1. Grayscale conversion and local-background estimation
2. Difference enhancement and binary segmentation
3. Close-then-open morphology
4. Area and circularity filtering
5. Offline multi-frame channel calibration
6. Per-channel relative-brightness recognition
7. One-dimensional correction for isolated state errors

All figures and reported values on the page come from the final thesis materials and experimental outputs.
