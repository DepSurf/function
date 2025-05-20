# Function: <code>irq_set_affinity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810622d2)
Location: include/linux/interrupt.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_resume
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/irq/proc.c (ffffffff810e1d10)
Location: include/linux/interrupt.h:240
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff810fc82b)
Location: include/linux/interrupt.h:240
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff810fcdaa)
Location: include/linux/interrupt.h:240
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/events/events_base.c (ffffffff814c9897)
Location: include/linux/interrupt.h:240
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106239d)
Location: include/linux/interrupt.h:251
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_resume
```
```
In kernel/irq/proc.c (ffffffff810e77b0)
Location: include/linux/interrupt.h:251
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff81103b7b)
Location: include/linux/interrupt.h:251
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff8110410f)
Location: include/linux/interrupt.h:251
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/events/events_base.c (ffffffff8151a3cb)
Location: include/linux/interrupt.h:251
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106540d)
Location: include/linux/interrupt.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/kernel/hpet.c:hpet_msi_resume
```
```
In kernel/irq/proc.c (ffffffff810ee17b)
Location: include/linux/interrupt.h:263
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff8110b26c)
Location: include/linux/interrupt.h:263
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff8110b810)
Location: include/linux/interrupt.h:263
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/events/events_base.c (ffffffff815468bb)
Location: include/linux/interrupt.h:263
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106433c)
Location: include/linux/interrupt.h:272
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/irq/proc.c (ffffffff810eda2f)
Location: include/linux/interrupt.h:272
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff8110d15c)
Location: include/linux/interrupt.h:272
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff8110d700)
Location: include/linux/interrupt.h:272
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/events/events_base.c (ffffffff8155a6d7)
Location: include/linux/interrupt.h:272
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810684bc)
Location: include/linux/interrupt.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/irq/proc.c (ffffffff810f645f)
Location: include/linux/interrupt.h:274
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff811183dc)
Location: include/linux/interrupt.h:274
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff81118990)
Location: include/linux/interrupt.h:274
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/events/events_base.c (ffffffff815beb17)
Location: include/linux/interrupt.h:274
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106b00d)
Location: include/linux/interrupt.h:272
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/irq/proc.c (ffffffff810fe77b)
Location: include/linux/interrupt.h:272
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff81124f5a)
Location: include/linux/interrupt.h:272
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81125527)
Location: include/linux/interrupt.h:272
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/events/events_base.c (ffffffff815f7147)
Location: include/linux/interrupt.h:272
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81070d9d)
Location: include/linux/interrupt.h:286
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/irq/proc.c (ffffffff81109f4b)
Location: include/linux/interrupt.h:286
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff8113065a)
Location: include/linux/interrupt.h:286
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81130c17)
Location: include/linux/interrupt.h:286
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/events/events_base.c (ffffffff816121e7)
Location: include/linux/interrupt.h:286
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074d15)
Location: include/linux/interrupt.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/proc.c (ffffffff8111363f)
Location: include/linux/interrupt.h:313
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff8113b1a9)
Location: include/linux/interrupt.h:313
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8113b777)
Location: include/linux/interrupt.h:313
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/events/events_base.c (ffffffff81645f64)
Location: include/linux/interrupt.h:313
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81075ce5)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/proc.c (ffffffff8111f7b3)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff81146db9)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81147387)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/events/events_base.c (ffffffff816684e4)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d0ca)
Location: include/linux/interrupt.h:329
Inline: True
```
```
In kernel/irq/proc.c (ffffffff8112bcec)
Location: include/linux/interrupt.h:329
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff81156c7a)
Location: include/linux/interrupt.h:329
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff81157204)
Location: include/linux/interrupt.h:329
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/events/events_base.c (ffffffff81718699)
Location: include/linux/interrupt.h:329
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107cfea)
Location: include/linux/interrupt.h:330
Inline: True
```
```
In kernel/irq/proc.c (ffffffff8112770b)
Location: include/linux/interrupt.h:330
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff81152d9a)
Location: include/linux/interrupt.h:330
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff811532d4)
Location: include/linux/interrupt.h:330
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/platform-pci.c (ffffffff81740124)
Location: include/linux/interrupt.h:330
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107e1c5)
Location: include/linux/interrupt.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/proc.c (ffffffff811279ca)
Location: include/linux/interrupt.h:334
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff8115408a)
Location: include/linux/interrupt.h:334
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff811546d4)
Location: include/linux/interrupt.h:334
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/platform-pci.c (ffffffff81723b74)
Location: include/linux/interrupt.h:334
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_set_affinity(unsigned int irq, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81140280)
Location: kernel/irq/manage.c:466
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
**Symbols:**

```
ffffffff81140280-ffffffff811402e2: irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_set_affinity(unsigned int irq, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81163bd0)
Location: kernel/irq/manage.c:481
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
**Symbols:**

```
ffffffff81163bd0-ffffffff81163c39: irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_set_affinity(unsigned int irq, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811978c0)
Location: kernel/irq/manage.c:473
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
**Symbols:**

```
ffffffff811978c0-ffffffff81197929: irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_set_affinity(unsigned int irq, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a9580)
Location: kernel/irq/manage.c:476
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
**Symbols:**

```
ffffffff811a9580-ffffffff811a95e9: irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_set_affinity(unsigned int irq, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b90e0)
Location: kernel/irq/manage.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
**Symbols:**

```
ffffffff811b90e0-ffffffff811b9149: irq_set_affinity (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/vgic/vgic-v4.c (ffff8000100e0bac)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_flush_hwstate
```
```
In kernel/irq/proc.c (ffff800010185488)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-common.c (ffff8000101b1bc0)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffff8000101b24a0)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b518)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff8000107257a8)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff8000107262bc)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
```
```
In drivers/soc/fsl/qbman/bman_portal.c (ffff800010810db4)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_portal.c:bman_online_cpu
  - drivers/soc/fsl/qbman/bman_portal.c:bman_offline_cpu
```
```
In drivers/soc/fsl/qbman/qman_portal.c (ffff800010811344)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_portal.c:qman_online_cpu
  - drivers/soc/fsl/qbman/qman_portal.c:qman_offline_cpu
```
```
In drivers/soc/fsl/qbman/bman.c (ffff800010812160)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010815b24)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
```
```
In drivers/xen/events/events_base.c (ffff800010832500)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b96bfc)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_online_cpu
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99c24)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c680)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (c03d4474)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-common.c (c03fc43c)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (c03fcce0)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/sysdev/xics/xics-common.c (c0000000000ba6fc)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/xics-common.c:xics_migrate_irqs_away
```
```
In kernel/irq/proc.c (c0000000001df990)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-common.c (c000000000216e80)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-broadcast.c (c000000000217c68)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffe00011c286)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-common.c (ffffffe00013a418)
Location: include/linux/interrupt.h:314
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074ce5)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/proc.c (ffffffff81117d93)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff8113f569)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8113f9a7)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/events/events_base.c (ffffffff8162e214)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064d15)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/proc.c (ffffffff81108e03)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff811320b8)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81132727)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074c95)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/proc.c (ffffffff81115c83)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff8113d289)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8113d857)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/events/events_base.c (ffffffff8165c324)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81076cf5)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/proc.c (ffffffff811212b3)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff81149d79)
Location: include/linux/interrupt.h:314
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a367)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In drivers/xen/events/events_base.c (ffffffff81676914)
Location: include/linux/interrupt.h:314
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
