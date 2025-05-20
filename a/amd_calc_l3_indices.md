# Function: <code>amd_calc_l3_indices</code>

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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103eec2)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:299
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103eced)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:299
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e66a)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:300
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103c63a)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f24a)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:302
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104083a)
Location: arch/x86/kernel/cpu/cacheinfo.c:304
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81041d25)
Location: arch/x86/kernel/cpu/cacheinfo.c:305
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810441b5)
Location: arch/x86/kernel/cpu/cacheinfo.c:306
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044905)
Location: arch/x86/kernel/cpu/cacheinfo.c:306
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void amd_calc_l3_indices(struct amd_northbridge *nb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810480c0)
Location: arch/x86/kernel/cpu/cacheinfo.c:306
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff810480c0-ffffffff810481ad: amd_calc_l3_indices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void amd_calc_l3_indices(struct amd_northbridge *nb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81047570)
Location: arch/x86/kernel/cpu/cacheinfo.c:306
Inline: False
```
**Symbols:**

```
ffffffff81047570-ffffffff8104765d: amd_calc_l3_indices (STB_LOCAL)
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048f66)
Location: arch/x86/kernel/cpu/cacheinfo.c:306
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104f91a)
Location: arch/x86/kernel/cpu/cacheinfo.c:306
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105b108)
Location: arch/x86/kernel/cpu/cacheinfo.c:306
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81068a88)
Location: arch/x86/kernel/cpu/cacheinfo.c:319
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a398)
Location: arch/x86/kernel/cpu/cacheinfo.c:321
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81071867)
Location: arch/x86/kernel/cpu/cacheinfo.c:330
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044a85)
Location: arch/x86/kernel/cpu/cacheinfo.c:306
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034005)
Location: arch/x86/kernel/cpu/cacheinfo.c:306
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810448c5)
Location: arch/x86/kernel/cpu/cacheinfo.c:306
Inline: True
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045cc5)
Location: arch/x86/kernel/cpu/cacheinfo.c:306
Inline: True
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
</ul>
