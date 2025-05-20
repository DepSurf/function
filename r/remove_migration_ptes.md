# Function: <code>remove_migration_ptes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff811f0790)
Location: mm/migrate.c:189
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff811f0790-ffffffff811f07f5: remove_migration_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812114e0)
Location: mm/migrate.c:279
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812114e0-ffffffff81211550: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812236a0)
Location: mm/migrate.c:279
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812236a0-ffffffff81223710: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8122f050)
Location: mm/migrate.c:265
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff8122f050-ffffffff8122f0c0: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124bd90)
Location: mm/migrate.c:288
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff8124bd90-ffffffff8124be00: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126f870)
Location: mm/migrate.c:289
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff8126f870-ffffffff8126f8e0: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81283f00)
Location: mm/migrate.c:290
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff81283f00-ffffffff81283f70: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129f0c0)
Location: mm/migrate.c:288
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff8129f0c0-ffffffff8129f130: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812afab0)
Location: mm/migrate.c:289
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812afab0-ffffffff812afb20: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e3369)
Location: mm/migrate.c:294
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
Direct callers:
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812e5b60-ffffffff812e5bd0: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ee7e9)
Location: mm/migrate.c:290
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
Direct callers:
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812f0f20-ffffffff812f0f90: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f4979)
Location: mm/migrate.c:263
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
Direct callers:
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812f7220-ffffffff812f7290: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133f119)
Location: mm/migrate.c:271
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
Direct callers:
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff81341880-ffffffff813418f0: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void remove_migration_ptes(struct folio *src, struct folio *dst, bool locked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b3c95)
Location: mm/migrate.c:271
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
Direct callers:
  - mm/migrate.c:writeout
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff813b3430-ffffffff813b34b6: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void remove_migration_ptes(struct folio *src, struct folio *dst, bool locked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff814348e6)
Location: mm/migrate.c:286
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
Direct callers:
  - mm/migrate.c:writeout
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
```
**Symbols:**

```
ffffffff81433950-ffffffff814339d6: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void remove_migration_ptes(struct folio *src, struct folio *dst, bool locked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8146ac44)
Location: mm/migrate.c:282
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_undo_src
Direct callers:
  - mm/migrate.c:writeout
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
```
**Symbols:**

```
ffffffff814693b0-ffffffff81469436: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void remove_migration_ptes(struct folio *src, struct folio *dst, bool locked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81499c22)
Location: mm/migrate.c:285
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_undo_src
Direct callers:
  - mm/migrate.c:writeout
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
```
**Symbols:**

```
ffffffff814982c0-ffffffff81498346: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff800010351934)
Location: mm/migrate.c:289
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
Direct callers:
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffff8000103509b8-ffff800010350a40: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0552084)
Location: mm/migrate.c:289
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
c0552084-c055210c: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0000000004358d0)
Location: mm/migrate.c:289
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
c0000000004358d0-c000000000435974: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe000240112)
Location: mm/migrate.c:289
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
Direct callers:
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffe00023f450-ffffffe00023f4c0: remove_migration_ptes (STB_GLOBAL)
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
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a8090)
Location: mm/migrate.c:289
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812a8090-ffffffff812a8100: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81299a50)
Location: mm/migrate.c:289
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff81299a50-ffffffff81299ac0: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a5ea0)
Location: mm/migrate.c:289
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812a5ea0-ffffffff812a5f10: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void remove_migration_ptes(struct page *old, struct page *new, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b61f0)
Location: mm/migrate.c:289
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812b61f0-ffffffff812b6260: remove_migration_ptes (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool locked</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *src</code>
</li>
<li>
<b>Param added. </b>
<code>struct folio *dst</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *old</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *new</code>
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
