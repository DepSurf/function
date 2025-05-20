# Function: <code>cpu_have_feature</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool cpu_have_feature(unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/cpufeature.c (ffff800010099ad8)
Location: arch/arm64/kernel/cpufeature.c:2048
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:verify_local_elf_hwcaps
Direct callers:
  - arch/arm64/kernel/fpsimd.c:fpsimd_init
  - arch/arm64/kernel/fpsimd.c:fpsimd_init
  - arch/arm64/kernel/process.c:__switch_to
  - arch/arm64/kernel/cpuinfo.c:c_show
  - drivers/base/cpu.c:print_cpu_modalias
```
**Symbols:**

```
ffff800010099540-ffff80001009958c: cpu_have_feature (STB_GLOBAL)
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
In drivers/base/cpu.c (c09dc3b8)
Location: arch/arm/include/asm/cpufeature.h:30
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpu_modalias
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
In drivers/base/cpu.c (c000000000987798)
Location: arch/powerpc/include/asm/cpufeature.h:28
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpu_modalias
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
