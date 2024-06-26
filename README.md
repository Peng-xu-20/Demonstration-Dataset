# Intelligent-breeding-demonstration-data-set
A small demonstration dataset so that other researchers and developers can reproduce and understand our methods.
## Algorithm fusion model
The mathematical steps of the above-mentioned method are expressed in pseudo code as follows. Detect represents the target detection step using the improved YOLOv7 model.Track takes the detections and performs multi-object tracking.GetFrameImage,TransformBinaryImage, HitMissTransform, and PixelStatistics are steps in the Trajectory Processing Algorithm to determine the cross aggregation level of trajectories.ExtractCoordinates, CoordinateGrouping, CalculateGroupSpeed, and CalculateAverageSpeed are steps in the Speed Processing Algorithm to analyze the swimming speed of the fish school.DecisionMechanism integrates the cross aggregation level and average speed to determine the hunger level of the fish school.

![Improved YOLOv7 and Associated Algorithms Pseudocode](https://github.com/ALAN-SOFT/Intelligent-breeding-demonstration-data-set/assets/44634241/e2921956-c99c-4b2e-a7aa-6885c58b95f8)

![Fig.3 Graphical explanation of the proposed method](https://github.com/ALAN-SOFT/Intelligent-breeding-demonstration-data-set/assets/44634241/4c9d53c7-3ea1-4e3e-b82e-5e2ca098abb1)

The graphical explanation of this method is shown in Fig. 3. The collected original video data is used as the total input of the decision mechanism. Through the improved YOLOv7 model and SORT algorithm, the trajectory video and coordinate data can be obtained respectively. The trajectory video is used as the input of the trajectory processing algorithm, and the cross aggregation level can be obtained after calculation. The coordinate data is used as the input of the speed processing algorithm, and the overall swimming speed of the fish school can be obtained after calculation. The hunger level of fish school is classified according to the cross aggregation level, and the overall swimming speed of fish school is used as an auxiliary judgment condition to finally obtain the hunger level of fish school. On the basis of Decision Mechanism, the design of aquaculture consumer electronics products driven by image understanding can be realized.

![data-set](https://github.com/ALAN-SOFT/Intelligent-breeding-demonstration-data-set/assets/44634241/d9863ebb-843f-4389-8933-0caf8206d0c4)

![data-set](https://github.com/ALAN-SOFT/Intelligent-breeding-demonstration-data-set/assets/44634241/f3fe8e6e-6ed3-4123-bdf3-ec6c3f2079c6)
