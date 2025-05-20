# Function: <code>e820_end_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int e820_end_pfn(long unsigned int limit_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f67798)
Location: arch/x86/kernel/e820.c:757
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_end_of_ram_pfn
  - arch/x86/kernel/e820.c:e820_end_of_low_ram_pfn
```
**Symbols:**

```
ffffffff81f67798-ffffffff81f67825: e820_end_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int e820_end_pfn(long unsigned int limit_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f8f63c)
Location: arch/x86/kernel/e820.c:757
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820_end_of_ram_pfn
```
**Symbols:**

```
ffffffff81f8f63c-ffffffff81f8f6cc: e820_end_pfn (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff81fcac2b)
Location: arch/x86/kernel/e820.c:786
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820_end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820_end_of_ram_pfn
```
**Symbols:**

```
ffffffff81fcac2b-ffffffff81fcacaa: e820_end_pfn.constprop.3 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff820ab3db)
Location: arch/x86/kernel/e820.c:783
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff820ab3db-ffffffff820ab455: e820_end_pfn.constprop.3 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff826b1b80)
Location: arch/x86/kernel/e820.c:803
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff826b1b80-ffffffff826b1bfa: e820_end_pfn.constprop.3 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff826db258)
Location: arch/x86/kernel/e820.c:805
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff826db258-ffffffff826db2d1: e820_end_pfn.constprop.3 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff8289163f)
Location: arch/x86/kernel/e820.c:804
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff8289163f-ffffffff828916b8: e820_end_pfn.constprop.3 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff828a8bab)
Location: arch/x86/kernel/e820.c:815
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff828a8bab-ffffffff828a8c30: e820_end_pfn.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff828abc0f)
Location: arch/x86/kernel/e820.c:815
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff828abc0f-ffffffff828abc94: e820_end_pfn.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff82cd0f4d)
Location: arch/x86/kernel/e820.c:816
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff82cd0f4d-ffffffff82cd0ff5: e820_end_pfn.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff82fbcd8d)
Location: arch/x86/kernel/e820.c:830
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff82fbcd8d-ffffffff82fbce35: e820_end_pfn.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff831c74a1)
Location: arch/x86/kernel/e820.c:830
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff831c74a1-ffffffff831c7546: e820_end_pfn.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff832a8399)
Location: arch/x86/kernel/e820.c:830
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff832a8399-ffffffff832a843a: e820_end_pfn.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff83457809)
Location: arch/x86/kernel/e820.c:830
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff83457809-ffffffff834578b7: e820_end_pfn.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff83e75e90)
Location: arch/x86/kernel/e820.c:830
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff83e75e90-ffffffff83e75f59: e820_end_pfn.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff83697990)
Location: arch/x86/kernel/e820.c:830
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff83697990-ffffffff83697a8f: e820_end_pfn.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff838c7710)
Location: arch/x86/kernel/e820.c:830
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff838c7710-ffffffff838c780f: e820_end_pfn.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff82899c21)
Location: arch/x86/kernel/e820.c:815
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff82899c21-ffffffff82899ca6: e820_end_pfn.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff82891edf)
Location: arch/x86/kernel/e820.c:815
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff82891edf-ffffffff82891f64: e820_end_pfn.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff828acc01)
Location: arch/x86/kernel/e820.c:815
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff828acc01-ffffffff828acc86: e820_end_pfn.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/e820.c (ffffffff828acc1f)
Location: arch/x86/kernel/e820.c:815
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
**Symbols:**

```
ffffffff828acc1f-ffffffff828acca4: e820_end_pfn.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
