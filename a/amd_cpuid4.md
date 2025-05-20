# Function: <code>amd_cpuid4</code>

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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ef8a)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:224
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103edbc)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:224
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e73a)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:225
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103c6fd)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:226
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f30d)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:227
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810408fd)
Location: arch/x86/kernel/cpu/cacheinfo.c:229
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81041f24)
Location: arch/x86/kernel/cpu/cacheinfo.c:230
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810443b4)
Location: arch/x86/kernel/cpu/cacheinfo.c:230
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044b04)
Location: arch/x86/kernel/cpu/cacheinfo.c:230
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void amd_cpuid4(int leaf, union _cpuid4_leaf_eax *eax, union _cpuid4_leaf_ebx *ebx, union _cpuid4_leaf_ecx *ecx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048920)
Location: arch/x86/kernel/cpu/cacheinfo.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff81048920-ffffffff81048b63: amd_cpuid4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void amd_cpuid4(int leaf, union _cpuid4_leaf_eax *eax, union _cpuid4_leaf_ebx *ebx, union _cpuid4_leaf_ecx *ecx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81047e10)
Location: arch/x86/kernel/cpu/cacheinfo.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff81047e10-ffffffff81048053: amd_cpuid4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void amd_cpuid4(int leaf, union _cpuid4_leaf_eax *eax, union _cpuid4_leaf_ebx *ebx, union _cpuid4_leaf_ecx *ecx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049720)
Location: arch/x86/kernel/cpu/cacheinfo.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff81049720-ffffffff81049964: amd_cpuid4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void amd_cpuid4(int leaf, union _cpuid4_leaf_eax *eax, union _cpuid4_leaf_ebx *ebx, union _cpuid4_leaf_ecx *ecx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810503b0)
Location: arch/x86/kernel/cpu/cacheinfo.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff810503b0-ffffffff81050688: amd_cpuid4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void amd_cpuid4(int leaf, union _cpuid4_leaf_eax *eax, union _cpuid4_leaf_ebx *ebx, union _cpuid4_leaf_ecx *ecx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105b7c0)
Location: arch/x86/kernel/cpu/cacheinfo.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff8105b7c0-ffffffff8105bacd: amd_cpuid4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void amd_cpuid4(int leaf, union _cpuid4_leaf_eax *eax, union _cpuid4_leaf_ebx *ebx, union _cpuid4_leaf_ecx *ecx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81069750)
Location: arch/x86/kernel/cpu/cacheinfo.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff81069750-ffffffff81069a5d: amd_cpuid4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void amd_cpuid4(int leaf, union _cpuid4_leaf_eax *eax, union _cpuid4_leaf_ebx *ebx, union _cpuid4_leaf_ecx *ecx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106b070)
Location: arch/x86/kernel/cpu/cacheinfo.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff8106b070-ffffffff8106b37f: amd_cpuid4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void amd_cpuid4(int leaf, union _cpuid4_leaf_eax *eax, union _cpuid4_leaf_ebx *ebx, union _cpuid4_leaf_ecx *ecx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81072540)
Location: arch/x86/kernel/cpu/cacheinfo.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff81072540-ffffffff8107284f: amd_cpuid4 (STB_LOCAL)
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044c84)
Location: arch/x86/kernel/cpu/cacheinfo.c:230
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810341d4)
Location: arch/x86/kernel/cpu/cacheinfo.c:230
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044ac4)
Location: arch/x86/kernel/cpu/cacheinfo.c:230
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045ec4)
Location: arch/x86/kernel/cpu/cacheinfo.c:230
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
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
