# Function: <code>radix_tree_tag_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct radix_tree_root *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813ee1c0)
Location: lib/radix-tree.c:592
Inline: False
Direct callers:
  - mm/page-writeback.c:__set_page_dirty_nobuffers
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/shmem.c:shmem_add_seals
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff813ee1c0-ffffffff813ee24b: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct radix_tree_root *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81434390)
Location: lib/radix-tree.c:762
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/shmem.c:shmem_add_seals
  - fs/buffer.c:__set_page_dirty
  - fs/dax.c:dax_pfn_mkwrite
  - fs/dax.c:dax_fault
```
**Symbols:**

```
ffffffff81434390-ffffffff81434478: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct radix_tree_root *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81450900)
Location: lib/radix-tree.c:1277
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/shmem.c:shmem_add_seals
  - fs/buffer.c:__set_page_dirty
  - fs/dax.c:dax_pfn_mkwrite
  - fs/dax.c:dax_insert_mapping_entry
```
**Symbols:**

```
ffffffff81450900-ffffffff814509e8: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct radix_tree_root *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f0540)
Location: lib/radix-tree.c:1423
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/shmem.c:shmem_add_seals
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff818f0540-ffffffff818f0628: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct radix_tree_root *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81976990)
Location: lib/radix-tree.c:1421
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/shmem.c:shmem_add_seals
  - fs/buffer.c:__set_page_dirty
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_insert_mapping_entry
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
**Symbols:**

```
ffffffff81976990-ffffffff81976a78: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct radix_tree_root *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3140)
Location: lib/radix-tree.c:1422
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/memfd.c:memfd_fcntl
  - fs/buffer.c:__set_page_dirty
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_insert_mapping_entry
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
**Symbols:**

```
ffffffff819d3140-ffffffff819d322e: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0cb30)
Location: lib/radix-tree.c:988
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
**Symbols:**

```
ffffffff81a0cb30-ffffffff81a0cbda: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7c4c0)
Location: lib/radix-tree.c:975
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81a7c4c0-ffffffff81a7c554: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab37f0)
Location: lib/radix-tree.c:975
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81ab37f0-ffffffff81ab3884: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815ee910)
Location: lib/radix-tree.c:967
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff815ee910-ffffffff815ee9b9: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81613060)
Location: lib/radix-tree.c:967
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81613060-ffffffff81613109: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f67b0)
Location: lib/radix-tree.c:968
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff815f67b0-ffffffff815f6859: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:968
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81cdf7bd-ffffffff81cdf853: radix_tree_tag_set.cold (STB_LOCAL)
ffffffff81663c70-ffffffff81663d65: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:968
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81ea5f5d-ffffffff81ea5ff3: radix_tree_tag_set.cold (STB_LOCAL)
ffffffff8177de80-ffffffff8177df7c: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:968
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff820b78da-ffffffff820b7970: radix_tree_tag_set.cold (STB_LOCAL)
ffffffff8203aa10-ffffffff8203ab0c: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:967
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff82138d37-ffffffff82138dde: radix_tree_tag_set.cold (STB_LOCAL)
ffffffff820b8e80-ffffffff820b8fe2: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:967
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff8221aadc-ffffffff8221ab83: radix_tree_tag_set.cold (STB_LOCAL)
ffffffff82193790-ffffffff821938f2: radix_tree_tag_set (STB_GLOBAL)
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
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8d490)
Location: lib/radix-tree.c:975
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffff800010d8d490-ffff800010d8d548: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e87980)
Location: lib/radix-tree.c:975
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
c0e87980-c0e87a48: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ecf960)
Location: lib/radix-tree.c:975
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
**Symbols:**

```
c000000000ecf960-c000000000ecfa4c: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b674c)
Location: lib/radix-tree.c:975
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
**Symbols:**

```
ffffffe0008b674c-ffffffe0008b67f4: radix_tree_tag_set (STB_GLOBAL)
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
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a52640)
Location: lib/radix-tree.c:975
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81a52640-ffffffff81a526d4: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0f740)
Location: lib/radix-tree.c:975
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81a0f740-ffffffff81a0f7d4: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abea30)
Location: lib/radix-tree.c:975
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81abea30-ffffffff81abeac4: radix_tree_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *radix_tree_tag_set(struct xarray *root, long unsigned int index, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acaef0)
Location: lib/radix-tree.c:975
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register
```
**Symbols:**

```
ffffffff81acaef0-ffffffff81acaf84: radix_tree_tag_set (STB_GLOBAL)
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
