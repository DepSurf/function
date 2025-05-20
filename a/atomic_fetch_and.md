# Function: <code>atomic_fetch_and</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d0bd4)
Location: include/asm-generic/atomic-instrumented.h:292
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
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
In kernel/sched/fair.c (ffffffff810da414)
Location: include/asm-generic/atomic-instrumented.h:339
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815522f5)
Location: include/asm-generic/atomic-instrumented.h:339
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/fair.c (ffffffff810e1726)
Location: include/asm-generic/atomic-instrumented.h:425
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81582245)
Location: include/asm-generic/atomic-instrumented.h:425
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/fair.c (ffffffff810ebdc6)
Location: include/asm-generic/atomic-instrumented.h:425
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3c7f)
Location: include/asm-generic/atomic-instrumented.h:425
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c89f)
Location: include/asm-generic/atomic-instrumented.h:426
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670bef)
Location: include/asm-generic/atomic-instrumented.h:426
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816530a5)
Location: include/asm-generic/atomic-instrumented.h:426
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c4e15)
Location: include/linux/atomic/atomic-instrumented.h:312
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817eab15)
Location: include/linux/atomic/atomic-instrumented.h:329
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81910d45)
Location: include/linux/atomic/atomic-instrumented.h:329
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81954465)
Location: include/linux/atomic/atomic-instrumented.h:766
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199d8f5)
Location: include/linux/atomic/atomic-instrumented.h:766
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070c7e4)
Location: include/asm-generic/atomic-instrumented.h:425
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019e9b0)
Location: include/linux/atomic-fallback.h:635
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
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
In kernel/sched/fair.c (ffffffe0000f5744)
Location: arch/riscv/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d9078)
Location: arch/riscv/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/fair.c (ffffffff810e5f26)
Location: include/asm-generic/atomic-instrumented.h:425
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8159748f)
Location: include/asm-generic/atomic-instrumented.h:425
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/fair.c (ffffffff810d50c6)
Location: include/asm-generic/atomic-instrumented.h:425
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8158661f)
Location: include/asm-generic/atomic-instrumented.h:425
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/fair.c (ffffffff810e22f6)
Location: include/asm-generic/atomic-instrumented.h:425
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815979cf)
Location: include/asm-generic/atomic-instrumented.h:425
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/fair.c (ffffffff810ede96)
Location: include/asm-generic/atomic-instrumented.h:425
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b1e0f)
Location: include/asm-generic/atomic-instrumented.h:425
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
</details>
</li>
</ul>

## Differences
