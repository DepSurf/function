# Function: <code>__vmalloc_area_node</code>

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
In mm/vmalloc.c (ffffffff811cf0d3)
Location: mm/vmalloc.c:1579
Inline: True
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
In mm/vmalloc.c (ffffffff811ec263)
Location: mm/vmalloc.c:1601
Inline: True
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
In mm/vmalloc.c (ffffffff811fd503)
Location: mm/vmalloc.c:1616
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
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
In mm/vmalloc.c (ffffffff812081cb)
Location: mm/vmalloc.c:1668
Inline: True
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
In mm/vmalloc.c (ffffffff812212a7)
Location: mm/vmalloc.c:1666
Inline: True
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
In mm/vmalloc.c (ffffffff81243158)
Location: mm/vmalloc.c:1653
Inline: True
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
In mm/vmalloc.c (ffffffff81257868)
Location: mm/vmalloc.c:1659
Inline: True
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
In mm/vmalloc.c (ffffffff8126a5b8)
Location: mm/vmalloc.c:2393
Inline: True
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
In mm/vmalloc.c (ffffffff812794c8)
Location: mm/vmalloc.c:2399
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__vmalloc_area_node(struct vm_struct *area, gfp_t gfp_mask, pgprot_t prot, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ac2f0)
Location: mm/vmalloc.c:2444
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
**Symbols:**

```
ffffffff812ac2f0-ffffffff812ac52d: __vmalloc_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__vmalloc_area_node(struct vm_struct *area, gfp_t gfp_mask, pgprot_t prot, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b7880)
Location: mm/vmalloc.c:2478
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
**Symbols:**

```
ffffffff812b7880-ffffffff812b7a5e: __vmalloc_area_node (STB_LOCAL)
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
In mm/vmalloc.c (ffffffff812bd240)
Location: mm/vmalloc.c:2762
Inline: True
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
**Symbols:**

```
ffffffff812bd240-ffffffff812bd466: __vmalloc_area_node.constprop.0 (STB_LOCAL)
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
In mm/vmalloc.c (ffffffff812ff9b0)
Location: mm/vmalloc.c:2886
Inline: True
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
**Symbols:**

```
ffffffff812ff9b0-ffffffff812ffc2a: __vmalloc_area_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__vmalloc_area_node(struct vm_struct *area, gfp_t gfp_mask, pgprot_t prot, unsigned int page_shift, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81366aa0)
Location: mm/vmalloc.c:2958
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
**Symbols:**

```
ffffffff81366aa0-ffffffff81366e3c: __vmalloc_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__vmalloc_area_node(struct vm_struct *area, gfp_t gfp_mask, pgprot_t prot, unsigned int page_shift, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:3020
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
**Symbols:**

```
ffffffff813e2750-ffffffff813e2ccb: __vmalloc_area_node (STB_LOCAL)
ffffffff82064ccd-ffffffff82064d0d: __vmalloc_area_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__vmalloc_area_node(struct vm_struct *area, gfp_t gfp_mask, pgprot_t prot, unsigned int page_shift, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:3102
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
**Symbols:**

```
ffffffff81417300-ffffffff8141792c: __vmalloc_area_node (STB_LOCAL)
ffffffff820e446c-ffffffff820e44a2: __vmalloc_area_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__vmalloc_area_node(struct vm_struct *area, gfp_t gfp_mask, pgprot_t prot, unsigned int page_shift, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:3102
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
**Symbols:**

```
ffffffff81443e10-ffffffff81444474: __vmalloc_area_node (STB_LOCAL)
ffffffff821c10a0-ffffffff821c10d6: __vmalloc_area_node.cold (STB_LOCAL)
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
In mm/vmalloc.c (ffff80001030ff44)
Location: mm/vmalloc.c:2399
Inline: True
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
In mm/vmalloc.c (c052c3e4)
Location: mm/vmalloc.c:2399
Inline: True
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
In mm/vmalloc.c (c0000000003e1218)
Location: mm/vmalloc.c:2399
Inline: True
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
In mm/vmalloc.c (ffffffe000218436)
Location: mm/vmalloc.c:2399
Inline: True
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
In mm/vmalloc.c (ffffffff81271b18)
Location: mm/vmalloc.c:2399
Inline: True
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
In mm/vmalloc.c (ffffffff81263a88)
Location: mm/vmalloc.c:2399
Inline: True
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
In mm/vmalloc.c (ffffffff8126f8b8)
Location: mm/vmalloc.c:2399
Inline: True
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
In mm/vmalloc.c (ffffffff8127f2c8)
Location: mm/vmalloc.c:2399
Inline: True
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
