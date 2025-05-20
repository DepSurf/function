# Function: <code>mod_lruvec_state</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c93e5)
Location: include/linux/memcontrol.h:584
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffffffff811ee706)
Location: include/linux/memcontrol.h:584
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811de1f8)
Location: include/linux/memcontrol.h:587
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffffffff81204b76)
Location: include/linux/memcontrol.h:587
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811ff82d)
Location: include/linux/memcontrol.h:639
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffffffff81225939)
Location: include/linux/memcontrol.h:639
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812120f0)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffffffff81238f08)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81221a49)
Location: include/linux/memcontrol.h:673
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffffffff8124a0f4)
Location: include/linux/memcontrol.h:673
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff812959a7)
Location: include/linux/memcontrol.h:673
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122f4f9)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffffffff81258544)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff812a5787)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8125c5e2)
Location: include/linux/memcontrol.h:687
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffffffff81286c48)
Location: include/linux/memcontrol.h:687
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff812da3a8)
Location: include/linux/memcontrol.h:687
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8126698e)
Location: include/linux/vmstat.h:458
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffffffff81290ee7)
Location: include/linux/vmstat.h:458
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
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
In mm/workingset.c (ffffffff81296250)
Location: include/linux/vmstat.h:464
Inline: True
Direct callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81296250-ffffffff81296288: mod_lruvec_state.constprop.0 (STB_LOCAL)
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
In mm/workingset.c (ffffffff812d69e0)
Location: include/linux/vmstat.h:477
Inline: True
Direct callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff812d69e0-ffffffff812d6a18: mod_lruvec_state.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mod_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81335bf0)
Location: include/linux/vmstat.h:549
Inline: False
Direct callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81335bf0-ffffffff81335c26: mod_lruvec_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mod_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff813ac9c0)
Location: include/linux/vmstat.h:543
Inline: False
Direct callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_refault
```
**Symbols:**

```
ffffffff813ac9c0-ffffffff813aca13: mod_lruvec_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mod_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff813e0d60)
Location: include/linux/vmstat.h:549
Inline: False
Direct callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_refault
```
**Symbols:**

```
ffffffff813e0d60-ffffffff813e0db3: mod_lruvec_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mod_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff8140b630)
Location: include/linux/vmstat.h:549
Inline: False
Direct callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_refault
```
**Symbols:**

```
ffffffff8140b630-ffffffff8140b683: mod_lruvec_state (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102be990)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffff8000102f0330)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffff8000103465d4)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04ea8a8)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (c0513a54)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (c054b1f4)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c000000000377690)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (c0000000003b4d34)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (c000000000424574)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001e1068)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffffffe000203d4e)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffe0002394a4)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81227b49)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffffffff81250b94)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff8129dd67)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121ac99)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffffffff81243b14)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff8128f8f7)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812258e9)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffffffff8124e934)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff8129bb77)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81234be9)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/workingset.c (ffffffff8125e2a9)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff812aba5c)
Location: include/linux/memcontrol.h:710
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
