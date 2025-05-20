# Function: <code>mmap_base</code>

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
In arch/x86/mm/mmap.c (ffffffff8106f745)
Location: arch/x86/mm/mmap.c:84
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
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
In arch/x86/mm/mmap.c (ffffffff8106f4a4)
Location: arch/x86/mm/mmap.c:84
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
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
In arch/x86/mm/mmap.c (ffffffff810730f9)
Location: arch/x86/mm/mmap.c:84
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
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
In arch/x86/mm/mmap.c (ffffffff8107257a)
Location: arch/x86/mm/mmap.c:91
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_base
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
In arch/x86/mm/mmap.c (ffffffff81077dfa)
Location: arch/x86/mm/mmap.c:93
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_base
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
In arch/x86/mm/mmap.c (ffffffff8107a870)
Location: arch/x86/mm/mmap.c:93
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff8107a870-ffffffff8107a90b: mmap_base.isra.1 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff810811b0)
Location: arch/x86/mm/mmap.c:93
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff810811b0-ffffffff8108124b: mmap_base.isra.1 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff81084e00)
Location: arch/x86/mm/mmap.c:80
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff81084e00-ffffffff81084ea1: mmap_base.isra.0 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff81085af0)
Location: arch/x86/mm/mmap.c:80
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff81085af0-ffffffff81085b91: mmap_base.isra.0 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff81089210)
Location: arch/x86/mm/mmap.c:82
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff81089210-ffffffff810892b1: mmap_base.isra.0 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff810893f0)
Location: arch/x86/mm/mmap.c:82
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff810893f0-ffffffff81089491: mmap_base.isra.0 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff8108a110)
Location: arch/x86/mm/mmap.c:82
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff8108a110-ffffffff8108a1b4: mmap_base.isra.0 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff81099650)
Location: arch/x86/mm/mmap.c:82
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff81099650-ffffffff810996f4: mmap_base.isra.0 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff810ac530)
Location: arch/x86/mm/mmap.c:82
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff810ac530-ffffffff810ac5dd: mmap_base.isra.0 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff810c6560)
Location: arch/x86/mm/mmap.c:82
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff810c6560-ffffffff810c660d: mmap_base.isra.0 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff810c9cf0)
Location: arch/x86/mm/mmap.c:82
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff810c9cf0-ffffffff810c9d9d: mmap_base.isra.0 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff810d2150)
Location: arch/x86/mm/mmap.c:82
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff810d2150-ffffffff810d21fd: mmap_base.isra.0 (STB_LOCAL)
```
</details>
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
In mm/util.c (ffff8000102d8b6c)
Location: mm/util.c:365
Inline: True
Inline callers:
  - mm/util.c:arch_pick_mmap_layout
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ffdbc)
Location: mm/util.c:365
Inline: True
Inline callers:
  - mm/util.c:arch_pick_mmap_layout
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/mmap.c (c00000000008885c)
Location: arch/powerpc/mm/mmap.c:65
Inline: True
Inline callers:
  - arch/powerpc/mm/mmap.c:arch_pick_mmap_layout
  - arch/powerpc/mm/mmap.c:arch_pick_mmap_layout
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f3078)
Location: mm/util.c:365
Inline: True
Inline callers:
  - mm/util.c:arch_pick_mmap_layout
```
</details>
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
In arch/x86/mm/mmap.c (ffffffff81084af0)
Location: arch/x86/mm/mmap.c:80
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff81084af0-ffffffff81084b91: mmap_base.isra.0 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff810737c0)
Location: arch/x86/mm/mmap.c:80
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff810737c0-ffffffff81073861: mmap_base.isra.0 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff81084aa0)
Location: arch/x86/mm/mmap.c:80
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff81084aa0-ffffffff81084b41: mmap_base.isra.0 (STB_LOCAL)
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
In arch/x86/mm/mmap.c (ffffffff81086bf0)
Location: arch/x86/mm/mmap.c:80
Inline: True
Direct callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
**Symbols:**

```
ffffffff81086bf0-ffffffff81086c91: mmap_base.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
