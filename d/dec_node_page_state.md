# Function: <code>dec_node_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c6780)
Location: mm/vmstat.c:517
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:soft_offline_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff811c6780-ffffffff811c680e: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d5400)
Location: mm/vmstat.c:517
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/memory-failure.c:soft_offline_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff811d5400-ffffffff811d548e: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811de280)
Location: mm/vmstat.c:517
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/khugepaged.c:release_pte_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff811de280-ffffffff811de30e: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f3d10)
Location: mm/vmstat.c:592
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/khugepaged.c:release_pte_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff811f3d10-ffffffff811f3d9e: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81215100)
Location: mm/vmstat.c:592
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/khugepaged.c:release_pte_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff81215100-ffffffff8121518a: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81227fe0)
Location: mm/vmstat.c:592
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/khugepaged.c:release_pte_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff81227fe0-ffffffff8122806a: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81237c50)
Location: mm/vmstat.c:593
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/khugepaged.c:release_pte_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff81237c50-ffffffff81237cda: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81245f00)
Location: mm/vmstat.c:593
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/khugepaged.c:release_pte_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff81245f00-ffffffff81245f8a: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81274f20)
Location: mm/vmstat.c:593
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - fs/fuse/file.c:fuse_writepage_add
```
**Symbols:**

```
ffffffff81274f20-ffffffff81274fb0: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81280030)
Location: mm/vmstat.c:607
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - fs/fuse/file.c:fuse_writepage_add
```
**Symbols:**

```
ffffffff81280030-ffffffff812800c4: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81284ab0)
Location: mm/vmstat.c:619
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - fs/fuse/file.c:fuse_writepage_add
```
**Symbols:**

```
ffffffff81284ab0-ffffffff81284b3e: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c35f0)
Location: mm/vmstat.c:665
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff812c35f0-ffffffff812c369d: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81320990)
Location: mm/vmstat.c:694
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff81320990-ffffffff81320a6b: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81393ff0)
Location: mm/vmstat.c:681
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff81393ff0-ffffffff813940e2: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c7270)
Location: mm/vmstat.c:682
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff813c7270-ffffffff813c7362: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f1500)
Location: mm/vmstat.c:683
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff813f1500-ffffffff813f15ec: dec_node_page_state (STB_GLOBAL)
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
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102db388)
Location: mm/vmstat.c:593
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/khugepaged.c:release_pte_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffff8000102db388-ffff8000102db4d0: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c0502400)
Location: mm/vmstat.c:668
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
c0502400-c0502430: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039c170)
Location: mm/vmstat.c:668
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/khugepaged.c:release_pte_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
c00000000039c170-c00000000039c1d4: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f55c2)
Location: mm/vmstat.c:668
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffe0001f55c2-ffffffe0001f5602: dec_node_page_state (STB_GLOBAL)
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
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123e550)
Location: mm/vmstat.c:593
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/khugepaged.c:release_pte_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff8123e550-ffffffff8123e5da: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81231550)
Location: mm/vmstat.c:593
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/khugepaged.c:release_pte_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff81231550-ffffffff812315da: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123c2f0)
Location: mm/vmstat.c:593
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/khugepaged.c:release_pte_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff8123c2f0-ffffffff8123c37a: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124ba50)
Location: mm/vmstat.c:593
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/migrate.c:migrate_misplaced_page
  - mm/khugepaged.c:release_pte_page
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff8124ba50-ffffffff8124bada: dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
