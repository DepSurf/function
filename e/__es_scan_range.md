# Function: <code>__es_scan_range</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81359eb0)
Location: fs/ext4/extents_status.c:338
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
**Symbols:**

```
ffffffff81359eb0-ffffffff81359f23: __es_scan_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81382f00)
Location: fs/ext4/extents_status.c:338
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
**Symbols:**

```
ffffffff81382f00-ffffffff81382f7a: __es_scan_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139b410)
Location: fs/ext4/extents_status.c:338
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
**Symbols:**

```
ffffffff8139b410-ffffffff8139b48a: __es_scan_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e716f)
Location: fs/ext4/extents_status.c:338
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813f942f)
Location: fs/ext4/extents_status.c:341
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813fee01)
Location: fs/ext4/extents_status.c:341
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81451659)
Location: fs/ext4/extents_status.c:341
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814cf760)
Location: fs/ext4/extents_status.c:341
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81568030)
Location: fs/ext4/extents_status.c:339
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8159fc39)
Location: fs/ext4/extents_status.c:339
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815d8855)
Location: fs/ext4/extents_status.c:340
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
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
bool __es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff80001046e040)
Location: fs/ext4/extents_status.c:338
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
**Symbols:**

```
ffff80001046e040-ffff80001046e100: __es_scan_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c062f600)
Location: fs/ext4/extents_status.c:338
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
**Symbols:**

```
c062f600-c062f6a8: __es_scan_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c00000000058e070)
Location: fs/ext4/extents_status.c:338
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
**Symbols:**

```
c00000000058e070-c00000000058e138: __es_scan_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fb0ae)
Location: fs/ext4/extents_status.c:338
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
**Symbols:**

```
ffffffe0002fb0ae-ffffffe0002fb12e: __es_scan_range (STB_LOCAL)
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
bool __es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813939f0)
Location: fs/ext4/extents_status.c:338
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
**Symbols:**

```
ffffffff813939f0-ffffffff81393a6a: __es_scan_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81384480)
Location: fs/ext4/extents_status.c:338
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
**Symbols:**

```
ffffffff81384480-ffffffff813844fa: __es_scan_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81391350)
Location: fs/ext4/extents_status.c:338
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
**Symbols:**

```
ffffffff81391350-ffffffff813913ca: __es_scan_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a51e0)
Location: fs/ext4/extents_status.c:338
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
```
**Symbols:**

```
ffffffff813a51e0-ffffffff813a525a: __es_scan_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
