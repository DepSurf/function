# Function: <code>mem_cgroup_uncharge_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81200350)
Location: mm/memcontrol.c:5535
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_active_list
```
**Symbols:**

```
ffffffff81200350-ffffffff8120036b: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81224100)
Location: mm/memcontrol.c:5613
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81224100-ffffffff8122411e: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81236600)
Location: mm/memcontrol.c:5598
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81236600-ffffffff8123661e: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812420b0)
Location: mm/memcontrol.c:5660
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812420b0-ffffffff812420cf: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81261e30)
Location: mm/memcontrol.c:5760
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81261e30-ffffffff81261eb8: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81285e40)
Location: mm/memcontrol.c:5828
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81285e40-ffffffff81285ec8: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129ada0)
Location: mm/memcontrol.c:6159
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8129ada0-ffffffff8129ae28: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b6050)
Location: mm/memcontrol.c:6451
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812b6050-ffffffff812b60d9: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7f40)
Location: mm/memcontrol.c:6791
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812c7f40-ffffffff812c7fc9: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fd7e0)
Location: mm/memcontrol.c:6651
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812fd7e0-ffffffff812fd87c: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309c00)
Location: mm/memcontrol.c:6911
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81309c00-ffffffff81309c9c: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81310430)
Location: mm/memcontrol.c:6766
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81310430-ffffffff813104d1: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812ab5ab)
Location: include/linux/memcontrol.h:711
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff812b5d6e)
Location: include/linux/memcontrol.h:711
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81305362)
Location: include/linux/memcontrol.h:712
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff8130efe0)
Location: include/linux/memcontrol.h:712
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8136f5ae)
Location: include/linux/memcontrol.h:694
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff81381338)
Location: include/linux/memcontrol.h:694
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_folio_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a16ce)
Location: include/linux/memcontrol.h:707
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff813b26ec)
Location: include/linux/memcontrol.h:707
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_folio_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813cb34e)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff813dbc7d)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_folio_list
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036ae58)
Location: mm/memcontrol.c:6791
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffff80001036ae58-ffff80001036af08: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055c4a8)
Location: mm/memcontrol.c:6791
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
c055c4a8-c055c55c: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045a450)
Location: mm/memcontrol.c:6791
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
c00000000045a450-c00000000045a55c: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002485d2)
Location: mm/memcontrol.c:6791
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffe0002485d2-ffffffe000248656: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c0520)
Location: mm/memcontrol.c:6791
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812c0520-ffffffff812c05a9: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b15f0)
Location: mm/memcontrol.c:6791
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812b15f0-ffffffff812b1679: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812be330)
Location: mm/memcontrol.c:6791
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812be330-ffffffff812be3b9: mem_cgroup_uncharge_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ced20)
Location: mm/memcontrol.c:6791
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812ced20-ffffffff812ceda9: mem_cgroup_uncharge_list (STB_GLOBAL)
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
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
