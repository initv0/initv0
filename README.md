# Val Kafedzhy

**Infrastructure & Security Architect** · enterprise platforms, networks, cloud, and AI systems · Washington, D.C. · 20+ years

I design, build, and secure enterprise platforms, networks, and cloud infrastructure. With more than 20 years of hands-on experience, I connect architecture decisions with reliable operations, practical security controls, and business priorities.

My career spans infrastructure engineering, cloud architecture, and CTO responsibility:

- Built data-center infrastructure for a hosting business serving **30,000 customers across 3,000 servers**, and roughly halved its infrastructure costs.
- Spent **nine years on email security products across 32 data centers**, with monitoring at about a million metrics every 10 seconds.

I write it up at **[vkafed.com](https://vkafed.com)** as reference architectures with working code, honest trade-offs and the failure modes that actually bite. The repos here are the code behind those articles.

## What I work on

- **Firewalls, zero trust and network security:** segmentation, policy in the data path, edge and east-west firewalls
- **Cryptography and PKI:** offline roots, HSM and smart-card keys, mTLS, certificate automation, OpenPGP
- **eBPF and the Linux kernel:** kernel-level observability and runtime security
- **DNS, email and SMTP:** DNSSEC, encrypted DNS, SPF, DKIM, DMARC, MTA-STS, DANE
- **Cloud and multi-region networking:** AWS, Google Cloud and Azure; BGP, anycast, IPv6, multi-region failover
- **Kubernetes and platform security:** GitOps, policy guardrails, fleets of thousands of servers
- **Engineering and risk:** controls supporting SOC 2 examinations and ISO 27001 certification, alongside work with PCI DSS, FIPS and GDPR requirements

I hold a Master of Laws (LL.M.), which helps me connect contractual and regulatory requirements with the technical controls behind them.

**Current focus:** the platforms and security foundations that AI systems depend on, including identity, isolation, resilient connectivity, and audit evidence.

## Start here

- **[Zero Trust, Beyond the Buzzword](https://vkafed.com/zero-trust-networking-beyond-the-buzzword-an-enterprise-reference-architecture/):** a vendor-neutral reference architecture with PDP/PEP, SPIFFE identity and a real Cilium policy.
- **[An offline CA with smart-card key storage](https://vkafed.com/creating-a-new-ca-sha-512-4096-bit-with-pkcs-11-smart-card-storage-and-subordinate-ca/):** a root and subordinate CA with keys on PKCS#11 hardware.
- **[eBPF in Production](https://vkafed.com/ebpf-in-production-kernel-level-observability-and-security/):** kernel-level observability and security without a sidecar in the data path.
- **[BGP for the AI Era](https://vkafed.com/bgp-for-the-ai-era-multi-region-routing-for-inference-workloads/):** anycast and BGP that fail over on real inference SLOs, not process liveness.
- **[The AI Inference Networking Maturity Model](https://vkafed.com/ai-inference-networking-maturity-model/):** five levels and six dimensions for scoring how ready a network is to serve inference.

Everything else, by topic: [vkafed.com/topics](https://vkafed.com/topics/)

## Reference repos

Public code and examples accompanying the articles.

| Repo | What it is |
|---|---|
| **[anycast-bgp-inference-reference](https://github.com/initv0/anycast-bgp-inference-reference)** | FRR and BGP config plus a health agent that ties route advertisement to inference SLOs (p99 latency, GPU queue depth), with a failover benchmark harness. |
| **[ebpf-observability-samples](https://github.com/initv0/ebpf-observability-samples)** | Runnable bpftrace, Tetragon and Cilium samples for kernel-level observability and security, plus CO-RE and XDP readiness checks. |

## Certifications

CKA · CKAD · CKS · AWS Solutions Architect Professional · Google Cloud Professional Cloud Architect · Cisco CCNP · Cisco CCNA · Red Hat RHCE

**In progress:** studying for CISSP.

## Get in touch

Happy to compare notes on infrastructure and security architecture, PKI, Zero Trust, or AI platforms.

For professional connections, technical discussions, speaking, or press: [LinkedIn](https://www.linkedin.com/in/vkafed/) or [vkafed.com/contact](https://vkafed.com/contact/).
