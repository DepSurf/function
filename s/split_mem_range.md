# Function: <code>split_mem_range</code>

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
In arch/x86/mm/init.c (ffffffff818188a2)
Location: arch/x86/mm/init.c:264
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_memory_mapping
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
In arch/x86/mm/init.c (ffffffff818923ca)
Location: arch/x86/mm/init.c:276
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_memory_mapping
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
In arch/x86/mm/init.c (ffffffff818c6cea)
Location: arch/x86/mm/init.c:276
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_memory_mapping
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
In arch/x86/mm/init.c (ffffffff818fe44a)
Location: arch/x86/mm/init.c:277
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_memory_mapping
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
In arch/x86/mm/init.c (ffffffff8198857a)
Location: arch/x86/mm/init.c:325
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_memory_mapping
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
In arch/x86/mm/init.c (ffffffff819e4f7a)
Location: arch/x86/mm/init.c:327
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_memory_mapping
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
In arch/x86/mm/init.c (ffffffff81a2019a)
Location: arch/x86/mm/init.c:333
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_memory_mapping
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
In arch/x86/mm/init.c (ffffffff81a9392d)
Location: arch/x86/mm/init.c:336
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81a9392d-ffffffff81a93b12: split_mem_range.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init.c (ffffffff81acb20d)
Location: arch/x86/mm/init.c:336
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81acb20d-ffffffff81acb3f2: split_mem_range.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init.c (ffffffff81bc370d)
Location: arch/x86/mm/init.c:369
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81bc370d-ffffffff81bc38fa: split_mem_range.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init.c (ffffffff81c3c63d)
Location: arch/x86/mm/init.c:370
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81c3c63d-ffffffff81c3c82a: split_mem_range.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init.c (ffffffff81c2eadd)
Location: arch/x86/mm/init.c:379
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81c2eadd-ffffffff81c2eccc: split_mem_range.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init.c (ffffffff81d4d1e1)
Location: arch/x86/mm/init.c:377
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81d4d1e1-ffffffff81d4d3cd: split_mem_range.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init.c (ffffffff81f1ceb3)
Location: arch/x86/mm/init.c:386
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81f1ceb3-ffffffff81f1d0aa: split_mem_range.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init.c (ffffffff820c4f60)
Location: arch/x86/mm/init.c:387
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff820c4f60-ffffffff820c52ba: split_mem_range.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init.c (ffffffff82148fd0)
Location: arch/x86/mm/init.c:412
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff82148fd0-ffffffff8214931c: split_mem_range.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init.c (ffffffff8222ba90)
Location: arch/x86/mm/init.c:402
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff8222ba90-ffffffff8222bddc: split_mem_range.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init.c (ffffffff81a6a07d)
Location: arch/x86/mm/init.c:336
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81a6a07d-ffffffff81a6a262: split_mem_range.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init.c (ffffffff81a2654d)
Location: arch/x86/mm/init.c:336
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81a2654d-ffffffff81a26732: split_mem_range.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init.c (ffffffff81ad648d)
Location: arch/x86/mm/init.c:336
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81ad648d-ffffffff81ad6672: split_mem_range.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init.c (ffffffff81ae294d)
Location: arch/x86/mm/init.c:336
Inline: True
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81ae294d-ffffffff81ae2b32: split_mem_range.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
