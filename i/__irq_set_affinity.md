# Function: <code>__irq_set_affinity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810dc190)
Location: kernel/irq/manage.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_resume
  - arch/x86/kernel/hpet.c:hpet_work
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff810dc190-ffffffff810dc1f8: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e18a0)
Location: kernel/irq/manage.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_resume
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff810e18a0-ffffffff810e1908: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e81f0)
Location: kernel/irq/manage.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff810e81f0-ffffffff810e8258: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7610)
Location: kernel/irq/manage.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_work
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff810e7610-ffffffff810e7678: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ef990)
Location: kernel/irq/manage.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_work
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff810ef990-ffffffff810ef9f8: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f7dc0)
Location: kernel/irq/manage.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_work
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff810f7dc0-ffffffff810f7e28: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81103510)
Location: kernel/irq/manage.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_work
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff81103510-ffffffff81103578: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110bf20)
Location: kernel/irq/manage.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff8110bf20-ffffffff8110bf8b: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81118350)
Location: kernel/irq/manage.c:304
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff81118350-ffffffff811183bb: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81123c79)
Location: kernel/irq/manage.c:380
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_hint
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff81123ce0-ffffffff81123d4b: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111fac9)
Location: kernel/irq/manage.c:450
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_hint
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
**Symbols:**

```
ffffffff8111fb40-ffffffff8111fbab: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111fd79)
Location: kernel/irq/manage.c:450
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_hint
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
**Symbols:**

```
ffffffff8111fdf0-ffffffff8111fe5b: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81140219)
Location: kernel/irq/manage.c:443
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81163b86)
Location: kernel/irq/manage.c:458
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81197866)
Location: kernel/irq/manage.c:450
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a9526)
Location: kernel/irq/manage.c:453
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b9086)
Location: kernel/irq/manage.c:455
Inline: True
Inline callers:
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/manage.c:irq_force_affinity
  - kernel/irq/manage.c:irq_set_affinity
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017ab48)
Location: kernel/irq/manage.c:304
Inline: False
Direct callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_flush_hwstate
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/soc/fsl/qbman/bman_portal.c:bman_online_cpu
  - drivers/soc/fsl/qbman/bman_portal.c:bman_offline_cpu
  - drivers/soc/fsl/qbman/qman_portal.c:qman_online_cpu
  - drivers/soc/fsl/qbman/qman_portal.c:qman_offline_cpu
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/perf/arm_pmu.c:armpmu_request_irq
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_online_cpu
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu
  - drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu
```
**Symbols:**

```
ffff80001017ab48-ffff80001017ac1c: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cbdc4)
Location: kernel/irq/manage.c:304
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/clocksource/timer-tegra.c:tegra_timer_setup
  - drivers/clocksource/exynos_mct.c:exynos4_mct_starting_cpu
  - drivers/perf/arm_pmu.c:armpmu_request_irq
```
**Symbols:**

```
c03cbdc4-c03cbe2c: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d50b0)
Location: kernel/irq/manage.c:304
Inline: False
Direct callers:
  - arch/powerpc/sysdev/xics/xics-common.c:xics_migrate_irqs_away
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
**Symbols:**

```
c0000000001d50b0-c0000000001d515c: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000114908)
Location: kernel/irq/manage.c:304
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_hint
```
**Symbols:**

```
ffffffe000114908-ffffffe00011497c: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81110930)
Location: kernel/irq/manage.c:304
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff81110930-ffffffff8111099b: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81101660)
Location: kernel/irq/manage.c:304
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
**Symbols:**

```
ffffffff81101660-ffffffff811016cb: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110e820)
Location: kernel/irq/manage.c:304
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff8110e820-ffffffff8110e88b: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __irq_set_affinity(unsigned int irq, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81119d50)
Location: kernel/irq/manage.c:304
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff81119d50-ffffffff81119dbb: __irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
