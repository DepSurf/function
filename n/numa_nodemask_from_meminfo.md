# Function: <code>numa_nodemask_from_meminfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81f782ba)
Location: arch/x86/mm/numa.c:321
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_set_distance
  - arch/x86/mm/numa.c:numa_init
```
**Symbols:**

```
ffffffff81f782ba-ffffffff81f782ef: numa_nodemask_from_meminfo.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81fa0a76)
Location: arch/x86/mm/numa.c:320
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_set_distance
```
**Symbols:**

```
ffffffff81fa0a76-ffffffff81fa0aab: numa_nodemask_from_meminfo.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81fdc105)
Location: arch/x86/mm/numa.c:320
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff81fdc105-ffffffff81fdc13a: numa_nodemask_from_meminfo.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff820bd10b)
Location: arch/x86/mm/numa.c:320
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff820bd10b-ffffffff820bd145: numa_nodemask_from_meminfo.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff826c3f1f)
Location: arch/x86/mm/numa.c:320
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff826c3f1f-ffffffff826c3f84: numa_nodemask_from_meminfo.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff826ee1ba)
Location: arch/x86/mm/numa.c:320
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff826ee1ba-ffffffff826ee21f: numa_nodemask_from_meminfo.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff828a4ea8)
Location: arch/x86/mm/numa.c:319
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff828a4ea8-ffffffff828a4f0d: numa_nodemask_from_meminfo.constprop.5 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff828bd460)
Location: arch/x86/mm/numa.c:316
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff828bd460-ffffffff828bd4a7: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff828c38ea)
Location: arch/x86/mm/numa.c:316
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff828c38ea-ffffffff828c3931: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff82ce6e21)
Location: arch/x86/mm/numa.c:331
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff82ce6e21-ffffffff82ce6e68: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff82fd47a0)
Location: arch/x86/mm/numa.c:329
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff82fd47a0-ffffffff82fd47e7: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff831df27a)
Location: arch/x86/mm/numa.c:335
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff831df27a-ffffffff831df2c1: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff832c27cf)
Location: arch/x86/mm/numa.c:335
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff832c27cf-ffffffff832c2816: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff83474ee5)
Location: arch/x86/mm/numa.c:335
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff83474ee5-ffffffff83474f2b: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff83e9d560)
Location: arch/x86/mm/numa.c:335
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff83e9d560-ffffffff83e9d5a7: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff836c10f0)
Location: arch/x86/mm/numa.c:335
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff836c10f0-ffffffff836c11b6: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff838f1c60)
Location: arch/x86/mm/numa.c:337
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff838f1c60-ffffffff838f1d26: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff828ae8c0)
Location: arch/x86/mm/numa.c:316
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff828ae8c0-ffffffff828ae907: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff828a6ab2)
Location: arch/x86/mm/numa.c:316
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff828a6ab2-ffffffff828a6af9: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff828c17bf)
Location: arch/x86/mm/numa.c:316
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff828c17bf-ffffffff828c1806: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff828c490a)
Location: arch/x86/mm/numa.c:316
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
**Symbols:**

```
ffffffff828c490a-ffffffff828c4951: numa_nodemask_from_meminfo.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
