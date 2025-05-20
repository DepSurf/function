# Function: <code>arch_atomic_fetch_and</code>

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
Location: arch/x86/include/asm/atomic.h:213
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
Location: arch/x86/include/asm/atomic.h:216
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815522f5)
Location: arch/x86/include/asm/atomic.h:216
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
Location: arch/x86/include/asm/atomic.h:216
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81582245)
Location: arch/x86/include/asm/atomic.h:216
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
Location: arch/x86/include/asm/atomic.h:216
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3c7f)
Location: arch/x86/include/asm/atomic.h:216
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/core.c (ffffffff810dd8ce)
Location: arch/x86/include/asm/atomic.h:222
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/irq_work.c (ffffffff811f74f0)
Location: arch/x86/include/asm/atomic.h:222
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c89f)
Location: arch/x86/include/asm/atomic.h:222
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/core.c (ffffffff810da1de)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670bef)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/core.c (ffffffff810dbe51)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff810f6a5a)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816530a5)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/core.c (ffffffff810f01ad)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff811109de)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c4e15)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/core.c (ffffffff8110d76d)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff8112cbb2)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817eab15)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/core.c (ffffffff81133f0d)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff811568b2)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81910d45)
Location: arch/x86/include/asm/atomic.h:220
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/core.c (ffffffff81142c09)
Location: arch/x86/include/asm/atomic.h:133
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff8116692c)
Location: arch/x86/include/asm/atomic.h:133
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81954465)
Location: arch/x86/include/asm/atomic.h:133
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
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
In kernel/sched/core.c (ffffffff8114dbc9)
Location: arch/x86/include/asm/atomic.h:133
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff8117366c)
Location: arch/x86/include/asm/atomic.h:133
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199d8f5)
Location: arch/x86/include/asm/atomic.h:133
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
Location: arch/arm64/include/asm/atomic.h:50
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
Location: arch/x86/include/asm/atomic.h:216
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8159748f)
Location: arch/x86/include/asm/atomic.h:216
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
Location: arch/x86/include/asm/atomic.h:216
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8158661f)
Location: arch/x86/include/asm/atomic.h:216
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
Location: arch/x86/include/asm/atomic.h:216
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815979cf)
Location: arch/x86/include/asm/atomic.h:216
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
Location: arch/x86/include/asm/atomic.h:216
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b1e0f)
Location: arch/x86/include/asm/atomic.h:216
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
</details>
</li>
</ul>

## Differences
