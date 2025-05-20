# Function: <code>radix_tree_lookup_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(struct radix_tree_root *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813eefb0)
Location: lib/radix-tree.c:551
Inline: False
Direct callers:
  - mm/filemap.c:find_get_entry
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
```
**Symbols:**

```
ffffffff813eefb0-ffffffff813eeff5: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(struct radix_tree_root *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81435770)
Location: lib/radix-tree.c:721
Inline: False
Direct callers:
  - mm/filemap.c:find_get_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81435770-ffffffff814357b5: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(struct radix_tree_root *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81451f10)
Location: lib/radix-tree.c:955
Inline: False
Direct callers:
  - mm/filemap.c:find_get_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff81451f10-ffffffff81451f55: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct radix_tree_root *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f1e20)
Location: lib/radix-tree.c:1074
Inline: False
Direct callers:
  - mm/filemap.c:find_get_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff818f1e20-ffffffff818f1e65: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct radix_tree_root *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819782d0)
Location: lib/radix-tree.c:1073
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
  - mm/filemap.c:find_get_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff819782d0-ffffffff81978315: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct radix_tree_root *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d49e0)
Location: lib/radix-tree.c:1074
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
  - mm/filemap.c:find_get_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff819d49e0-ffffffff819d4a25: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d640)
Location: lib/radix-tree.c:816
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81a0d640-ffffffff81a0d681: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7cf80)
Location: lib/radix-tree.c:803
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81a7cf80-ffffffff81a7cfc0: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab42b0)
Location: lib/radix-tree.c:803
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81ab42b0-ffffffff81ab42f0: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eec50)
Location: lib/radix-tree.c:795
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff815eec50-ffffffff815eec90: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff816133a0)
Location: lib/radix-tree.c:795
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff816133a0-ffffffff816133e0: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f6a00)
Location: lib/radix-tree.c:795
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff815f6a00-ffffffff815f6a40: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81664100)
Location: lib/radix-tree.c:795
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81664100-ffffffff81664140: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177e360)
Location: lib/radix-tree.c:795
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff8177e360-ffffffff8177e3b5: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8203af40)
Location: lib/radix-tree.c:795
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff8203af40-ffffffff8203af95: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b9420)
Location: lib/radix-tree.c:794
Inline: False
```
**Symbols:**

```
ffffffff820b9420-ffffffff820b9475: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82193d30)
Location: lib/radix-tree.c:794
Inline: False
```
**Symbols:**

```
ffffffff82193d30-ffffffff82193d85: radix_tree_lookup_slot (STB_GLOBAL)
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
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8e7b0)
Location: lib/radix-tree.c:803
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffff800010d8e7b0-ffff800010d8e7fc: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e88eac)
Location: lib/radix-tree.c:803
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
c0e88eac-c0e88f08: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed13f0)
Location: lib/radix-tree.c:803
Inline: False
```
**Symbols:**

```
c000000000ed13f0-c000000000ed1454: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b721c)
Location: lib/radix-tree.c:803
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffe0008b721c-ffffffe0008b7240: radix_tree_lookup_slot (STB_GLOBAL)
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
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a53100)
Location: lib/radix-tree.c:803
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81a53100-ffffffff81a53140: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a10200)
Location: lib/radix-tree.c:803
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81a10200-ffffffff81a10240: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf4f0)
Location: lib/radix-tree.c:803
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81abf4f0-ffffffff81abf530: radix_tree_lookup_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void **radix_tree_lookup_slot(const struct xarray *root, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acb9c0)
Location: lib/radix-tree.c:803
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_fix_revmap
```
**Symbols:**

```
ffffffff81acb9c0-ffffffff81acba00: radix_tree_lookup_slot (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root *root</code> ➡️ <code>const struct radix_tree_root *root</code>
</li>
</ul>
</details>
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
<code>const struct radix_tree_root *root</code> ➡️ <code>const struct xarray *root</code>
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
