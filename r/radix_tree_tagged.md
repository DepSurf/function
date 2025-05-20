# Function: <code>radix_tree_tagged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int radix_tree_tagged(struct radix_tree_root *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813ee010)
Location: lib/radix-tree.c:1438
Inline: False
Direct callers:
  - mm/page-writeback.c:mapping_tagged
  - mm/shmem.c:shmem_add_seals
```
**Symbols:**

```
ffffffff813ee010-ffffffff813ee023: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int radix_tree_tagged(struct radix_tree_root *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81434150)
Location: lib/radix-tree.c:1613
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/shmem.c:shmem_add_seals
```
**Symbols:**

```
ffffffff81434150-ffffffff81434162: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int radix_tree_tagged(struct radix_tree_root *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81450600)
Location: lib/radix-tree.c:1924
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/shmem.c:shmem_add_seals
```
**Symbols:**

```
ffffffff81450600-ffffffff81450612: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct radix_tree_root *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f0350)
Location: lib/radix-tree.c:2091
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/shmem.c:shmem_add_seals
```
**Symbols:**

```
ffffffff818f0350-ffffffff818f0362: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct radix_tree_root *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819767a0)
Location: lib/radix-tree.c:2088
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/shmem.c:shmem_add_seals
```
**Symbols:**

```
ffffffff819767a0-ffffffff819767b2: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct radix_tree_root *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d56ab)
Location: lib/radix-tree.c:2089
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff819d3050-ffffffff819d305e: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d90b)
Location: lib/radix-tree.c:1478
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffffffff81a0c3e0-ffffffff81a0c3ee: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7d27c)
Location: lib/radix-tree.c:1465
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffffffff81a7bd80-ffffffff81a7bd8e: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab45ac)
Location: lib/radix-tree.c:1465
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffffffff81ab30b0-ffffffff81ab30be: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eeeef)
Location: lib/radix-tree.c:1457
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
Direct callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
**Symbols:**

```
ffffffff815ed920-ffffffff815ed92e: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8161363f)
Location: lib/radix-tree.c:1457
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
Direct callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
**Symbols:**

```
ffffffff81612050-ffffffff8161205e: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f6c8f)
Location: lib/radix-tree.c:1458
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffffffff815f5740-ffffffff815f574e: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff81664399)
Location: lib/radix-tree.c:1458
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffffffff81cdf4ed-ffffffff81cdf50b: radix_tree_tagged.cold (STB_LOCAL)
ffffffff81663180-ffffffff816631a8: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff8177e6b6)
Location: lib/radix-tree.c:1458
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffffffff81ea5ca7-ffffffff81ea5cc5: radix_tree_tagged.cold (STB_LOCAL)
ffffffff8177d1b0-ffffffff8177d1e4: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff8203b306)
Location: lib/radix-tree.c:1458
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffffffff820b7616-ffffffff820b7634: radix_tree_tagged.cold (STB_LOCAL)
ffffffff82039a50-ffffffff82039a84: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff820b97e6)
Location: lib/radix-tree.c:1456
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffffffff82138b1d-ffffffff82138b3b: radix_tree_tagged.cold (STB_LOCAL)
ffffffff820b7d70-ffffffff820b7da4: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff821940f6)
Location: lib/radix-tree.c:1456
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
Direct callers:
  - drivers/gpu/drm/drm_lease.c:drm_mode_list_lessees_ioctl
```
**Symbols:**

```
ffffffff8221a8c2-ffffffff8221a8e0: radix_tree_tagged.cold (STB_LOCAL)
ffffffff82192680-ffffffff821926b4: radix_tree_tagged (STB_GLOBAL)
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
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8eae0)
Location: lib/radix-tree.c:1465
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffff800010d8d380-ffff800010d8d398: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e8924c)
Location: lib/radix-tree.c:1465
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
c0e8786c-c0e8788c: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed180c)
Location: lib/radix-tree.c:1465
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
c000000000ecf650-c000000000ecf66c: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b74e4)
Location: lib/radix-tree.c:1465
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffffffe0008b5fe2-ffffffe0008b5ffc: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a533fc)
Location: lib/radix-tree.c:1465
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffffffff81a51f00-ffffffff81a51f0e: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a104fc)
Location: lib/radix-tree.c:1465
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffffffff81a0f000-ffffffff81a0f00e: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf7ec)
Location: lib/radix-tree.c:1465
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffffffff81abe2f0-ffffffff81abe2fe: radix_tree_tagged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int radix_tree_tagged(const struct xarray *root, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acbcbc)
Location: lib/radix-tree.c:1465
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
```
**Symbols:**

```
ffffffff81aca790-ffffffff81aca79e: radix_tree_tagged (STB_GLOBAL)
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
