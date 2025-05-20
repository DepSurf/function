# Function: <code>disable_err_thresholding</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 *c, unsigned int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810511c0)
Location: arch/x86/kernel/cpu/mce/amd.c:586
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff810511c0-ffffffff810512fb: disable_err_thresholding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 *c, unsigned int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051b20)
Location: arch/x86/kernel/cpu/mce/amd.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff81051b20-ffffffff81051c5b: disable_err_thresholding (STB_GLOBAL)
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105693d)
Location: arch/x86/kernel/cpu/mce/amd.c:602
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105584d)
Location: arch/x86/kernel/cpu/mce/amd.c:602
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105704d)
Location: arch/x86/kernel/cpu/mce/amd.c:602
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105fe0d)
Location: arch/x86/kernel/cpu/mce/amd.c:615
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106c677)
Location: arch/x86/kernel/cpu/mce/amd.c:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107c6d7)
Location: arch/x86/kernel/cpu/mce/amd.c:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107ea27)
Location: arch/x86/kernel/cpu/mce/amd.c:640
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81085f37)
Location: arch/x86/kernel/cpu/mce/amd.c:632
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
<summary>In <code>aws</code>: ✅</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 *c, unsigned int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051c20)
Location: arch/x86/kernel/cpu/mce/amd.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff81051c20-ffffffff81051d5b: disable_err_thresholding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 *c, unsigned int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810414c0)
Location: arch/x86/kernel/cpu/mce/amd.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff810414c0-ffffffff81041629: disable_err_thresholding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 *c, unsigned int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051ad0)
Location: arch/x86/kernel/cpu/mce/amd.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff81051ad0-ffffffff81051c0b: disable_err_thresholding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void disable_err_thresholding(struct cpuinfo_x86 *c, unsigned int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81052f10)
Location: arch/x86/kernel/cpu/mce/amd.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff81052f10-ffffffff8105304b: disable_err_thresholding (STB_GLOBAL)
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
