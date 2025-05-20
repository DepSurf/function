# Function: <code>mem_cgroup_migrate</code>

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
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81224120)
Location: mm/memcontrol.c:5632
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff81224120-ffffffff8122424b: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81236620)
Location: mm/memcontrol.c:5617
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff81236620-ffffffff8123674b: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812420d0)
Location: mm/memcontrol.c:5679
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff812420d0-ffffffff812421fc: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81261ec0)
Location: mm/memcontrol.c:5779
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffff81261ec0-ffffffff81261ff2: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81285ed0)
Location: mm/memcontrol.c:5847
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffff81285ed0-ffffffff81285fff: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129ae30)
Location: mm/memcontrol.c:6178
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_replace_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffff8129ae30-ffffffff8129af5f: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b60e0)
Location: mm/memcontrol.c:6470
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffff812b60e0-ffffffff812b622c: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7fd0)
Location: mm/memcontrol.c:6810
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffff812c7fd0-ffffffff812c811c: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fd880)
Location: mm/memcontrol.c:6670
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_replace_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffff812fd880-ffffffff812fd972: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309ca0)
Location: mm/memcontrol.c:6930
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_replace_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffff81309ca0-ffffffff81309d99: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813104e0)
Location: mm/memcontrol.c:6791
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_replace_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffff813104e0-ffffffff81310605: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135b800)
Location: mm/memcontrol.c:6970
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_replace_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffff8135b800-ffffffff8135b915: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct folio *old, struct folio *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d5030)
Location: mm/memcontrol.c:6953
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_replace_page
  - mm/migrate.c:folio_migrate_flags
```
**Symbols:**

```
ffffffff813d5030-ffffffff813d51c0: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct folio *old, struct folio *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145aaa0)
Location: mm/memcontrol.c:7142
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/migrate.c:folio_migrate_flags
```
**Symbols:**

```
ffffffff8145aaa0-ffffffff8145ac21: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct folio *old, struct folio *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81490700)
Location: mm/memcontrol.c:7210
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/migrate.c:folio_migrate_flags
```
**Symbols:**

```
ffffffff81490700-ffffffff81490881: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct folio *old, struct folio *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814c0170)
Location: mm/memcontrol.c:7588
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_folio
  - mm/migrate.c:folio_migrate_flags
```
**Symbols:**

```
ffffffff814c0170-ffffffff814c01f3: mem_cgroup_migrate (STB_GLOBAL)
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
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036af08)
Location: mm/memcontrol.c:6810
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffff80001036af08-ffff80001036b01c: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055c55c)
Location: mm/memcontrol.c:6810
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
c055c55c-c055c670: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045a560)
Location: mm/memcontrol.c:6810
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
c00000000045a560-c00000000045a748: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000248656)
Location: mm/memcontrol.c:6810
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffe000248656-ffffffe00024874a: mem_cgroup_migrate (STB_GLOBAL)
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
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c05b0)
Location: mm/memcontrol.c:6810
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffff812c05b0-ffffffff812c06fc: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b1680)
Location: mm/memcontrol.c:6810
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffff812b1680-ffffffff812b17b6: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812be3c0)
Location: mm/memcontrol.c:6810
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffff812be3c0-ffffffff812be50c: mem_cgroup_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page *oldpage, struct page *newpage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cedb0)
Location: mm/memcontrol.c:6810
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/migrate.c:migrate_page_states
```
**Symbols:**

```
ffffffff812cedb0-ffffffff812cef12: mem_cgroup_migrate (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *old</code>
</li>
<li>
<b>Param added. </b>
<code>struct folio *new</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *oldpage</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *newpage</code>
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
