# Function: <code>ext4_convert_meta_bg</code>

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
In fs/ext4/resize.c (ffffffff812c1cf1)
Location: fs/ext4/resize.c:1779
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
In fs/ext4/resize.c (ffffffff812f142f)
Location: fs/ext4/resize.c:1779
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
In fs/ext4/resize.c (ffffffff813073ff)
Location: fs/ext4/resize.c:1779
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
In fs/ext4/resize.c (ffffffff81321edf)
Location: fs/ext4/resize.c:1780
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
In fs/ext4/resize.c (ffffffff81346618)
Location: fs/ext4/resize.c:1808
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
In fs/ext4/resize.c (ffffffff813747b8)
Location: fs/ext4/resize.c:1811
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
In fs/ext4/resize.c (ffffffff8138c915)
Location: fs/ext4/resize.c:1811
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
In fs/ext4/resize.c (ffffffff813b7029)
Location: fs/ext4/resize.c:1817
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
In fs/ext4/resize.c (ffffffff813cff5f)
Location: fs/ext4/resize.c:1853
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
int ext4_convert_meta_bg(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81419350)
Location: fs/ext4/resize.c:1831
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff81419350-ffffffff814195bf: ext4_convert_meta_bg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_convert_meta_bg(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8142d3f0)
Location: fs/ext4/resize.c:1842
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff8142d3f0-ffffffff8142d6a7: ext4_convert_meta_bg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_convert_meta_bg(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff814340b0)
Location: fs/ext4/resize.c:1842
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff814340b0-ffffffff81434367: ext4_convert_meta_bg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_convert_meta_bg(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1854
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff81487af0-ffffffff81487dd9: ext4_convert_meta_bg (STB_LOCAL)
ffffffff81ccd097-ffffffff81ccd0b5: ext4_convert_meta_bg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_convert_meta_bg(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1877
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff8150b3e0-ffffffff8150b701: ext4_convert_meta_bg (STB_LOCAL)
ffffffff81e7ffb1-ffffffff81e7ffcf: ext4_convert_meta_bg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_convert_meta_bg(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1910
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff815a6080-ffffffff815a63a5: ext4_convert_meta_bg (STB_LOCAL)
ffffffff8207045f-ffffffff8207047d: ext4_convert_meta_bg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_convert_meta_bg(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1909
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff815dc8f0-ffffffff815dcc15: ext4_convert_meta_bg (STB_LOCAL)
ffffffff820f0135-ffffffff820f0153: ext4_convert_meta_bg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_convert_meta_bg(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1908
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
```
**Symbols:**

```
ffffffff816151d0-ffffffff816154e2: ext4_convert_meta_bg (STB_LOCAL)
ffffffff821cd2f2-ffffffff821cd310: ext4_convert_meta_bg.cold (STB_LOCAL)
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
In fs/ext4/resize.c (ffff8000104a892c)
Location: fs/ext4/resize.c:1853
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
In fs/ext4/resize.c (c066ad1c)
Location: fs/ext4/resize.c:1853
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
In fs/ext4/resize.c (c0000000005d6bf0)
Location: fs/ext4/resize.c:1853
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
In fs/ext4/resize.c (ffffffe0003291f2)
Location: fs/ext4/resize.c:1853
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
In fs/ext4/resize.c (ffffffff813c853f)
Location: fs/ext4/resize.c:1853
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
In fs/ext4/resize.c (ffffffff813b8fbf)
Location: fs/ext4/resize.c:1853
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
In fs/ext4/resize.c (ffffffff813c59cf)
Location: fs/ext4/resize.c:1853
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
In fs/ext4/resize.c (ffffffff813dabff)
Location: fs/ext4/resize.c:1853
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
