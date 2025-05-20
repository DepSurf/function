# Function: <code>vfs_dedupe_file_range_compare</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_dedupe_file_range_compare(struct inode *src, loff_t srcoff, struct inode *dest, loff_t destoff, loff_t len, bool *is_same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81244610)
Location: fs/read_write.c:1878
Inline: False
Direct callers:
  - fs/read_write.c:vfs_clone_file_prep_inodes
```
**Symbols:**

```
ffffffff81244610-ffffffff81244913: vfs_dedupe_file_range_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_dedupe_file_range_compare(struct inode *src, loff_t srcoff, struct inode *dest, loff_t destoff, loff_t len, bool *is_same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81250060)
Location: fs/read_write.c:1894
Inline: False
Direct callers:
  - fs/read_write.c:vfs_clone_file_prep_inodes
```
**Symbols:**

```
ffffffff81250060-ffffffff81250286: vfs_dedupe_file_range_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_dedupe_file_range_compare(struct inode *src, loff_t srcoff, struct inode *dest, loff_t destoff, loff_t len, bool *is_same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81271f80)
Location: fs/read_write.c:1897
Inline: False
Direct callers:
  - fs/read_write.c:vfs_clone_file_prep_inodes
```
**Symbols:**

```
ffffffff81271f80-ffffffff8127223c: vfs_dedupe_file_range_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfs_dedupe_file_range_compare(struct inode *src, loff_t srcoff, struct inode *dest, loff_t destoff, loff_t len, bool *is_same);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff81298467)
Location: fs/read_write.c:1924
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_prep_inodes
Direct callers:
  - fs/read_write.c:vfs_clone_file_prep_inodes
```
**Symbols:**

```
ffffffff81297f60-ffffffff81298251: vfs_dedupe_file_range_compare.part.26 (STB_LOCAL)
ffffffff81298260-ffffffff81298270: vfs_dedupe_file_range_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ad162)
Location: fs/read_write.c:1800
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c9b14)
Location: fs/read_write.c:1882
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812db5e5)
Location: fs/read_write.c:1880
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff81311580)
Location: fs/read_write.c:1964
Inline: True
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff81311580-ffffffff8131197d: vfs_dedupe_file_range_compare.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (ffffffff81366900)
Location: fs/remap_range.c:202
Inline: True
Direct callers:
  - fs/remap_range.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff81366900-ffffffff81366cf4: vfs_dedupe_file_range_compare.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (ffffffff8136d1b0)
Location: fs/remap_range.c:202
Inline: True
Direct callers:
  - fs/remap_range.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff8136d1b0-ffffffff8136d5a4: vfs_dedupe_file_range_compare.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (ffffffff813bbe90)
Location: fs/remap_range.c:190
Inline: True
Direct callers:
  - fs/remap_range.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff813bbe90-ffffffff813bc281: vfs_dedupe_file_range_compare.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (0)
Location: fs/remap_range.c:191
Inline: True
Direct callers:
  - fs/remap_range.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff81441d40-ffffffff814420fb: vfs_dedupe_file_range_compare.constprop.0 (STB_LOCAL)
ffffffff81e76c1f-ffffffff81e76c76: vfs_dedupe_file_range_compare.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (0)
Location: fs/remap_range.c:183
Inline: True
Direct callers:
  - fs/remap_range.c:__generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff814d08a0-ffffffff814d0b7d: vfs_dedupe_file_range_compare.constprop.0 (STB_LOCAL)
ffffffff82068dd1-ffffffff82068e28: vfs_dedupe_file_range_compare.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (0)
Location: fs/remap_range.c:186
Inline: True
Direct callers:
  - fs/remap_range.c:__generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff81506fa0-ffffffff8150727d: vfs_dedupe_file_range_compare.constprop.0 (STB_LOCAL)
ffffffff820e86f5-ffffffff820e8748: vfs_dedupe_file_range_compare.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (0)
Location: fs/remap_range.c:192
Inline: True
Direct callers:
  - fs/remap_range.c:__generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff8153c2c0-ffffffff8153c618: vfs_dedupe_file_range_compare.constprop.0 (STB_LOCAL)
ffffffff821c54e0-ffffffff821c5527: vfs_dedupe_file_range_compare.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffff8000103804b8)
Location: fs/read_write.c:1880
Inline: True
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffff8000103804b8-ffff800010380900: vfs_dedupe_file_range_compare.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056b424)
Location: fs/read_write.c:1880
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000477070)
Location: fs/read_write.c:1880
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000255b3e)
Location: fs/read_write.c:1880
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d3bc5)
Location: fs/read_write.c:1880
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c4845)
Location: fs/read_write.c:1880
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d19d5)
Location: fs/read_write.c:1880
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e27fd)
Location: fs/read_write.c:1880
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
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
</ul>
