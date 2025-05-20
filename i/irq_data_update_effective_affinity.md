# Function: <code>irq_data_update_effective_affinity</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81056e5f)
Location: include/linux/irq.h:786
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid
```
```
In drivers/xen/events/events_base.c (ffffffff8155910d)
Location: include/linux/irq.h:786
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff8105b3b7)
Location: include/linux/irq.h:815
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In drivers/xen/events/events_base.c (ffffffff815bd4fd)
Location: include/linux/irq.h:815
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff8105e2f5)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In drivers/xen/events/events_base.c (ffffffff815f5ba7)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff81063f85)
Location: include/linux/irq.h:818
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In drivers/xen/events/events_base.c (ffffffff81610c67)
Location: include/linux/irq.h:818
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff81067646)
Location: include/linux/irq.h:831
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In drivers/xen/events/events_base.c (ffffffff81644940)
Location: include/linux/irq.h:831
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff81067f86)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In drivers/xen/events/events_base.c (ffffffff81666ef0)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff8106f090)
Location: include/linux/irq.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In drivers/xen/events/events_base.c (ffffffff81716d00)
Location: include/linux/irq.h:879
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff8107061e)
Location: include/linux/irq.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In drivers/xen/events/events_base.c (ffffffff81734220)
Location: include/linux/irq.h:892
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff81070e0e)
Location: include/linux/irq.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In drivers/xen/events/events_base.c (ffffffff81717d34)
Location: include/linux/irq.h:894
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107cae6)
Location: include/linux/irq.h:896
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In drivers/xen/events/events_base.c (ffffffff81795603)
Location: include/linux/irq.h:896
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108c105)
Location: include/linux/irq.h:900
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In drivers/xen/events/events_base.c (ffffffff818ce33e)
Location: include/linux/irq.h:900
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a0865)
Location: include/linux/irq.h:915
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In kernel/irq/manage.c (ffffffff811976c3)
Location: include/linux/irq.h:915
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In drivers/xen/events/events_base.c (ffffffff81a1f95f)
Location: include/linux/irq.h:915
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a37e7)
Location: include/linux/irq.h:928
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In kernel/irq/manage.c (ffffffff811a9291)
Location: include/linux/irq.h:928
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In drivers/xen/events/events_base.c (ffffffff81a68ca9)
Location: include/linux/irq.h:928
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810aa805)
Location: include/linux/irq.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In kernel/irq/manage.c (ffffffff811b8df1)
Location: include/linux/irq.h:910
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In drivers/xen/events/events_base.c (ffffffff81abb8f6)
Location: include/linux/irq.h:910
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
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
In drivers/irqchip/irq-gic.c (ffff80001066c3c0)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066f270)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010671c5c)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800010676eb8)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_set_affinity
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b690)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_set_affinity
```
```
In drivers/xen/events/events_base.c (ffff800010830bb4)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/irqchip/irq-hip04.c (c0813fcc)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_irq_set_affinity
```
```
In drivers/irqchip/irq-gic.c (c0815744)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3.c (c0818028)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081b1c0)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081ebd4)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_set_affinity
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-sifive-plic.c (0)
Location: include/linux/irq.h:855
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
In arch/x86/kernel/apic/vector.c (ffffffff81067a76)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In drivers/xen/events/events_base.c (ffffffff8162cc20)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81057de6)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
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
In arch/x86/kernel/apic/vector.c (ffffffff81067f26)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In drivers/xen/events/events_base.c (ffffffff8165ad30)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In arch/x86/kernel/apic/vector.c (ffffffff810695e6)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In drivers/xen/events/events_base.c (ffffffff81675320)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
```
</details>
</li>
</ul>

## Differences
