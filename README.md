# Camera_Chessboard
직접 촬영한 체스보드 영상을 카메라 캘리브레이션을 통해 수치를 얻어낸다.
얻어낸 수치를 통해 pose estimation의 수치를 바꾼다.
원하는 모양의 좌표를 입력하여 만든다.(작성자의 경우 L모양을 만들었다.)


## Camera Calibration Results
* The number of selected images = 5
* RMS error = 1.0248617140650016
* Camera matrix (K) = 
[[1.10023029e+03 0.00000000e+00 3.38025357e+02]
 [0.00000000e+00 1.09955769e+03 6.31476930e+02]
 [0.00000000e+00 0.00000000e+00 1.00000000e+00]]
* Distortion coefficient (k1, k2, p1, p2, k3, ...) = [ 8.81899477e-02 -8.06280792e-01  1.15883981e-03 -8.94166415e-04
  2.43730957e+00]
  
  
  카메라 캘리브레이션 스크린샷 
<img width="472" alt="스크린샷 2023-04-25 오후 3 29 52" src="https://user-images.githubusercontent.com/61642764/234193210-85431c74-4ed3-417a-8eb3-b90b92a655f1.png">



## Pose Estimation Results


교수님의 예제 사용시 출력


<img width="1072" alt="스크린샷 2023-04-25 오후 4 42 25" src="https://user-images.githubusercontent.com/61642764/234208979-17a852b5-1d09-40ac-a232-1fd07eb0c22b.png">



직접 촬영한 영상 사용시 출력


<img width="428" alt="스크린샷 2023-04-25 오후 4 44 04" src="https://user-images.githubusercontent.com/61642764/234208947-627c9a18-91f4-4ce6-ba50-3f8d92923603.png">

K값과 distortion coefficient 값을 위의 Calibration 값으로 수정하여 직접 촬영한 영상 사용시 출력


<img width="472" alt="스크린샷 2023-04-25 오후 4 51 32" src="https://user-images.githubusercontent.com/61642764/234211146-3aaeb9eb-7661-4e8f-89e4-01a66d30881c.png">

