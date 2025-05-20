# Function: <code>sched_smt_active</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81044d3d)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
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
In arch/x86/kernel/cpu/bugs.c (ffffffff810474be)
Location: include/linux/sched/smt.h:10
Inline: True
```
```
In kernel/cpu.c (ffffffff8109c0d5)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:show_smt_active
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81048350)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In kernel/cpu.c (ffffffff810a2655)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:show_smt_active
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b9f1)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:tsx_async_abort_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In kernel/cpu.c (ffffffff810a9325)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:show_smt_active
```
```
In kernel/sched/topology.c (ffffffff81100f4c)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_perf_domains
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8104af31)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:tsx_async_abort_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In kernel/cpu.c (ffffffff810a4d75)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:show_smt_active
```
```
In kernel/sched/topology.c (ffffffff810ffaa0)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_perf_domains
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c811)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:tsx_async_abort_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In kernel/cpu.c (ffffffff810a5a75)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:show_smt_active
```
```
In kernel/sched/fair.c (ffffffff810ec0a1)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
```
```
In kernel/sched/topology.c (ffffffff81101ee0)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_perf_domains
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81053cf1)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:tsx_async_abort_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:unpriv_ebpf_notify
```
```
In kernel/cpu.c (ffffffff810b72d5)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:active_show
```
```
In kernel/sched/fair.c (ffffffff81104674)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
```
```
In kernel/sched/topology.c (ffffffff8111e857)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_perf_domains
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8105f856)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:retbleed_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:mmio_stale_data_show_state
  - arch/x86/kernel/cpu/bugs.c:tsx_async_abort_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:unpriv_ebpf_notify
```
```
In kernel/cpu.c (ffffffff810cda75)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:active_show
```
```
In kernel/sched/fair.c (ffffffff81121b0f)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
```
```
In kernel/sched/build_utility.c (ffffffff81142ed7)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_perf_domains
```
```
In drivers/idle/intel_idle.c (ffffffff81f29365)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_ibrs
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8106e146)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:retbleed_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:mmio_stale_data_show_state
  - arch/x86/kernel/cpu/bugs.c:tsx_async_abort_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:unpriv_ebpf_notify
```
```
In kernel/cpu.c (ffffffff810ebba5)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:active_show
```
```
In kernel/sched/fair.c (ffffffff8114d4d4)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
```
```
In kernel/sched/build_utility.c (ffffffff8117041f)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_perf_domains
```
```
In drivers/idle/intel_idle.c (ffffffff820d5175)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_ibrs
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81070fd6)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mmio_stale_data
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mmio_stale_data
  - arch/x86/kernel/cpu/bugs.c:retbleed_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:tsx_async_abort_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:unpriv_ebpf_notify
```
```
In kernel/cpu.c (ffffffff810f7885)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:active_show
```
```
In kernel/sched/fair.c (ffffffff81154255)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_use_asym_prio
  - kernel/sched/fair.c:select_idle_sibling
```
```
In kernel/sched/build_utility.c (ffffffff8118002f)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_perf_domains
```
```
In drivers/idle/intel_idle.c (ffffffff821437d0)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_ibrs
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81076cd6)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:retbleed_show_state
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:tsx_async_abort_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:mds_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:l1tf_show_state
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:unpriv_ebpf_notify
```
```
In kernel/cpu.c (ffffffff81100c35)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:active_show
```
```
In kernel/sched/fair.c (ffffffff81161a25)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_use_asym_prio
  - kernel/sched/fair.c:select_idle_sibling
```
```
In kernel/sched/build_utility.c (ffffffff8118ed60)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_is_eas_possible
```
```
In drivers/idle/intel_idle.c (ffffffff82225ee0)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_ibrs
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
In kernel/cpu.c (ffff8000100f77d8)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:show_smt_active
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (0)
Location: include/linux/sched/smt.h:15
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013df7c)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:show_smt_active
```
</details>
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
In arch/x86/kernel/cpu/bugs.c (ffffffff810484c0)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In kernel/cpu.c (ffffffff8109bf75)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:show_smt_active
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81037820)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In kernel/cpu.c (ffffffff8108a9a5)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:show_smt_active
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81048300)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In kernel/cpu.c (ffffffff8109bf25)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:show_smt_active
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81049710)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In kernel/cpu.c (ffffffff810a3b25)
Location: include/linux/sched/smt.h:10
Inline: True
Inline callers:
  - kernel/cpu.c:show_smt_active
```
</details>
</li>
</ul>

## Differences
