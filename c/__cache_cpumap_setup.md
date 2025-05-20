# Function: <code>__cache_cpumap_setup</code>

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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f214)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:859
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
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:859
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
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:860
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
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:861
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f58e)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:865
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81040c99)
Location: arch/x86/kernel/cpu/cacheinfo.c:907
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810422ab)
Location: arch/x86/kernel/cpu/cacheinfo.c:934
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044714)
Location: arch/x86/kernel/cpu/cacheinfo.c:934
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044e64)
Location: arch/x86/kernel/cpu/cacheinfo.c:934
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
void __cache_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048b70)
Location: arch/x86/kernel/cpu/cacheinfo.c:934
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
**Symbols:**

```
ffffffff81048b70-ffffffff81048cb9: __cache_cpumap_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __cache_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048060)
Location: arch/x86/kernel/cpu/cacheinfo.c:934
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
**Symbols:**

```
ffffffff81048060-ffffffff810481a3: __cache_cpumap_setup (STB_LOCAL)
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049c16)
Location: arch/x86/kernel/cpu/cacheinfo.c:934
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __cache_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:934
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
```
**Symbols:**

```
ffffffff810501e0-ffffffff810503ac: __cache_cpumap_setup (STB_LOCAL)
ffffffff81c9a8c2-ffffffff81c9a90b: __cache_cpumap_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __cache_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:935
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
```
**Symbols:**

```
ffffffff8105ae90-ffffffff8105b06f: __cache_cpumap_setup (STB_LOCAL)
ffffffff81e49d28-ffffffff81e49d77: __cache_cpumap_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __cache_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:948
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
```
**Symbols:**

```
ffffffff81069540-ffffffff81069739: __cache_cpumap_setup (STB_LOCAL)
ffffffff8205276b-ffffffff820527bf: __cache_cpumap_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __cache_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:947
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
```
**Symbols:**

```
ffffffff8106ab80-ffffffff8106ad76: __cache_cpumap_setup (STB_LOCAL)
ffffffff820d0c24-ffffffff820d0c66: __cache_cpumap_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __cache_cpumap_setup(unsigned int cpu, int index, struct _cpuid4_info_regs *base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:949
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves
```
**Symbols:**

```
ffffffff81071f80-ffffffff81072172: __cache_cpumap_setup (STB_LOCAL)
ffffffff821ab74d-ffffffff821ab78d: __cache_cpumap_setup.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044fe4)
Location: arch/x86/kernel/cpu/cacheinfo.c:934
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810344f4)
Location: arch/x86/kernel/cpu/cacheinfo.c:934
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044e24)
Location: arch/x86/kernel/cpu/cacheinfo.c:934
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81046224)
Location: arch/x86/kernel/cpu/cacheinfo.c:934
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
