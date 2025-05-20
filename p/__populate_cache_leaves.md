# Function: <code>__populate_cache_leaves</code>

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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f1ce)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:923
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
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:923
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e96e)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:942
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103c93e)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:943
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f54b)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:947
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81040b50)
Location: arch/x86/kernel/cpu/cacheinfo.c:989
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81042170)
Location: arch/x86/kernel/cpu/cacheinfo.c:1017
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __populate_cache_leaves(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810445b0)
Location: arch/x86/kernel/cpu/cacheinfo.c:1017
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
**Symbols:**

```
ffffffff810445b0-ffffffff810449df: __populate_cache_leaves (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __populate_cache_leaves(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044d00)
Location: arch/x86/kernel/cpu/cacheinfo.c:1017
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
**Symbols:**

```
ffffffff81044d00-ffffffff8104512f: __populate_cache_leaves (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __populate_cache_leaves(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048e40)
Location: arch/x86/kernel/cpu/cacheinfo.c:1017
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
**Symbols:**

```
ffffffff81048e40-ffffffff81048fde: __populate_cache_leaves (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __populate_cache_leaves(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048300)
Location: arch/x86/kernel/cpu/cacheinfo.c:1017
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
**Symbols:**

```
ffffffff81048300-ffffffff81048494: __populate_cache_leaves (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __populate_cache_leaves(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049ac0)
Location: arch/x86/kernel/cpu/cacheinfo.c:1017
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
**Symbols:**

```
ffffffff81049ac0-ffffffff81049d64: __populate_cache_leaves (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/cacheinfo.c (ffff80001009b8f8)
Location: arch/arm64/kernel/cacheinfo.c:81
Inline: True
Inline callers:
  - arch/arm64/kernel/cacheinfo.c:_populate_cache_leaves
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
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/cacheinfo.c (ffffffe0000b7596)
Location: arch/riscv/kernel/cacheinfo.c:61
Inline: True
Inline callers:
  - arch/riscv/kernel/cacheinfo.c:_populate_cache_leaves
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __populate_cache_leaves(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044e80)
Location: arch/x86/kernel/cpu/cacheinfo.c:1017
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
**Symbols:**

```
ffffffff81044e80-ffffffff810452af: __populate_cache_leaves (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __populate_cache_leaves(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034390)
Location: arch/x86/kernel/cpu/cacheinfo.c:1017
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
**Symbols:**

```
ffffffff81034390-ffffffff810347bf: __populate_cache_leaves (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __populate_cache_leaves(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044cc0)
Location: arch/x86/kernel/cpu/cacheinfo.c:1017
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
**Symbols:**

```
ffffffff81044cc0-ffffffff810450ef: __populate_cache_leaves (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __populate_cache_leaves(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810460c0)
Location: arch/x86/kernel/cpu/cacheinfo.c:1017
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
**Symbols:**

```
ffffffff810460c0-ffffffff810464ef: __populate_cache_leaves (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
