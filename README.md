# IHBPFlow

IHBPFlow: Inertial Constrained Hierarchical Belief Propagation for Optical Flow

This is an implementation of IHBPFlow for optical flow estimation. It is implemented on Windows 7 with Visual Studio 2013.

An executable demo is provided in 'exe' folder.
	Since we use EpicFlow as postprocessing setp, you need to get edge maps first before running IHBPFlow.
	We use SED to detect edges in our paper. The code can be downloaded here: 
		http://research.microsoft.com/en-us/downloads/389109f6-b4e8-404c-84bf-239f7cbf4e3d/
	Demo can be excuted as follows:
		IHBPFlow <imgs_dir> <edges_dir> <result_dir>
	We provide a part of MPI-Sintel sequences and corresponding edge maps, you can run demo by 
	typing 'IHBPFlow images edges results'. Results will be saved in 'results' folder.
	
	Code is coming soon.