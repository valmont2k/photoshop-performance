Puget Systems Photoshop CC 2019 Benchmark (BETA ver 18.10)
www.pugetsystems.com


-----How to run the benchmark-----

Before running the benchmark, we highly recommend resetting Photoshop to it's default settings as changes in color space, bit depth, etc. can drastically alter the final results. Information on how to reset the preferences (and how to back up your current settings) can be found in the Photoshop User Guide - Workspace - Preferences.

Depending on your operating system, run either the Windows___.exe or MacOS___.app files to launch the benchmark. If you have Photoshop installed in a non-default location or otherwise have issues with the benchmark, launch Photoshop manually then go to "File -> Scripts -> Browse". Navigate to the location of the benchmark folder and select either the "PugetBenchmark_Basic.jsxbin" or "PugetBenchmark_Extended.jsxbin" script.


-----Compatibility-----

This benchmark is designed for Photoshop 2019 and should run on virtually any OpenCL-enabled Windows or Mac-based system that has Photoshop CC 2019 installed. However, due to the size of the test projects it is ideal to have more than 24GB of system RAM. The benchmark should be able to complete with smaller amounts of RAM, but the Extended test in particular is likely to receive a lower than normal score.

Note that this benchmark currently requires the language used in Photoshop to be English.

This benchmark is still in BETA Plug-ins and customized preferences in particular may prevent the benchmark from running properly.


-----Benchmark modes and tested tasks-----

Our benchmark is available in two modes: Basic and Extended. For the Basic mode, Photoshop is run in 8 Bits/channel mode for the General and Filter tasks. For the Extended mode, the General and Filter tasks are repeated only with Photoshop in 16 Bits/Channel mode


Each individual task is run a total of three times with the fastest result being used to tally the final score. A full run should take approximately 20-45 minutes but will vary based on the performance of your system. When the benchmark is complete, it will give you an "Overall Score" as well as individual scores for the different types of tests. A log file is generated in the benchmark folder that includes these scores as well as the time in seconds it took to complete each individual task.


It would be nearly impossible to test everything in Photoshop, but our benchmark is designed to test a broad range of tasks in order to give an accurate overall picture of how a system performs in Photoshop. We test how long it takes to complete general tasks, apply filters, and generate a panorama (photomerge). The tested actions are:

General
	Open 18MP .CR2 RAW Image
	Resize to 500MB
	Rotate
	Magic Wand Select
	Mask Refinement
	Paint Bucket
	Gradient
	Content Aware Fill
	Save .PSD File
	Open .PSD File
Filter
	Camera Raw Filter
	Lens Correction
	Reduce Noise
	Smart Sharpen
	Field Blur
	Tilt-Shift Blur
	Iris Blur
	Adaptive Wide Angle
	Liquify
Photomerge
	Photomerge 6x 22MP .CR2 RAW Images
	Photomerge 6x 45MP .NEF RAW Images


-----How does the scoring work?-----

The scoring system used in our benchmark is based on the performance relative to a reference system with the following specifications:

Intel Core i9 9900K 8 Core
NVIDIA GeForce RTX 2080 8GB
64GB of RAM
Samsung 960 Pro 1TB
Windows 10
Adobe Photoshop CC 2019 (ver. 20.0.0)

The scores are based on the performance of this reference system with the Overall score being "1000" while the scores for the General, Filter, and Photomerge tests being "100"

The time to complete each individual task is compared to the reference result with the average for each type of test (general, filter, and photomerge) being used as the score for that test. The Overall Score is based on a weighted average of the four tests:

General - 40% (50/50 split between 8-bit and 16-bit if run in Extended mode)
Filter - 40% (50/50 split between 8-bit and 16-bit if run in Extended mode)
Photomerge - 20%

There is also a dedicated GPU Score that is the average of the results for the Rotate, Smart Sharpen, Field Blur, Tilt-Shift Blur, and Iris Blur which are the five tasks that make the most use of the video card.


-----Commercial use & pricing-----

Our Photoshop benchmark is provided completely free of charge for anyone to download and use. We only ask that you do not directly re-distribute the benchmark and if using it for public benchmarking that you credit Puget Systems for the benchmark process. If in doubt, just toss in a link to this page!