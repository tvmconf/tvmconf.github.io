---
title: "TVM Conference, Dec 2nd-4th 2020"
layout: index
order : 12
description: "TVM"
---
{% include JB/setup %}

<br>

# About

[Apache TVM(incubating)](https://tvm.apache.org/) is an open-source deep learning compiler stack for CPUs, GPUs, and specialized accelerators.
It aims to close the gap between the productivity-focused deep learning frameworks, and the performance- or
efficiency-oriented hardware backends.

We are excited to announce the 2020 TVM Virtual Conference, December 2-4. The TVM Conference will cover the state of the
art of deep learning compilation optimization. We welcome TVM contributors, potential users, [UW SAMPL](http://sampl.ai)
sponsors, collaborators and researchers and practitioners from the broader community. The conference will discuss recent
advances in frameworks, compilers, systems and architecture support, security, training and hardware acceleration.

## Resources

- [Code of conduct](https://www.apache.org/foundation/policies/conduct.html).

## 2020 Program

|          | **Dec 2 - Tutorials**   |          |          |
|----------|----------|----------|----------|
| Time     | Title    | Speakers | Company  |
| TBD       | Introduction to TVM       | Chris Hoge       | OctoML       |
| TBD       | TVMC: a command-line driver for TVM       | Leandro Nunes       | Arm       |
| TBD       | Bring Your Own Codegen to TVM       | Zhi Chen       | Amazon Web Services       |
| TBD       | uTVM: Running the TVM Stack on Bare Metal       | Andrew Reusch       | OctoML       |
|          |          |          |          |
|          | **Dec 3 - Conference**   |          |          |
|----------|----------|----------|----------|
| Time     | Title    | Speakers | Company  |
| 9:00       | Keynote and Community Update       | Luis Ceze       | OctoML       |
| 10:00       | Break       |        |        |
| 10:15       | TVM at AWS  | Yida Wang,Yao Wang,Wei Xiao       | Amazon Web Services     |
| 10:45       | TVM at Imagination     | Ashutosh Parkhi       | Imagination Technologies       |
| 10:51       | TVM at Synopsys & ITRI       | Kerwin Tung       | ITRI (Industrial Technology Research Institute)       |
| 10:57       | A Generic Method to Utilize Vendor-specific AI Accelerator on Android Mobile for TVM       | Ming-Yu Hung       | MediaTek Inc.       |
| 11:03       | Extending TVM to Support Custom ML Hardware -- the Awesome Front End       | Joey Chou       | SiMa.ai       |
| 11:10       | Break       |        |        |
| 11:20       | TBD       | Joey Gonzalez       | UC Berkeley       |
| 11:50       | Lorien: A Scale-Out System and Database for Auto-Tuning Tensor Programs       | Cody Yu       | Amazon Web Services      |
| 12:10       | Lunch Break       |        |        |
| 12:50       | TVM at ARM       | Ramana Radhakrishnan       | Arm       |
| 13:20       | TVM at OctoML       | Jason Knight       | OctoML       |
| 13:40       | Break       |        |        |
| 14:00       | Lightning Talks        | Various       | Various       |
|          |          |          |          |
|          | **Dec 4 - Conference**   |          |          |
|----------|----------|----------|----------|
| Time     | Title    | Speakers | Company  |
| 9:30       | MLIR Talk from Google       | Jacques Pienaar       | Google       |
| 10:00       | Break       |        |        |
| 10:15       | Bringing Vitis-AI hardware acceleration to TVM for cloud and edge       | Jorn Tuyls       | Xilinx       |
| 10:35       | TVM @ Alibaba       | xiaoyong liu       | Alibaba       |
| 10:55       | End-to-End Performance Assessment of AI Systems with TVM and Virtual Models       | Michael J. Klaiber       | Bosch Corporate Research       |
| 11:15       | Break       |        |        |
| 11:50       | TVM for Edge Inference at AMD       | Mei Ye       | AMD       |
| 12:10       | Lunch Break       |        |        |
| 12:50       | Ansor : Generating High-Performance Tensor Programs for Deep Learning (An auto-scheduler for TVM)       | Lianmin Zheng       | UC Berkeley       |
| 13:10       | TVM Object System: Multi-language Support for just $19.99       | Jared Roesch       | OctoML       |
| 13:20       | Break       |        |        |
| 13:40       | Lightning Talks        | Various       | Various       |
|          |          |          |          |
|          | **Dec 3 - Lightning Talks**   |          |          |
|----------|----------|----------|----------|
| Time     | Title    | Speakers | Company  |
| 14:00       | Graph-Level Scheduling Optimization with Polyhedral Analysis for Tensor Programs       | Jie Wang       | Amazon Web Services (Amazon AI)       |
| 14:06       | FeatGraph: A Flexible and Efficient Backend for Graph Neural Network Systems       | Yuwei Hu       | Cornell University       |
| 14:18       | RAFT:Accelerating the Tuning Process for  AutoTVM       | HaiWen Fu       | Beihang University       |
| 14:24       | A TVM IR to MLIR Automatic Converter  :  Bridging TVM with MLIR Ecosystem       | Jinman Zhao       | Huawei Technologies Canada/ University of Toronto       |
| 14:30       | BERT inference optimization using TVM       | Haichen Shen       | Amazon Web Services       |
| 14:36       | Writing Sparse Operators in TIR       | Tristan Konolige       | OctoML       |
| 14:48       | Optimizing Automatic Tuning Process of TVM Based on Parallel Genetic Algorithm       | YuChen Feng       | Beihang University       |
| 14:54       | Overhauling the Onnx Importer to Support Dyanmism       | Matthew Brookhart       | OctoML       |
| 15:00       | AdaTune (Microsoft)       | Menghao Li        | Microsoft       |
|          |          |          |          |
|          | **Dec 4 - Lightning Talks**   |          |          |
|----------|----------|----------|----------|
| Time     | Title    | Speakers | Company  |
| 13:40       | Real-time AI on edge servers with TVM       | Kazutaka Morita       | NTT       |
| 13:46       | Integrating and simulating hardware accelerators in TVM       | Luis Vega       | OctoML       |
| 13:58       | AArch64 pre-quantized networks performance       | Giuseppe Rossini       | Arm       |
| 14:04       | Hardware-aware Quantization in TVM       | Ziheng Jiang       | OctoML       |
| 14:10       | Integrating the Arm Ethos-N NPUs into TVM       | Matthew Barrett       | Arm       |
| 14:16       | Running AI WASM Model Securely in Sandbox using TVM and Wasmtime       | Leon Wang       | Huawei       |
| 14:22       | Ethos-U55 : microNPU support for uTVM       | Manupa Karunaratne       | Arm       |
| 14:28       | Enable TVM QNN on RISC-V with Subword SIMD Computation       | Jenq-Kuen Lee       | National Tsing-Hua University, Taiwan       |
| 14:34       | A Generic Framework Based on TVM/VTA for OpenCL-Compatible Cloud Devices       | Zhang Hao       | Fourth Paradigm Southeast Asia       |

## TVMConf Partners

<div class="partner-logos">
    <div class="partner-logo">
      <img src="images/partners/amd.png" height="80" />
    </div>

    <div class="partner-logo">
      <img src="images/partners/arm.png" height="80" />
    </div>

    <div class="partner-logo">
      <img src="images/partners/aws.png" height="80" />
    </div>

    <div class="partner-logo">
      <img src="images/partners/ntt.png" height="80" />
    </div>

    <div class="partner-logo">
      <img src="images/partners/octoml.png" height="80" />
    </div>

    <div class="partner-logo">
      <img src="images/partners/qualcomm.png" height="80" />
    </div>

    <div class="partner-logo">
      <img src="images/partners/sima.png" height="80" />
    </div>

    <div class="partner-logo">
      <img src="images/partners/xilinx.png" height="80" />
    </div>
</div>

## Community Sponsor

<div class="community_logo">
    <a href="https://apache.org">
        <img src="images/logo/asf.png" height="100"/>
    </a>
</div>


## Follow us on Twitter

<a href="https://twitter.com/ApacheTVM?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-show-count="false">Follow @ApacheTVM</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<br>
<a class="twitter-timeline" width="500" height="700" href="https://twitter.com/ApacheTVM?ref_src=twsrc%5Etfw">Tweets by ApacheTVM</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Past Conferences

- [TVM Conference 2019](2019)
- [TVM Conference 2018](2018)
