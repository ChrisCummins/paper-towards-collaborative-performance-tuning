# Towards Collaborative Performance Tuning of Algorithmic Skeletons
[Chris Cummins](http://chriscummins.cc/),
[Pavlos Petoumenos](http://homepages.inf.ed.ac.uk/ppetoume/),
[Michel Steuwer](http://homepages.inf.ed.ac.uk/msteuwer/),
[Hugh Leather](http://homepages.inf.ed.ac.uk/hleather/).

**Abstract**
> The physical limitations of microprocessor design have forced the industry
> towards increasingly heterogeneous designs to extract performance. This trend
> has not been matched with adequate software tools, leading to a growing
> disparity between the availability of parallelism and the ability for
> application developers to exploit it.
>
> Algorithmic skeletons simplify parallel programming by providing high-level,
> reusable patterns of computation. Achieving performant skeleton
> implementations is a difficult task; skeleton authors must attempt to
> anticipate and tune for a wide range of architectures and use cases. This
> results in implementations that target the general case and cannot provide the
> performance advantages that are gained from tuning low level optimization
> parameters. Autotuning combined with machine learning offers promising
> performance benefits in these situations, but the high cost of training and
> lack of available tools limits the practicality of autotuning for real world
> programming. We believe that performing autotuning at the level of the
> skeleton library can overcome these issues.
>
> In this work, we present OmniTune - an extensible and distributed framework
> for dynamic autotuning of optimization parameters at runtime. OmniTune uses a
> client-server model with a flexible API to support machine learning enabled
> autotuning. Training data is shared across a network of cooperating systems,
> using a collective approach to performance tuning.
>
> We demonstrate the practicality of OmniTune in a case study using the
> algorithmic skeleton library SkelCL. By automatically tuning the workgroup
> size of OpenCL Stencil skeleton kernels, we show that that static tuning
> across a range of GPUs and programs can achieve only 26% of the optimal
> performance, while OmniTune achieves 92% of this maximum, equating to an
> average 5.65x speedup. OmniTune achieves this without introducing a
> significant runtime overhead, and enables portable, cross-device and cross-
> program tuning.

**Presented** High-Level Programming for Heterogeneous and Hierarchical Parallel Systems.
Prague, Czech Republic, Tuesday, Jan 19th 2016. Co-Located with HiPEAC 2016.

```
@inproceedings{cummins2016a,
    author    = "Cummins, Chris and Petoumenos, Pavlos and Steuwer, Michel and Leather, Hugh",
    title     = "Towards Collaborative Performance Tuning of Algorithmic Skeletons",
    booktitle = "High-Level Programming for Heterogeneous and Hierarchical Parallel Systems (HLPGPU)",
    year      = "2016",
}
```
