# Function: <code>ext4_update_disksize_before_punch</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812ca100)
Location: fs/ext4/inode.c:3869
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff812ca100-ffffffff812ca21c: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dfdd0)
Location: fs/ext4/inode.c:3995
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff812dfdd0-ffffffff812dfeec: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813041b0)
Location: fs/ext4/inode.c:4115
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813041b0-ffffffff8130427d: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81328bb0)
Location: fs/ext4/inode.c:4164
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81328bb0-ffffffff81328c7d: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81356f40)
Location: fs/ext4/inode.c:4176
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81356f40-ffffffff81357014: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136f260)
Location: fs/ext4/inode.c:4209
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8136f260-ffffffff8136f334: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:4221
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8139c73b-ffffffff8139c75e: ext4_update_disksize_before_punch.cold (STB_LOCAL)
ffffffff813987b0-ffffffff81398888: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b11f0)
Location: fs/ext4/inode.c:4198
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813b11f0-ffffffff813b12c7: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fce30)
Location: fs/ext4/inode.c:3894
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813fce30-ffffffff813fcf32: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140f5a0)
Location: fs/ext4/inode.c:3929
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8140f5a0-ffffffff8140f6a2: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81415920)
Location: fs/ext4/inode.c:3928
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81415920-ffffffff81415a22: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81468e60)
Location: fs/ext4/inode.c:3852
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81468e60-ffffffff81468f62: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e8c50)
Location: fs/ext4/inode.c:3917
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff814e8c50-ffffffff814e8d5f: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81582740)
Location: fs/ext4/inode.c:4003
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81582740-ffffffff8158285c: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b9330)
Location: fs/ext4/inode.c:3792
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff815b9330-ffffffff815b944c: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815f20b0)
Location: fs/ext4/inode.c:3809
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff815f20b0-ffffffff815f21cc: ext4_update_disksize_before_punch (STB_GLOBAL)
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
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010485b30)
Location: fs/ext4/inode.c:4198
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffff800010485b30-ffff800010485c2c: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0647798)
Location: fs/ext4/inode.c:4198
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
c0647798-c064794c: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005ab4f0)
Location: fs/ext4/inode.c:4198
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
c0000000005ab4f0-c0000000005ab668: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030dcdc)
Location: fs/ext4/inode.c:4198
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffe00030dcdc-ffffffe00030ddac: ext4_update_disksize_before_punch (STB_GLOBAL)
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
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a97d0)
Location: fs/ext4/inode.c:4198
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813a97d0-ffffffff813a98a7: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139a260)
Location: fs/ext4/inode.c:4198
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8139a260-ffffffff8139a337: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a7030)
Location: fs/ext4/inode.c:4198
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813a7030-ffffffff813a7107: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_update_disksize_before_punch(struct inode *inode, loff_t offset, loff_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813bb840)
Location: fs/ext4/inode.c:4198
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813bb840-ffffffff813bb917: ext4_update_disksize_before_punch (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
