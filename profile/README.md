<h1 align="center">Welcome to Michael's Compute Kernel Lab</h1>

<p align="center">
  <img src="https://github.com/mmfhui-kernels.png?size=200" width="120" alt="Michael's Compute Kernel Lab logo">
</p>

<p align="center">Full documentation for compute kernels that are built and optimized step by step from scratch.</p>

## How each workload repository is structured

For every workload repository, I follow the same structured path to ensure strict numerical performance engineering practices. For setup, the algorithm/computation is explained (with its source paper when relevant), a correctness-first reference implementation is built, and existing implementations are profiled. For groundwork, I characterize the formulation, analyze precision relative to the domain, and create a measured roofline. Each optimization is then a separate version, which is always validated against the reference and benchmarked fairly against both its hardware ceiling and the top existing implementation.

## Kernels

<!-- kernels:start -->
_No published kernels yet._
<!-- kernels:end -->

## Infrastructure

- [kernel-harness](https://github.com/mmfhui-kernels/kernel-harness): reusable harness that builds, checks, and does benchmarking for every workload repository.
- [workload-template](https://github.com/mmfhui-kernels/workload-template): the starting structure for each and every workload in a template.

## Contact

Interested in a custom compute kernel for your specific workload?

hui[dot]m[at]northeastern[dot]edu

## Notice

This is a personal project that is built on my own time and independent of any employer or institution. I try my best to upstream improvements when it fits an existing open-source project, but some of the formulation decisions I make (every step of reasoning is outlined in each repository) to reach the highest percent of attainable performance may fundamentally be incompatible. All the compute kernels inside this organization are built to be standalone so I encourage you to try them out and find out what the fastest kernels are that fit your specific needs.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
