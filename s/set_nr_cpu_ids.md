# Function: <code>set_nr_cpu_ids</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff83e717b7)
Location: include/linux/cpumask.h:44
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/smpboot.c (ffffffff83e89fd1)
Location: include/linux/cpumask.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In kernel/smp.c (ffffffff83eaebf2)
Location: include/linux/cpumask.h:44
Inline: True
Inline callers:
  - kernel/smp.c:nrcpus
  - kernel/smp.c:setup_nr_cpu_ids
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
In arch/x86/xen/smp_pv.c (ffffffff83692694)
Location: include/linux/cpumask.h:44
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/smpboot.c (ffffffff836ad672)
Location: include/linux/cpumask.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In kernel/smp.c (ffffffff836d3c22)
Location: include/linux/cpumask.h:44
Inline: True
Inline callers:
  - kernel/smp.c:nrcpus
  - kernel/smp.c:setup_nr_cpu_ids
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
In arch/x86/xen/smp_pv.c (ffffffff838c21a4)
Location: include/linux/cpumask.h:44
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/smpboot.c (ffffffff838ddcbf)
Location: include/linux/cpumask.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In kernel/smp.c (ffffffff83905c02)
Location: include/linux/cpumask.h:44
Inline: True
Inline callers:
  - kernel/smp.c:nrcpus
  - kernel/smp.c:setup_nr_cpu_ids
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
