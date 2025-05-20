# Function: <code>radix_tree_tag_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct radix_tree_root *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813ee250)
Location: lib/radix-tree.c:638
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/shmem.c:shmem_add_seals
  - lib/radix-tree.c:radix_tree_delete_item
```
**Symbols:**

```
ffffffff813ee250-ffffffff813ee318: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct radix_tree_root *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81435060)
Location: lib/radix-tree.c:824
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/shmem.c:shmem_add_seals
```
**Symbols:**

```
ffffffff81435060-ffffffff8143512a: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct radix_tree_root *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81451460)
Location: lib/radix-tree.c:1367
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/shmem.c:shmem_add_seals
```
**Symbols:**

```
ffffffff81451460-ffffffff8145152a: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct radix_tree_root *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f12f0)
Location: lib/radix-tree.c:1497
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/shmem.c:shmem_add_seals
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff818f12f0-ffffffff818f13c2: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct radix_tree_root *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81977770)
Location: lib/radix-tree.c:1495
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/shmem.c:shmem_add_seals
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81977770-ffffffff81977842: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct radix_tree_root *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3ed0)
Location: lib/radix-tree.c:1496
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/memfd.c:memfd_fcntl
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff819d3ed0-ffffffff819d3f93: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0cf20)
Location: lib/radix-tree.c:1050
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81a0cf20-ffffffff81a0cfa3: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7c870)
Location: lib/radix-tree.c:1037
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81a7c870-ffffffff81a7c8f9: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab3ba0)
Location: lib/radix-tree.c:1037
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81ab3ba0-ffffffff81ab3c29: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815ee310)
Location: lib/radix-tree.c:1029
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff815ee310-ffffffff815ee39c: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81612a40)
Location: lib/radix-tree.c:1029
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81612a40-ffffffff81612acc: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f6550)
Location: lib/radix-tree.c:1030
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff815f6550-ffffffff815f65e1: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1030
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81cdf779-ffffffff81cdf7bd: radix_tree_tag_clear.cold (STB_LOCAL)
ffffffff81663ba0-ffffffff81663c62: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1030
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81ea5f19-ffffffff81ea5f5d: radix_tree_tag_clear.cold (STB_LOCAL)
ffffffff8177ddb0-ffffffff8177de7f: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1030
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff820b7896-ffffffff820b78da: radix_tree_tag_clear.cold (STB_LOCAL)
ffffffff8203a930-ffffffff8203a9ff: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1029
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff82138cfa-ffffffff82138d37: radix_tree_tag_clear.cold (STB_LOCAL)
ffffffff820b8da0-ffffffff820b8e6f: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1029
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff8221aa9f-ffffffff8221aadc: radix_tree_tag_clear.cold (STB_LOCAL)
ffffffff821936b0-ffffffff8219377f: radix_tree_tag_clear (STB_GLOBAL)
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
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8dea0)
Location: lib/radix-tree.c:1037
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffff800010d8dea0-ffff800010d8df34: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e88598)
Location: lib/radix-tree.c:1037
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
c0e88598-c0e88624: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed0840)
Location: lib/radix-tree.c:1037
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
c000000000ed0840-c000000000ed0928: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b6b16)
Location: lib/radix-tree.c:1037
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffe0008b6b16-ffffffe0008b6b9e: radix_tree_tag_clear (STB_GLOBAL)
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
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a529f0)
Location: lib/radix-tree.c:1037
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81a529f0-ffffffff81a52a79: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0faf0)
Location: lib/radix-tree.c:1037
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81a0faf0-ffffffff81a0fb79: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abede0)
Location: lib/radix-tree.c:1037
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81abede0-ffffffff81abee69: radix_tree_tag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *radix_tree_tag_clear(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acb2a0)
Location: lib/radix-tree.c:1037
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81acb2a0-ffffffff81acb329: radix_tree_tag_clear (STB_GLOBAL)
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
