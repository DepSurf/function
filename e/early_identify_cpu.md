# Function: <code>early_identify_cpu</code>

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
In arch/x86/kernel/cpu/common.c (ffffffff81f6a8a0)
Location: arch/x86/kernel/cpu/common.c:723
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff81f92b61)
Location: arch/x86/kernel/cpu/common.c:787
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff81fcde33)
Location: arch/x86/kernel/cpu/common.c:791
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff820ae482)
Location: arch/x86/kernel/cpu/common.c:851
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff826b49b5)
Location: arch/x86/kernel/cpu/common.c:947
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff826de1d5)
Location: arch/x86/kernel/cpu/common.c:1042
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
In arch/x86/kernel/cpu/common.c (ffffffff82894618)
Location: arch/x86/kernel/cpu/common.c:1064
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff828abd92)
Location: arch/x86/kernel/cpu/common.c:1165
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff828abd92-ffffffff828abfc8: early_identify_cpu.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff828aef95)
Location: arch/x86/kernel/cpu/common.c:1195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff82cd3ed7)
Location: arch/x86/kernel/cpu/common.c:1215
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff82cd3ed7-ffffffff82cd4016: early_identify_cpu.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff82fbfe5f)
Location: arch/x86/kernel/cpu/common.c:1286
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff82fbfe5f-ffffffff82fbffa3: early_identify_cpu.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff831ca573)
Location: arch/x86/kernel/cpu/common.c:1287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff832ab9af)
Location: arch/x86/kernel/cpu/common.c:1290
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff8345ba4e)
Location: arch/x86/kernel/cpu/common.c:1523
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff8345ba4e-ffffffff8345bb81: early_identify_cpu.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff83e7c190)
Location: arch/x86/kernel/cpu/common.c:1549
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff83e7c190-ffffffff83e7c2d2: early_identify_cpu.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff8369e8a0)
Location: arch/x86/kernel/cpu/common.c:1562
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff8369e8a0-ffffffff8369e9cf: early_identify_cpu.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff838ce680)
Location: arch/x86/kernel/cpu/common.c:1618
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff838ce680-ffffffff838ce787: early_identify_cpu.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff8289cfb4)
Location: arch/x86/kernel/cpu/common.c:1195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff8289514c)
Location: arch/x86/kernel/cpu/common.c:1195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff828aff77)
Location: arch/x86/kernel/cpu/common.c:1195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff828affa5)
Location: arch/x86/kernel/cpu/common.c:1195
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
</details>
</li>
</ul>

## Differences
