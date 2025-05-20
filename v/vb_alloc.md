# Function: <code>vb_alloc</code>

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
In mm/vmalloc.c (ffffffff811ce711)
Location: mm/vmalloc.c:934
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (ffffffff811eb351)
Location: mm/vmalloc.c:958
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (ffffffff811fc5c1)
Location: mm/vmalloc.c:929
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (ffffffff81207295)
Location: mm/vmalloc.c:980
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (ffffffff81220385)
Location: mm/vmalloc.c:978
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (ffffffff81242165)
Location: mm/vmalloc.c:961
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (ffffffff81256895)
Location: mm/vmalloc.c:961
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (ffffffff8126aaf4)
Location: mm/vmalloc.c:1564
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (ffffffff81279a04)
Location: mm/vmalloc.c:1572
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (ffffffff812aa440)
Location: mm/vmalloc.c:1673
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812aa440-ffffffff812aa590: vb_alloc.constprop.0 (STB_LOCAL)
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
In mm/vmalloc.c (ffffffff812b5af0)
Location: mm/vmalloc.c:1662
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812b5af0-ffffffff812b5c5b: vb_alloc.constprop.0 (STB_LOCAL)
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
In mm/vmalloc.c (ffffffff812bb1e0)
Location: mm/vmalloc.c:1932
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812bb1e0-ffffffff812bb34b: vb_alloc.constprop.0 (STB_LOCAL)
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
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1984
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812fd7f0-ffffffff812fd975: vb_alloc.constprop.0 (STB_LOCAL)
ffffffff81cbcf4b-ffffffff81cbcf81: vb_alloc.constprop.0.cold (STB_LOCAL)
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
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2003
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81364760-ffffffff813648f7: vb_alloc.constprop.0 (STB_LOCAL)
ffffffff81e6ebfe-ffffffff81e6ec32: vb_alloc.constprop.0.cold (STB_LOCAL)
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
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2065
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff813e02b0-ffffffff813e0447: vb_alloc.constprop.0 (STB_LOCAL)
ffffffff82064af7-ffffffff82064b2b: vb_alloc.constprop.0.cold (STB_LOCAL)
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
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2161
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81415040-ffffffff8141520e: vb_alloc.constprop.0 (STB_LOCAL)
ffffffff820e4241-ffffffff820e426f: vb_alloc.constprop.0.cold (STB_LOCAL)
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
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2161
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81441b10-ffffffff81441cde: vb_alloc.constprop.0 (STB_LOCAL)
ffffffff821c0e75-ffffffff821c0ea3: vb_alloc.constprop.0.cold (STB_LOCAL)
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
In mm/vmalloc.c (ffff800010310c08)
Location: mm/vmalloc.c:1572
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (c052caa0)
Location: mm/vmalloc.c:1572
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (c0000000003e19ac)
Location: mm/vmalloc.c:1572
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (ffffffe00021893e)
Location: mm/vmalloc.c:1572
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
</details>
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
In mm/vmalloc.c (ffffffff81272054)
Location: mm/vmalloc.c:1572
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (ffffffff81263fc4)
Location: mm/vmalloc.c:1572
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (ffffffff8126fdf4)
Location: mm/vmalloc.c:1572
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
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
In mm/vmalloc.c (ffffffff8127f7e2)
Location: mm/vmalloc.c:1572
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
</details>
</li>
</ul>

## Differences
