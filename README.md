# Val Kafedzhy

**AI Infrastructure Security Architect** · Washington, D.C. · 20+ years

I design security for the platforms AI runs on: identity, keys, networks, and the controls an auditor signs off on. Over 20 years I've gone from hosting engineer to cloud architect and CTO, spent nine years on Cisco's email security products, and today I work on security and infrastructure for cloud security services.

I write it up at **[vkafed.com](https://vkafed.com)** as reference architectures with working code, honest trade-offs and the failure modes that actually bite. The repos here are the code behind those articles.

## What I work on

- **PKI and encryption:** CA design with offline roots and hardware keys, mTLS, certificate automation, OpenPGP
- **Zero trust and network security:** identity-aware segmentation, BGP and anycast, IPv6, eBPF in the data path
- **Kubernetes and platform security:** GitOps, policy guardrails, runtime security
- **DNS and email security:** DNSSEC, encrypted DNS, SPF, DKIM, DMARC, MTA-STS and DANE
- **Compliance:** SOC 2, ISO 27001, PCI DSS, FIPS and GDPR controls

**Now building:** an AI inference security reference architecture with a tested lab, covering workload and agent identity, the model supply chain, tool-use boundaries and isolation, published one chapter at a time on vkafed.com.

## Start here

- **[Zero Trust, Beyond the Buzzword](https://vkafed.com/zero-trust-networking-beyond-the-buzzword-an-enterprise-reference-architecture/):** a vendor-neutral reference architecture with PDP/PEP, SPIFFE identity and a real Cilium policy.
- **[An offline CA with smart-card key storage](https://vkafed.com/creating-a-new-ca-sha-512-4096-bit-with-pkcs-11-smart-card-storage-and-subordinate-ca/):** a root and subordinate CA with keys on PKCS#11 hardware.
- **[eBPF in Production](https://vkafed.com/ebpf-in-production-kernel-level-observability-and-security/):** kernel-level observability and security without a sidecar in the data path.
- **[BGP for the AI Era](https://vkafed.com/bgp-for-the-ai-era-multi-region-routing-for-inference-workloads/):** anycast and BGP that fail over on real inference SLOs, not process liveness.
- **[The AI Inference Networking Maturity Model](https://vkafed.com/ai-inference-networking-maturity-model/):** five levels and six dimensions for scoring how ready a network is to serve inference.

Everything else, by topic: [vkafed.com/topics](https://vkafed.com/topics/)

## Reference repos

Personal work, built on my own time and equipment.

| Repo | What it is |
|---|---|
| **[anycast-bgp-inference-reference](https://github.com/initv0/anycast-bgp-inference-reference)** | FRR and BGP config plus a health agent that ties route advertisement to inference SLOs (p99 latency, GPU queue depth), with a failover benchmark harness. |
| **[ebpf-observability-samples](https://github.com/initv0/ebpf-observability-samples)** | Runnable bpftrace, Tetragon and Cilium samples for kernel-level observability and security, plus CO-RE and XDP readiness checks. |

## Certifications

CKA · CKAD · CKS · AWS Solutions Architect Professional · Google Cloud Professional Cloud Architect · Cisco CCNP · Red Hat RHCE

## Get in touch

Happy to compare notes on securing AI infrastructure, PKI or zero trust, and open to speaking and press requests: [LinkedIn](https://www.linkedin.com/in/vkafed/) or [vkafed.com/contact](https://vkafed.com/contact/).
