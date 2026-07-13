# Val Kafedzhy

**AI Infrastructure & Enterprise Platform Architect** · Washington, D.C. · 20+ years

I design the networking, platform, and security layer under large systems — lately,
specifically under AI at scale: routing inference traffic across regions, segmenting workloads
with Zero Trust, instrumenting the kernel with eBPF, and keeping GPU clusters fast and reachable
when a region degrades. I write it up with working configs, honest trade-offs, and real failure
modes — not vendor slideware.

Site: **[vkafed.com](https://vkafed.com)** · LinkedIn: **[in/vkafed](https://www.linkedin.com/in/vkafed/)**

## What I work on

- **BGP & enterprise routing** — anycast, multi-region failover, health-triggered route withdrawal, BFD
- **AI infrastructure networking** — inference traffic across regions under tight p99 SLOs
- **eBPF** — kernel-level observability and security without sidecar overhead
- **Zero Trust platform security** — identity-aware segmentation, policy enforced in the data path
- **Cloud & multi-region networking** — service meshes, IPv6, high-performance connectivity at scale

## Certifications

- **Kubernetes** — CKA, CKAD & CKS (the full CNCF trifecta, each earned 3×)
- **Cloud** — AWS Certified Solutions Architect – Professional (×2) · Google Professional Cloud Architect
- **Networking & Systems** — Cisco CCNP · Red Hat Certified Engineer (RHCE)

## Start here — recent writing

- **[BGP for the AI Era](https://vkafed.com/bgp-for-the-ai-era-multi-region-routing-for-inference-workloads/)** — anycast + BGP that fails over on real inference SLOs, not process liveness. Ships with a working FRR config and health agent.
- **[eBPF in Production](https://vkafed.com/ebpf-in-production-kernel-level-observability-and-security/)** — kernel-level observability and security without a sidecar in the data path. Runnable samples below.
- **[Zero Trust, Beyond the Buzzword](https://vkafed.com/zero-trust-networking-beyond-the-buzzword-an-enterprise-reference-architecture/)** — a vendor-neutral reference architecture: PDP/PEP, SPIFFE identity, a real Cilium policy.
- **[Service Mesh vs eBPF-Native Data Planes](https://vkafed.com/service-mesh-vs-ebpf-native-data-planes-how-to-choose/)** — the head-to-head on when sidecars still win.
- **[IPv6 at Enterprise Scale](https://vkafed.com/ipv6-at-enterprise-scale-a-migration-playbook/)** — a migration playbook: dual-stack core, a real address plan, NAT64/DNS64.

Browse by topic: [Networking & Routing](https://vkafed.com/category/networking-routing/) ·
[Cloud & Platform Networking](https://vkafed.com/category/cloud-platform-networking/) ·
[Zero Trust & Platform Security](https://vkafed.com/category/zero-trust-platform-security/) ·
[AI Infrastructure Networking](https://vkafed.com/category/ai-infrastructure-networking/)

## Reference repos (companions to the writing)

| Repo | What it is |
|---|---|
| **[anycast-bgp-inference-reference](https://github.com/initv0/anycast-bgp-inference-reference)** | FRR/BGP config + a health agent that ties route advertisement to real inference SLOs (p99 latency, GPU queue depth), with hysteresis to survive BGP dampening. Companion to the BGP article. |
| **[ebpf-observability-samples](https://github.com/initv0/ebpf-observability-samples)** | Runnable bpftrace, Tetragon, and Cilium samples for kernel-level observability and security — no sidecars — plus BTF/CO-RE and XDP readiness checks. Companion to the eBPF article. |

## Let's talk

Open to advisory and consulting conversations on multi-region routing, Zero-Trust segmentation,
and the networking layer under AI platforms. Happy to compare notes either way.

- Site: [vkafed.com](https://vkafed.com)
- LinkedIn: [linkedin.com/in/vkafed](https://www.linkedin.com/in/vkafed/)
