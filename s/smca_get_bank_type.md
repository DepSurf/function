# Function: <code>smca_get_bank_type</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81051162)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_mce_is_memory_error
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104e5d2)
Location: arch/x86/kernel/cpu/mce/amd.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051657)
Location: arch/x86/kernel/cpu/mce/amd.c:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051fb7)
Location: arch/x86/kernel/cpu/mce/amd.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056b57)
Location: arch/x86/kernel/cpu/mce/amd.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055a67)
Location: arch/x86/kernel/cpu/mce/amd.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810572e7)
Location: arch/x86/kernel/cpu/mce/amd.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810600cd)
Location: arch/x86/kernel/cpu/mce/amd.c:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
enum smca_bank_types smca_get_bank_type(unsigned int cpu, unsigned int bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106c9ca)
Location: arch/x86/kernel/cpu/mce/amd.c:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
```
**Symbols:**

```
ffffffff8106a890-ffffffff8106a929: smca_get_bank_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
enum smca_bank_types smca_get_bank_type(unsigned int cpu, unsigned int bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107ca5a)
Location: arch/x86/kernel/cpu/mce/amd.c:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
```
**Symbols:**

```
ffffffff8107a720-ffffffff8107a7b9: smca_get_bank_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
enum smca_bank_types smca_get_bank_type(unsigned int cpu, unsigned int bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107ed94)
Location: arch/x86/kernel/cpu/mce/amd.c:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
```
**Symbols:**

```
ffffffff8107c9c0-ffffffff8107ca59: smca_get_bank_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
enum smca_bank_types smca_get_bank_type(unsigned int cpu, unsigned int bank);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810862c3)
Location: arch/x86/kernel/cpu/mce/amd.c:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
```
**Symbols:**

```
ffffffff81083ea0-ffffffff81083f39: smca_get_bank_type (STB_GLOBAL)
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810520b7)
Location: arch/x86/kernel/cpu/mce/amd.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81041aa7)
Location: arch/x86/kernel/cpu/mce/amd.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051f67)
Location: arch/x86/kernel/cpu/mce/amd.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810533a7)
Location: arch/x86/kernel/cpu/mce/amd.c:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_mce_is_memory_error
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:amd_filter_mce
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
