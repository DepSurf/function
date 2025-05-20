# Function: <code>ext4_setup_next_flex_gd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812c1909)
Location: fs/ext4/resize.c:1496
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812f12f9)
Location: fs/ext4/resize.c:1496
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813072c9)
Location: fs/ext4/resize.c:1496
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8132207b)
Location: fs/ext4/resize.c:1497
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813467c7)
Location: fs/ext4/resize.c:1523
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813745e3)
Location: fs/ext4/resize.c:1526
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffff8138cb69)
Location: fs/ext4/resize.c:1526
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffff813b7218)
Location: fs/ext4/resize.c:1534
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffff813d01a2)
Location: fs/ext4/resize.c:1570
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_setup_next_flex_gd(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t n_blocks_count, long unsigned int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8141a250)
Location: fs/ext4/resize.c:1548
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff8141a250-ffffffff8141a4bb: ext4_setup_next_flex_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_setup_next_flex_gd(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t n_blocks_count, long unsigned int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8142df60)
Location: fs/ext4/resize.c:1556
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff8142df60-ffffffff8142e1dd: ext4_setup_next_flex_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_setup_next_flex_gd(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t n_blocks_count, long unsigned int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81434c20)
Location: fs/ext4/resize.c:1556
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff81434c20-ffffffff81434e9a: ext4_setup_next_flex_gd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_setup_next_flex_gd(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t n_blocks_count, long unsigned int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1567
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff814886b0-ffffffff8148893d: ext4_setup_next_flex_gd (STB_LOCAL)
ffffffff81ccd138-ffffffff81ccd15a: ext4_setup_next_flex_gd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_setup_next_flex_gd(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t n_blocks_count, long unsigned int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1590
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff8150b710-ffffffff8150b9be: ext4_setup_next_flex_gd (STB_LOCAL)
ffffffff81e7ffcf-ffffffff81e7fff1: ext4_setup_next_flex_gd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_setup_next_flex_gd(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t n_blocks_count, long unsigned int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1625
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff815a63c0-ffffffff815a666e: ext4_setup_next_flex_gd (STB_LOCAL)
ffffffff8207047d-ffffffff8207049f: ext4_setup_next_flex_gd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_setup_next_flex_gd(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t n_blocks_count, long unsigned int flexbg_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1624
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff815dcc30-ffffffff815dcedc: ext4_setup_next_flex_gd (STB_LOCAL)
ffffffff820f0153-ffffffff820f0175: ext4_setup_next_flex_gd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_setup_next_flex_gd(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd, ext4_fsblk_t n_blocks_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1624
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff81615660-ffffffff8161590e: ext4_setup_next_flex_gd (STB_LOCAL)
ffffffff821cd34e-ffffffff821cd370: ext4_setup_next_flex_gd.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffff8000104a8c48)
Location: fs/ext4/resize.c:1570
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (c066b108)
Location: fs/ext4/resize.c:1570
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (c0000000005d68e0)
Location: fs/ext4/resize.c:1570
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffe000328d2c)
Location: fs/ext4/resize.c:1570
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffff813c8782)
Location: fs/ext4/resize.c:1570
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffff813b9202)
Location: fs/ext4/resize.c:1570
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffff813c5c12)
Location: fs/ext4/resize.c:1570
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/resize.c (ffffffff813dae42)
Location: fs/ext4/resize.c:1570
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int flexbg_size</code>
</li>
</ul>
</details>
</li>
</ul>
