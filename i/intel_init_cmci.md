# Function: <code>intel_init_cmci</code>

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
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff810479bc)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:423
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81047ac2)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:423
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104963e)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:425
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81048fde)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:425
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104ca0e)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f6dd)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104cd9d)
Location: arch/x86/kernel/cpu/mce/intel.c:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fccd)
Location: arch/x86/kernel/cpu/mce/intel.c:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105065d)
Location: arch/x86/kernel/cpu/mce/intel.c:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_init_cmci();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054be0)
Location: arch/x86/kernel/cpu/mce/intel.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_vendor
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81054be0-ffffffff81054c78: intel_init_cmci (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_init_cmci();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81053b20)
Location: arch/x86/kernel/cpu/mce/intel.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_vendor
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81053b20-ffffffff81053bb8: intel_init_cmci (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_init_cmci();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810553f0)
Location: arch/x86/kernel/cpu/mce/intel.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_vendor
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff810553f0-ffffffff81055488: intel_init_cmci (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_init_cmci();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105dd90)
Location: arch/x86/kernel/cpu/mce/intel.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_vendor
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff8105dd90-ffffffff8105de28: intel_init_cmci (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_init_cmci();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a4d0)
Location: arch/x86/kernel/cpu/mce/intel.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff8106a4d0-ffffffff8106a580: intel_init_cmci (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_init_cmci();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107a2f0)
Location: arch/x86/kernel/cpu/mce/intel.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff8107a2f0-ffffffff8107a3a0: intel_init_cmci (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_init_cmci();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c5a0)
Location: arch/x86/kernel/cpu/mce/intel.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff8107c5a0-ffffffff8107c650: intel_init_cmci (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_init_cmci();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81083a90)
Location: arch/x86/kernel/cpu/mce/intel.c:404
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_vendor
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81083a90-ffffffff81083b40: intel_init_cmci (STB_GLOBAL)
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105075d)
Location: arch/x86/kernel/cpu/mce/intel.c:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103fda9)
Location: arch/x86/kernel/cpu/mce/intel.c:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105060d)
Location: arch/x86/kernel/cpu/mce/intel.c:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81051a4d)
Location: arch/x86/kernel/cpu/mce/intel.c:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
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
