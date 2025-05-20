# Function: <code>memblock_merge_regions</code>

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
In mm/memblock.c (ffffffff8181d982)
Location: mm/memblock.c:454
Inline: True
Direct callers:
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_set_node
```
**Symbols:**

```
ffffffff8181d982-ffffffff8181da0d: memblock_merge_regions.isra.12 (STB_LOCAL)
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
In mm/memblock.c (ffffffff81897dae)
Location: mm/memblock.c:450
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81897dae-ffffffff81897e39: memblock_merge_regions.isra.13 (STB_LOCAL)
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
In mm/memblock.c (ffffffff818cc44d)
Location: mm/memblock.c:450
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff818cc44d-ffffffff818cc4d8: memblock_merge_regions.isra.14 (STB_LOCAL)
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
In mm/memblock.c (ffffffff81903b39)
Location: mm/memblock.c:434
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81903b39-ffffffff81903bc4: memblock_merge_regions.isra.13 (STB_LOCAL)
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
In mm/memblock.c (ffffffff8198db44)
Location: mm/memblock.c:434
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff8198db44-ffffffff8198dbcf: memblock_merge_regions.isra.13 (STB_LOCAL)
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
In mm/memblock.c (ffffffff819ea3f9)
Location: mm/memblock.c:437
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff819ea3f9-ffffffff819ea484: memblock_merge_regions.isra.13 (STB_LOCAL)
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
In mm/memblock.c (ffffffff81a2566f)
Location: mm/memblock.c:514
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81a2566f-ffffffff81a256f8: memblock_merge_regions.isra.15 (STB_LOCAL)
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
In mm/memblock.c (ffffffff81a95db7)
Location: mm/memblock.c:511
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81a95db7-ffffffff81a95e41: memblock_merge_regions.isra.0 (STB_LOCAL)
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
In mm/memblock.c (ffffffff81acd68e)
Location: mm/memblock.c:511
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81acd68e-ffffffff81acd718: memblock_merge_regions.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memblock_merge_regions(struct memblock_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc5f93)
Location: mm/memblock.c:507
Inline: False
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
```
**Symbols:**

```
ffffffff81bc5f93-ffffffff81bc601e: memblock_merge_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memblock_merge_regions(struct memblock_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3eef3)
Location: mm/memblock.c:494
Inline: False
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
```
**Symbols:**

```
ffffffff81c3eef3-ffffffff81c3ef7e: memblock_merge_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memblock_merge_regions(struct memblock_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c30fc2)
Location: mm/memblock.c:494
Inline: False
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
```
**Symbols:**

```
ffffffff81c30fc2-ffffffff81c31050: memblock_merge_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memblock_merge_regions(struct memblock_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d4f8e2)
Location: mm/memblock.c:502
Inline: False
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
```
**Symbols:**

```
ffffffff81d4f8e2-ffffffff81d4f970: memblock_merge_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memblock_merge_regions(struct memblock_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f1f808)
Location: mm/memblock.c:502
Inline: False
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81f1f808-ffffffff81f1f8af: memblock_merge_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memblock_merge_regions(struct memblock_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820c8b80)
Location: mm/memblock.c:506
Inline: False
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff820c8b80-ffffffff820c8c67: memblock_merge_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memblock_merge_regions(struct memblock_type *type, long unsigned int start_rgn, long unsigned int end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214ce00)
Location: mm/memblock.c:507
Inline: False
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff8214ce00-ffffffff8214ced1: memblock_merge_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memblock_merge_regions(struct memblock_type *type, long unsigned int start_rgn, long unsigned int end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8222f910)
Location: mm/memblock.c:513
Inline: False
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff8222f910-ffffffff8222f9e1: memblock_merge_regions (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (ffff80001031b6c8)
Location: mm/memblock.c:511
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffff80001031b6c8-ffff80001031b7c8: memblock_merge_regions.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memblock_merge_regions(struct memblock_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0535410)
Location: mm/memblock.c:511
Inline: False
Direct callers:
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
c0535410-c05354d8: memblock_merge_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (c0000000003eeff0)
Location: mm/memblock.c:511
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
c0000000003eeff0-c0000000003ef11c: memblock_merge_regions.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (ffffffe000047a86)
Location: mm/memblock.c:511
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffe000047a86-ffffffe000047b16: memblock_merge_regions.isra.0 (STB_LOCAL)
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
In mm/memblock.c (ffffffff81a6c4fe)
Location: mm/memblock.c:511
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81a6c4fe-ffffffff81a6c588: memblock_merge_regions.isra.0 (STB_LOCAL)
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
In mm/memblock.c (ffffffff81a28a45)
Location: mm/memblock.c:511
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81a28a45-ffffffff81a28acf: memblock_merge_regions.isra.0 (STB_LOCAL)
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
In mm/memblock.c (ffffffff81ad890e)
Location: mm/memblock.c:511
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81ad890e-ffffffff81ad8998: memblock_merge_regions.isra.0 (STB_LOCAL)
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
In mm/memblock.c (ffffffff81ae4dc4)
Location: mm/memblock.c:511
Inline: True
Direct callers:
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81ae4dc4-ffffffff81ae4e4e: memblock_merge_regions.isra.0 (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int start_rgn</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int end_rgn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
