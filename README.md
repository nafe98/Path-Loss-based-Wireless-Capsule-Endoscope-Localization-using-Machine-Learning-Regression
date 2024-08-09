# Path-Loss-based-Wireless-Capsule-Endoscope-Localization-using-Machine-Learning-Regression

ABSTRACT Localization of wireless capsule endoscope (WCE) while it travels through the Gastrointestinal
(GI) tract is required to find the exact location of the intestinal lesions. In this paper, we propose a method of
localizing the WCE in the small intestine by applying machine learning-based regression algorithms on the
ultra-wideband (UWB) and medical implant communication service (MICS) band signal. The path loss of
the signals received by sensor receivers placed on the body surface is used as the input features to find the 3D
x-y-z position of the WCE. To improve the accuracy of localization, we estimate the smoothed path loss by
applying local linear regression moving average (LLRMA) and local weighted linear regression (LWLR) on
the scattered path loss to minimize the path loss deviations caused by the dielectric properties of human body
tissues. Then, we apply five machine learning regression algorithms namely Decision Tree (DT), Random
Forest (RF), Extreme Gradient Boosting (XGB), Linear Regression (LR), and K-Nearest Neighbors (KNN)
on both the scattered and smoothed path loss to localize 2443 mapped positions of the WCE in the small
intestine trajectory model. We also analyze the impact of the number of sensor receivers and the network
topology of the sensor array on the accuracy of localization. It is observed that the localization accuracy
is significantly improved by applying all the regression algorithms on the smoothed path loss data. For the
smoothed dataset, the best accuracy with 0.21 mm and 0.22 mm root mean square error (RMSE) is achieved
by applying the KNN regression method on UWB and MICS path loss model, respectively using 48 sensor
receivers. Additionally, it is also observed that with the UWB and MICS path loss, KNN shows 0.22 mm
and 0.27 mm RMSE on the smoothed path loss using only 8 sensor receivers with a computational time of
0.004 sec and 0.005 sec, respectively.
