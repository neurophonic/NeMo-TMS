# NeMo-TMS Toolbox
Neuron Modeling for TMS (NeMo-TMS) toolbox is for multi-scale modeling of the effects of Transcranial Magnetic Stimulation on single-neuron activity. The instructions and open-source codes provided here enable users with different levels of expertise to investigate the neuronal behavior under TMS.

Refer to the following article for more details:
Shirinpour, et al. "Multi-scale modeling toolbox for single neuron and subcellular activity under Transcranial Magnetic Stimulation." Brain Stimulation (2021). https://doi.org/10.1016/j.brs.2021.09.004

## Overview
This paradigm incorporates modeling at three scales:

- TMS-induced electric field calculation at the macroscopic scale 
- Simulation of neuronal activity under the external electric field from the previous step
- Simulation of subcellular calcium concentrations based on the membrane voltages calculated in the previous step.

The procedures for running simulations at each scale and the intermediate steps are given in the instructions. This pipeline has been tested on **Windows 10**, and **Linux** (Ubuntu 16.04/18.04). We have tested all the steps on **macOS Catalina**, except for the model generation (step 1) which currently is not functional on macOS (note that generated models can be transferred between computers and operating systems). However, the codes are developed to run on the native operating system's configurations and possibly not work if there are any modifications (for example, using other forms of shell).

## Instructions
Refer to **Full_Tutorial.pdf** for a comprehensive tutorial on how to use NeMo-TMS.

For a quick guide on how to use NeMo-TMS, refer to **Quick_Guide.pdf**.

## Older versions
You can access the older versions of the toolbox from the [Releases](https://github.com/OpitzLab/NeMo-TMS/releases) section.

## Reference
Please cite the following reference:

Shirinpour, et al. "Multi-scale modeling toolbox for single neuron and subcellular activity under Transcranial Magnetic Stimulation." Brain Stimulation (2021). https://doi.org/10.1016/j.brs.2021.09.004

## Correspondence
aopitz[at]umn.edu (Prof. Alexander Opitz)

