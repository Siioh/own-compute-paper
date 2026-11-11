# The Case for User-Controlled Cloud Agents

Tyler Ramsarran, November 2026

**[Read the paper (PDF)](own-compute-white-paper.pdf)**

Direct download: https://github.com/Siioh/own-compute-paper/releases/latest/download/own-compute-white-paper.pdf

## Abstract

Coding agents, language-model programs that edit files and run commands, execute on user-held compute: machines and allocations their users own or may use. Vendor and research-center documentation shows agents on SSH hosts, customer-run machines, GPU workstations and cluster login nodes, and it marks the limits of these execution paths. In five products a session is bound to one environment. Where vendor products run tools on user-held compute, the vendor runs the agent loop or receives the session’s event stream. On the shared research systems reviewed here, each center sets its own agent rules, and agents act with the full reach of the user’s account. These limits matter in research computing and in development tasks that span machines and operating systems. This paper argues for a user-controlled cloud agent: like a vendor’s cloud session, it keeps running after the user closes the laptop and lets the user steer it from any device. It runs on user-held compute, keeps a multi-machine task under one point of control, follows each site’s rules and uses a model endpoint and access the user controls. The paper states five requirements for it.

The paper motivates Own Compute, a Hermes Agent plugin by the author.

## Citation

```bibtex
@misc{ramsarran2026usercontrolled,
  author       = {Tyler Ramsarran},
  title        = {The Case for User-Controlled Cloud Agents},
  year         = {2026},
  month        = nov,
  howpublished = {\url{https://github.com/Siioh/own-compute-paper}}
}
```

## License

This paper is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See [LICENSE](LICENSE).
