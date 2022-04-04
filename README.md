# LanePrediction
ENPM673 – Perception for Autonomous Robots – Spring 2022


# Instructions to Run Programs:
# Problem 1: Histogram equalization

Even before running the code, Please goto histogram_adapt_equalization.py line number 99 and change the path to ./Data folder to feed the input images
```
git clone https://github.com/sumedhreddy90/LaneCurvePrediction.git
cd Code
python3 histogram_adapt_equalization.py
```
# Output:
Histogram Frame:
![Histogram_frame](https://user-images.githubusercontent.com/24978535/161637559-f75164ec-3b15-46e2-886f-4c83ea3134a4.jpg)

Adaptive Histogram Frame:
![Adaptive_histogram](https://user-images.githubusercontent.com/24978535/161637610-0f34880c-9dd7-43b0-bc98-83ab32bd543f.png)

Comparision between Histogram and AH
![Adaptive_Histogram_Compare](https://user-images.githubusercontent.com/24978535/161637650-7cb3bf1d-bdbd-43bc-80b4-00648ad68d0a.jpg)


# Problem 2: Straight Lane Detection
```
cd Code
python3 straight_lane.py
```
# Output
Canny Edge Detection:
![2_Canny_Edges](https://user-images.githubusercontent.com/24978535/161637910-52c0cea0-9daf-4538-84e0-f85251e2c89e.jpg)
Warped Edges:
![2_warped](https://user-images.githubusercontent.com/24978535/161637928-94e2195b-92a4-4674-b193-f6b3f8a9e628.jpg)
Final Straight lane detection
![2_straighlane_detected](https://user-images.githubusercontent.com/24978535/161637938-8ee9c4e0-a4eb-4cd1-b288-7e1c977e701d.jpg)

# Problem 3:  Predict Turn 
```
cd Code
python3 lane_predict.py
```
# Output
Undistort Frame
![undistorted](https://user-images.githubusercontent.com/24978535/161638158-5254184d-f18b-42cc-811a-2def2071f07e.jpg)
Bird eye- Warped Frame
![warp](https://user-images.githubusercontent.com/24978535/161638177-027144df-9610-4990-9d91-a7601b94e44b.jpg)
Detected Lanes - colors mask
![lanes](https://user-images.githubusercontent.com/24978535/161638185-ac2f8f5b-b3bc-415a-b787-cd30faf393b1.jpg)
Final Road lane detection
![lanes_detected](https://user-images.githubusercontent.com/24978535/161638199-d8ce0d0a-2c51-4228-a0c2-3d5d21f29799.jpg)
Combined Output
![combined_result](https://user-images.githubusercontent.com/24978535/161638210-3bee4a98-ba3c-4720-9d40-dd8037f6d8f0.jpg)





```
