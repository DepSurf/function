# Function: <code>ext4_fill_fiemap_extents</code>

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
In fs/ext4/extents.c (ffffffff812c99b0)
Location: fs/ext4/extents.c:2146
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
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
In fs/ext4/extents.c (ffffffff812f9294)
Location: fs/ext4/extents.c:2158
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
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
In fs/ext4/extents.c (ffffffff8130f294)
Location: fs/ext4/extents.c:2158
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
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
In fs/ext4/extents.c (ffffffff812ed7cf)
Location: fs/ext4/extents.c:2158
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
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
In fs/ext4/extents.c (ffffffff8131228f)
Location: fs/ext4/extents.c:2158
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
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
In fs/ext4/extents.c (ffffffff8134017b)
Location: fs/ext4/extents.c:2152
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
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
In fs/ext4/extents.c (ffffffff8135775b)
Location: fs/ext4/extents.c:2152
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_fill_fiemap_extents(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137ce40)
Location: fs/ext4/extents.c:2169
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
```
**Symbols:**

```
ffffffff8137ce40-ffffffff8137d27d: ext4_fill_fiemap_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_fill_fiemap_extents(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81395540)
Location: fs/ext4/extents.c:2169
Inline: False
```
**Symbols:**

```
ffffffff81395540-ffffffff8139597d: ext4_fill_fiemap_extents (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ext4_fill_fiemap_extents(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010468340)
Location: fs/ext4/extents.c:2169
Inline: False
```
**Symbols:**

```
ffff800010468340-ffff800010468748: ext4_fill_fiemap_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_fill_fiemap_extents(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062903c)
Location: fs/ext4/extents.c:2169
Inline: False
```
**Symbols:**

```
c062903c-c06294d0: ext4_fill_fiemap_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_fill_fiemap_extents(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0000000005866c0)
Location: fs/ext4/extents.c:2169
Inline: False
```
**Symbols:**

```
c0000000005866c0-c000000000586c34: ext4_fill_fiemap_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_fill_fiemap_extents(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f5fbe)
Location: fs/ext4/extents.c:2169
Inline: False
```
**Symbols:**

```
ffffffe0002f5fbe-ffffffe0002f62fe: ext4_fill_fiemap_extents (STB_LOCAL)
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
int ext4_fill_fiemap_extents(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138db20)
Location: fs/ext4/extents.c:2169
Inline: False
```
**Symbols:**

```
ffffffff8138db20-ffffffff8138df5d: ext4_fill_fiemap_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_fill_fiemap_extents(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137e5b0)
Location: fs/ext4/extents.c:2169
Inline: False
```
**Symbols:**

```
ffffffff8137e5b0-ffffffff8137e9ed: ext4_fill_fiemap_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_fill_fiemap_extents(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138b480)
Location: fs/ext4/extents.c:2169
Inline: False
```
**Symbols:**

```
ffffffff8138b480-ffffffff8138b8bd: ext4_fill_fiemap_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_fill_fiemap_extents(struct inode *inode, ext4_lblk_t block, ext4_lblk_t num, struct fiemap_extent_info *fieinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139f1d0)
Location: fs/ext4/extents.c:2169
Inline: False
```
**Symbols:**

```
ffffffff8139f1d0-ffffffff8139f60d: ext4_fill_fiemap_extents (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
