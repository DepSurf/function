# Function: <code>ext4_break_layouts</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81354210)
Location: fs/ext4/inode.c:4207
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81354210-ffffffff81354319: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136c480)
Location: fs/ext4/inode.c:4239
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8136c480-ffffffff8136c587: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81395a60)
Location: fs/ext4/inode.c:4251
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81395a60-ffffffff81395b4c: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ae430)
Location: fs/ext4/inode.c:4228
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813ae430-ffffffff813ae51c: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fa3d0)
Location: fs/ext4/inode.c:3926
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813fa3d0-ffffffff813fa4ba: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140c9a0)
Location: fs/ext4/inode.c:3961
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8140c9a0-ffffffff8140ca8a: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81412b20)
Location: fs/ext4/inode.c:3960
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81412b20-ffffffff81412c0a: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81465e40)
Location: fs/ext4/inode.c:3884
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81465e40-ffffffff81465f39: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e58b0)
Location: fs/ext4/inode.c:3949
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff814e58b0-ffffffff814e59d1: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157efd0)
Location: fs/ext4/inode.c:4035
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8157efd0-ffffffff8157f0f1: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b6480)
Location: fs/ext4/inode.c:3824
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff815b6480-ffffffff815b65a1: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ef220)
Location: fs/ext4/inode.c:3841
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff815ef220-ffffffff815ef341: ext4_break_layouts (STB_GLOBAL)
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
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010482f68)
Location: fs/ext4/inode.c:4228
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffff800010482f68-ffff800010483080: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0644404)
Location: fs/ext4/inode.c:4228
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
c0644404-c064446c: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a7cf0)
Location: fs/ext4/inode.c:4228
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
c0000000005a7cf0-c0000000005a7e60: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030b6d0)
Location: fs/ext4/inode.c:4228
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffe00030b6d0-ffffffe00030b7a6: ext4_break_layouts (STB_GLOBAL)
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
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a6a10)
Location: fs/ext4/inode.c:4228
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813a6a10-ffffffff813a6afc: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813974a0)
Location: fs/ext4/inode.c:4228
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813974a0-ffffffff8139758c: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a4270)
Location: fs/ext4/inode.c:4228
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813a4270-ffffffff813a435c: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_break_layouts(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b8970)
Location: fs/ext4/inode.c:4228
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813b8970-ffffffff813b8a5c: ext4_break_layouts (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
