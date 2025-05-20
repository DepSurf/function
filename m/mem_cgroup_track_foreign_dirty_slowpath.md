# Function: <code>mem_cgroup_track_foreign_dirty_slowpath</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7910)
Location: mm/memcontrol.c:4503
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff812c7910-ffffffff812c7a5a: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fd3a0)
Location: mm/memcontrol.c:4383
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff812fd3a0-ffffffff812fd4ee: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309820)
Location: mm/memcontrol.c:4648
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff81309820-ffffffff81309960: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130fe60)
Location: mm/memcontrol.c:4416
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff8130fe60-ffffffff8130ffa1: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135b100)
Location: mm/memcontrol.c:4583
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff8135b100-ffffffff8135b2df: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct folio *folio, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d47b0)
Location: mm/memcontrol.c:4534
Inline: False
Direct callers:
  - mm/page-writeback.c:folio_account_dirtied
```
**Symbols:**

```
ffffffff813d47b0-ffffffff813d49d8: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct folio *folio, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145a1e0)
Location: mm/memcontrol.c:4644
Inline: False
Direct callers:
  - mm/page-writeback.c:folio_account_dirtied
```
**Symbols:**

```
ffffffff8145a1e0-ffffffff8145a408: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct folio *folio, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148fe40)
Location: mm/memcontrol.c:4668
Inline: False
Direct callers:
  - mm/page-writeback.c:folio_account_dirtied
```
**Symbols:**

```
ffffffff8148fe40-ffffffff81490063: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct folio *folio, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bf650)
Location: mm/memcontrol.c:4865
Inline: False
Direct callers:
  - mm/page-writeback.c:folio_account_dirtied
```
**Symbols:**

```
ffffffff814bf650-ffffffff814bf873: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
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
void mem_cgroup_track_foreign_dirty_slowpath(struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036a738)
Location: mm/memcontrol.c:4503
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffff80001036a738-ffff80001036a8cc: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055bc5c)
Location: mm/memcontrol.c:4503
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
c055bc5c-c055be68: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000459980)
Location: mm/memcontrol.c:4503
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
c000000000459980-c000000000459bb4: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000247f88)
Location: mm/memcontrol.c:4503
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffe000247f88-ffffffe0002480e2: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
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
void mem_cgroup_track_foreign_dirty_slowpath(struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bfef0)
Location: mm/memcontrol.c:4503
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff812bfef0-ffffffff812c003a: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b0fc0)
Location: mm/memcontrol.c:4503
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff812b0fc0-ffffffff812b110a: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bdd00)
Location: mm/memcontrol.c:4503
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff812bdd00-ffffffff812bde4a: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_track_foreign_dirty_slowpath(struct page *page, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ce660)
Location: mm/memcontrol.c:4503
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff812ce660-ffffffff812ce7c7: mem_cgroup_track_foreign_dirty_slowpath (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
