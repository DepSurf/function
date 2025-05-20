# Function: <code>radix_tree_replace_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118ddad)
Location: include/linux/radix-tree.h:257
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff8119e73d)
Location: include/linux/radix-tree.h:257
Inline: True
```
```
In mm/shmem.c (ffffffff811a7da8)
Location: include/linux/radix-tree.h:257
Inline: True
```
```
In mm/migrate.c (ffffffff811f1778)
Location: include/linux/radix-tree.h:257
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8119f848)
Location: include/linux/radix-tree.h:259
Inline: True
Inline callers:
  - mm/filemap.c:page_cache_tree_insert
```
```
In mm/truncate.c (ffffffff811b4126)
Location: include/linux/radix-tree.h:259
Inline: True
```
```
In mm/shmem.c (ffffffff811be225)
Location: include/linux/radix-tree.h:259
Inline: True
```
```
In mm/migrate.c (ffffffff81211af1)
Location: include/linux/radix-tree.h:259
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8121ade8)
Location: include/linux/radix-tree.h:259
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/dax.c (ffffffff81288175)
Location: include/linux/radix-tree.h:259
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_unlock_mapping_entry
```
```
In lib/radix-tree.c (ffffffff81435bfc)
Location: include/linux/radix-tree.h:259
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_replace_clear_tags
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct radix_tree_root *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81452180)
Location: lib/radix-tree.c:1100
Inline: False
Direct callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_pfn_mkwrite
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_mapping_entry
```
**Symbols:**

```
ffffffff81452180-ffffffff81452192: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct radix_tree_root *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f2030)
Location: lib/radix-tree.c:1225
Inline: False
Direct callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_mapping_entry
```
**Symbols:**

```
ffffffff818f2030-ffffffff818f2049: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct radix_tree_root *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819784d0)
Location: lib/radix-tree.c:1223
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_mapping_entry
```
**Symbols:**

```
ffffffff819784d0-ffffffff819784e6: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct radix_tree_root *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d4bf0)
Location: lib/radix-tree.c:1224
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:unlock_mapping_entry
```
**Symbols:**

```
ffffffff819d4bf0-ffffffff819d4c06: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d860)
Location: lib/radix-tree.c:936
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81a0d860-ffffffff81a0d873: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7d1d0)
Location: lib/radix-tree.c:923
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81a7d1d0-ffffffff81a7d1e3: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab4500)
Location: lib/radix-tree.c:923
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81ab4500-ffffffff81ab4513: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eeb40)
Location: lib/radix-tree.c:915
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff815eeb40-ffffffff815eeb8b: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81613290)
Location: lib/radix-tree.c:915
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81613290-ffffffff816132db: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f68f0)
Location: lib/radix-tree.c:915
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff815f68f0-ffffffff815f693b: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81663b50)
Location: lib/radix-tree.c:915
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81663b50-ffffffff81663b9b: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177dd30)
Location: lib/radix-tree.c:915
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff8177dd30-ffffffff8177dda8: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8203a8a0)
Location: lib/radix-tree.c:915
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff8203a8a0-ffffffff8203a918: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b8d10)
Location: lib/radix-tree.c:914
Inline: False
```
**Symbols:**

```
ffffffff820b8d10-ffffffff820b8d90: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82193620)
Location: lib/radix-tree.c:914
Inline: False
```
**Symbols:**

```
ffffffff82193620-ffffffff821936a0: radix_tree_replace_slot (STB_GLOBAL)
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
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8ea20)
Location: lib/radix-tree.c:923
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffff800010d8ea20-ffff800010d8ea40: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e8919c)
Location: lib/radix-tree.c:923
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
c0e8919c-c0e891bc: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed1730)
Location: lib/radix-tree.c:923
Inline: False
```
**Symbols:**

```
c000000000ed1730-c000000000ed174c: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b7428)
Location: lib/radix-tree.c:923
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffe0008b7428-ffffffe0008b7446: radix_tree_replace_slot (STB_GLOBAL)
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
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a53350)
Location: lib/radix-tree.c:923
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81a53350-ffffffff81a53363: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a10450)
Location: lib/radix-tree.c:923
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81a10450-ffffffff81a10463: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf740)
Location: lib/radix-tree.c:923
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81abf740-ffffffff81abf753: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray *root, void **slot, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acbc10)
Location: lib/radix-tree.c:923
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81acbc10-ffffffff81acbc23: radix_tree_replace_slot (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root *root</code> ➡️ <code>struct xarray *root</code>
</li>
</ul>
</details>
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
