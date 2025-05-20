# Function: <code>set_my_cpu_offset</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_my_cpu_offset(long unsigned int off);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/setup.c (ffff800011433fa0)
Location: arch/arm64/include/asm/percpu.h:14
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:smp_setup_processor_id
```
```
In arch/arm64/kernel/smp.c (ffff80001009c230)
Location: arch/arm64/include/asm/percpu.h:14
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:secondary_start_kernel
Direct callers:
  - arch/arm64/kernel/smp.c:smp_prepare_boot_cpu
```
**Symbols:**

```
ffff80001009ba70-ffff80001009ba78: set_my_cpu_offset (STB_LOCAL)
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
In arch/arm/kernel/setup.c (c1504470)
Location: arch/arm/include/asm/percpu.h:13
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:smp_setup_processor_id
  - arch/arm/kernel/setup.c:cpu_init
```
```
In arch/arm/kernel/smp.c (c1505c70)
Location: arch/arm/include/asm/percpu.h:13
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_prepare_boot_cpu
```
</details>
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
<b>Arch</b>
<ul>
</ul>
