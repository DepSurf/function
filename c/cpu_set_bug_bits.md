# Function: <code>cpu_set_bug_bits</code>

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
In arch/x86/kernel/cpu/common.c (ffffffff826de2a7)
Location: arch/x86/kernel/cpu/common.c:1000
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff828946ea)
Location: arch/x86/kernel/cpu/common.c:1001
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff828abe69)
Location: arch/x86/kernel/cpu/common.c:1094
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff828aed6a)
Location: arch/x86/kernel/cpu/common.c:1108
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff828aed6a-ffffffff828aeeed: cpu_set_bug_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff82cd3c3a)
Location: arch/x86/kernel/cpu/common.c:1114
Inline: True
```
**Symbols:**

```
ffffffff82cd3c3a-ffffffff82cd3ed7: cpu_set_bug_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff82fbfbc2)
Location: arch/x86/kernel/cpu/common.c:1132
Inline: True
```
**Symbols:**

```
ffffffff82fbfbc2-ffffffff82fbfe5f: cpu_set_bug_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff831ca264)
Location: arch/x86/kernel/cpu/common.c:1133
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff831ca264-ffffffff831ca501: cpu_set_bug_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff832ab687)
Location: arch/x86/kernel/cpu/common.c:1136
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff832ab687-ffffffff832ab924: cpu_set_bug_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8345b776)
Location: arch/x86/kernel/cpu/common.c:1298
Inline: True
```
**Symbols:**

```
ffffffff8345b776-ffffffff8345ba4e: cpu_set_bug_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff83e7bc50)
Location: arch/x86/kernel/cpu/common.c:1321
Inline: True
```
**Symbols:**

```
ffffffff83e7bc50-ffffffff83e7c09b: cpu_set_bug_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8369e310)
Location: arch/x86/kernel/cpu/common.c:1320
Inline: True
```
**Symbols:**

```
ffffffff8369e310-ffffffff8369e7f5: cpu_set_bug_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff838cdf00)
Location: arch/x86/kernel/cpu/common.c:1363
Inline: True
```
**Symbols:**

```
ffffffff838cdf00-ffffffff838ce489: cpu_set_bug_bits.constprop.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8289cd89)
Location: arch/x86/kernel/cpu/common.c:1108
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff8289cd89-ffffffff8289cf0c: cpu_set_bug_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff82894f1c)
Location: arch/x86/kernel/cpu/common.c:1108
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff82894f1c-ffffffff828950a4: cpu_set_bug_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff828afd4c)
Location: arch/x86/kernel/cpu/common.c:1108
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff828afd4c-ffffffff828afecf: cpu_set_bug_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff828afd7a)
Location: arch/x86/kernel/cpu/common.c:1108
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff828afd7a-ffffffff828afefd: cpu_set_bug_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
