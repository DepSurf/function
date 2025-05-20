# Function: <code>__cache_amd_cpumap_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f222)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:805
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103efdd)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:805
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e9a8)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:806
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103c97a)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:807
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f7c9)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:808
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81040dda)
Location: arch/x86/kernel/cpu/cacheinfo.c:850
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810423eb)
Location: arch/x86/kernel/cpu/cacheinfo.c:877
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044849)
Location: arch/x86/kernel/cpu/cacheinfo.c:877
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044f99)
Location: arch/x86/kernel/cpu/cacheinfo.c:877
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cache_amd_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048770)
Location: arch/x86/kernel/cpu/cacheinfo.c:877
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
```
**Symbols:**

```
ffffffff81048770-ffffffff81048919: __cache_amd_cpumap_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cache_amd_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81047c60)
Location: arch/x86/kernel/cpu/cacheinfo.c:877
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
```
**Symbols:**

```
ffffffff81047c60-ffffffff81047e09: __cache_amd_cpumap_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cache_amd_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810491e0)
Location: arch/x86/kernel/cpu/cacheinfo.c:877
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
**Symbols:**

```
ffffffff810491e0-ffffffff8104937d: __cache_amd_cpumap_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cache_amd_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104fba0)
Location: arch/x86/kernel/cpu/cacheinfo.c:877
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
```
**Symbols:**

```
ffffffff8104fba0-ffffffff8104fe14: __cache_amd_cpumap_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __cache_amd_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105ac00)
Location: arch/x86/kernel/cpu/cacheinfo.c:878
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
```
**Symbols:**

```
ffffffff8105ac00-ffffffff8105ae83: __cache_amd_cpumap_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __cache_amd_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81069270)
Location: arch/x86/kernel/cpu/cacheinfo.c:891
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
```
**Symbols:**

```
ffffffff81069270-ffffffff81069527: __cache_amd_cpumap_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __cache_amd_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a8b0)
Location: arch/x86/kernel/cpu/cacheinfo.c:890
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
```
**Symbols:**

```
ffffffff8106a8b0-ffffffff8106ab67: __cache_amd_cpumap_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __cache_amd_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81071cb0)
Location: arch/x86/kernel/cpu/cacheinfo.c:892
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
```
**Symbols:**

```
ffffffff81071cb0-ffffffff81071f64: __cache_amd_cpumap_setup (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045119)
Location: arch/x86/kernel/cpu/cacheinfo.c:877
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034629)
Location: arch/x86/kernel/cpu/cacheinfo.c:877
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044f59)
Location: arch/x86/kernel/cpu/cacheinfo.c:877
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81046359)
Location: arch/x86/kernel/cpu/cacheinfo.c:877
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
