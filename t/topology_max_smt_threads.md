# Function: <code>topology_max_smt_threads</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/topology.h:126
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/include/asm/topology.h:126
Inline: True
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/topology.h:126
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/include/asm/topology.h:126
Inline: True
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/topology.h:126
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/include/asm/topology.h:126
Inline: True
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/topology.h:120
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/include/asm/topology.h:120
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/topology.h:120
Inline: True
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
In arch/x86/events/core.c (ffffffff81007ca5)
Location: arch/x86/include/asm/topology.h:120
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff826d0872)
Location: arch/x86/include/asm/topology.h:120
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff826e46e2)
Location: arch/x86/include/asm/topology.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:calculate_max_logical_packages
```
```
In kernel/cpu.c (ffffffff8108f815)
Location: arch/x86/include/asm/topology.h:120
Inline: True
Inline callers:
  - kernel/cpu.c:show_smt_active
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
In arch/x86/events/core.c (ffffffff81007b85)
Location: arch/x86/include/asm/topology.h:120
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff828869d1)
Location: arch/x86/include/asm/topology.h:120
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff8289b1b7)
Location: arch/x86/include/asm/topology.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:calculate_max_logical_packages
```
```
In kernel/cpu.c (ffffffff81097b15)
Location: arch/x86/include/asm/topology.h:120
Inline: True
Inline callers:
  - kernel/cpu.c:show_smt_active
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
In arch/x86/events/core.c (ffffffff81007e45)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff8289d8bd)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b2f93)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:calculate_max_logical_packages
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
In arch/x86/events/core.c (ffffffff81008065)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff828a092c)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b63ee)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:calculate_max_logical_packages
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
In arch/x86/events/core.c (ffffffff810090d5)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff82cc6b8a)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff82cdb591)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:calculate_max_logical_packages
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
In arch/x86/events/core.c (ffffffff81008185)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff82fb25a7)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff82fc79e7)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:calculate_max_logical_packages
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
In arch/x86/events/core.c (ffffffff810089f5)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff831bc675)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff831d227f)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:calculate_max_logical_packages
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
In arch/x86/events/core.c (ffffffff81009835)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff8329c973)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff832b4a8e)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:calculate_max_logical_packages
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
In arch/x86/events/core.c (ffffffff81008f15)
Location: arch/x86/include/asm/topology.h:134
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff8344b451)
Location: arch/x86/include/asm/topology.h:134
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff83466341)
Location: arch/x86/include/asm/topology.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:calculate_max_logical_packages
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
In arch/x86/events/core.c (ffffffff8100a2b5)
Location: arch/x86/include/asm/topology.h:134
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff83e662e2)
Location: arch/x86/include/asm/topology.h:134
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff83e89d5f)
Location: arch/x86/include/asm/topology.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
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
In arch/x86/events/core.c (ffffffff81009b05)
Location: arch/x86/include/asm/topology.h:134
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff83686952)
Location: arch/x86/include/asm/topology.h:134
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff836ad461)
Location: arch/x86/include/asm/topology.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
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
In arch/x86/events/core.c (ffffffff8100f225)
Location: arch/x86/include/asm/topology.h:134
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff838b5b62)
Location: arch/x86/include/asm/topology.h:134
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff838dd941)
Location: arch/x86/include/asm/topology.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In arch/x86/events/core.c (ffffffff81008065)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff8288e92c)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff828a43f5)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:calculate_max_logical_packages
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
In arch/x86/events/core.c (ffffffff81006855)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff8288c892)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff8289c537)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:calculate_max_logical_packages
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
In arch/x86/events/core.c (ffffffff81008025)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff828a192c)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b7305)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:calculate_max_logical_packages
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
In arch/x86/events/core.c (ffffffff81008185)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/core.c:events_ht_sysfs_show
```
```
In arch/x86/events/intel/core.c (ffffffff828a1940)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:fixup_ht_bug
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b7406)
Location: arch/x86/include/asm/topology.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:calculate_max_logical_packages
```
</details>
</li>
</ul>

## Differences
