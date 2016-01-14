# AnomalyAnalysisWithOpticalFlow
This project is designed for anomaly detection of video sequence.
We improve the efficiency of optical flow computation with foreground
mask and spacial sampling and increase the robustness of optical flow
with good feature (TK) points selecting and forward-backward filtering.
A foreground channel is also added to the feature vector to help detect
static or low
speed objects. The algorithm is validated on real-life traffic
surveillance to prove its effectiveness. It is also evaluated on a
benchmark dataset and achieve detection results comparable to
state-of-art methods and outperforms them at pixel-level when the false
alarm rate is low. The strength of our algorithm is that it runs
real-time on the benchmark dataset which is hundreds of times faster
than comparative methods.

Vist the following link to see our published ICASSP 2016 conference
paper for this project.

https://www.researchgate.net/publication/290428052_Fast_Anomaly_Detection_in_Traffic_Surveillance_Video_based_on_Robust_Sparse_Optical_Flow
