# Benchmark list

This document contains a list of benchmarks used in the experiments in the paper "Flexible Cache Partitioning for Multi-Mode Real-Time Systems" submitted to Design, Automation and Test in Europe Conference (DATE) 2021. The library name, name of each benchmark, and execution options are shown in the table below:

Library | Benchmarks
--- | ---
YOLO<a href="#note1" id="note1ref"><sup>1</sup></a> | dog_detection, dog_classifier, kite, tdf_detection, tdf_classifier
Compression | bzip2 (31 MB), bzip2 (742 MB), gzip (with fast option, 31MB), gzip (with fast option, 742MB), gzip (with best option, 31MB), gzip (with best option, 742MB)
Basic Sorting | bsort
Mälardalen WCET Benchmarks | fdct
VLFeat | kmeans, vec
SoPlex<a href="#note2" id="note2ref"><sup>2</sup></a> | dcmulti, enigma, mcf64, mcf128, meanvarxsc, wheel
GTSAM<a href="#note3" id="note3ref"><sup>3</sup></a> | Simple Rotation, Pose 2 SLAM wSPCG, ISAM2 Smart Factor Stereo IMU, METIS Ordering Example, Pose 3 SLAM Example Expressions Bearing Range with Transform, Planar SLAM Example, Pose 2 SLAM Example, Pose 2 SLAM Example lago, Pose 2 SLAM Stress Test, Visual ISAM 2 Example, SFM Example Smart Factor, Range ISAM Example plaza 2, SFM Example, Inverse Kinematics Example Expressions, Pose 3 SLAM Example g2o, Stereo VO Example, SFM Example Smart Factor PCG, Pose 3 SLAM Example initialize Pose 3 Gradient, Imu Factor Example 2, Stereo VO Example large, Camera Resectioning, SFM Example bal, SFM Example bal COLAMDMETIS, Pose 3 SLAM Example initialize Pose 3 Chordal, Localization Example, SFM Example Expressions, Visual ISAM Example, Imu Factors Example, Solver Comparer, SFM Example Expressions bal, Time TBB, Pose 2 SLAM Example Expressions, Pose 2 SLAM Example g2o, Odometry Example, Pose 3 SLAM Example change Keys, ISAM 2 Example Smart Factor, Pose 2 SLAM Example graph, Create SFM Example Data, Self-Calibration Example, Pose 2 SLAM Example graphviz
OMPL<a href="#note4" id="note4ref"><sup>4</sup></a> | Quotient Space Planning Rigid Body 3D, Geometric Car Planning, Optimal Planning, Hybrid System Planning, Koules, State Sampling, Point 2D Planning, Quotient Space Planning Hyper Cube, Regression Test
OpenCV | example_cpp_letter_recog, example_cpp_stereo_match_bm_d128_b13, example_cpp_stereo_match_hh_d192_b5, example_cpp_stereo_match_sgbm_d144_b3, example_cpp_stereo_match_sgbm3way_d144_b3, example_cpp_stitching


<a id="note1" href="#note1ref"><sup>1</sup></a> You Only Look Once (YOLO) is an object detection system targeted for real-time processing, we used Darknet open source neural network framework. The VLFeat open source library implements popular computer vision algorithms specializing in image understanding and local features extraction and matching.

<a id="note2" href="#note2ref"><sup>2</sup></a> SoPlex is an optimization package for solving linear programming problems based on an advanced implementation of the primal and dual revised simplex algorithm.

<a id="note3" href="#note3ref"><sup>3</sup></a> Georgia Tech Smoothing and Mapping (GTSAM) Library is a C++ library that implements sensor fusion for robotics and computer vision applications, including SLAM (Simultaneous Localization and Mapping) and VO (Visual Odometry).

<a id="note4" href="#note4ref"><sup>4</sup></a> The Open Motion Planning Library (OMPL) consists of many state-of-the-art sampling-based motion planning algorithms.
