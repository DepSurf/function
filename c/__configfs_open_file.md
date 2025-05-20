# Function: <code>__configfs_open_file</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (ffffffff81370a40)
Location: fs/configfs/file.c:356
Inline: True
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff81370a40-ffffffff81370c1f: __configfs_open_file.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (ffffffff81388f20)
Location: fs/configfs/file.c:356
Inline: True
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff81388f20-ffffffff813890ff: __configfs_open_file.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __configfs_open_file(struct inode *inode, struct file *file, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff813d3a30)
Location: fs/configfs/file.c:356
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff813d3a30-ffffffff813d3c0f: __configfs_open_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __configfs_open_file(struct inode *inode, struct file *file, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff813e5770)
Location: fs/configfs/file.c:356
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff813e5770-ffffffff813e5943: __configfs_open_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __configfs_open_file(struct inode *inode, struct file *file, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff813ec380)
Location: fs/configfs/file.c:354
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff813ec380-ffffffff813ec553: __configfs_open_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __configfs_open_file(struct inode *inode, struct file *file, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:290
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff8143e260-ffffffff8143e441: __configfs_open_file (STB_LOCAL)
ffffffff81cc8751-ffffffff81cc8766: __configfs_open_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __configfs_open_file(struct inode *inode, struct file *file, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:290
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff814b9b80-ffffffff814b9d66: __configfs_open_file (STB_LOCAL)
ffffffff81e7b49e-ffffffff81e7b4b3: __configfs_open_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __configfs_open_file(struct inode *inode, struct file *file, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:290
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff81551350-ffffffff81551536: __configfs_open_file (STB_LOCAL)
ffffffff8206bcc8-ffffffff8206bcdd: __configfs_open_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __configfs_open_file(struct inode *inode, struct file *file, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:290
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff81589070-ffffffff81589254: __configfs_open_file (STB_LOCAL)
ffffffff820ebb56-ffffffff820ebb6b: __configfs_open_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __configfs_open_file(struct inode *inode, struct file *file, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:290
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff815c1c40-ffffffff815c1e5c: __configfs_open_file (STB_LOCAL)
ffffffff821c8dba-ffffffff821c8dcf: __configfs_open_file.cold (STB_LOCAL)
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
In fs/configfs/file.c (ffff800010459320)
Location: fs/configfs/file.c:356
Inline: True
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffff800010459320-ffff800010459504: __configfs_open_file.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __configfs_open_file(struct inode *inode, struct file *file, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (c061aaec)
Location: fs/configfs/file.c:356
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
c061aaec-c061acc8: __configfs_open_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __configfs_open_file(struct inode *inode, struct file *file, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (c0000000005744a0)
Location: fs/configfs/file.c:356
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
c0000000005744a0-c000000000574760: __configfs_open_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __configfs_open_file(struct inode *inode, struct file *file, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffe0002e9d7a)
Location: fs/configfs/file.c:356
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffe0002e9d7a-ffffffe0002e9f06: __configfs_open_file (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (ffffffff81381500)
Location: fs/configfs/file.c:356
Inline: True
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff81381500-ffffffff813816df: __configfs_open_file.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (ffffffff81371f90)
Location: fs/configfs/file.c:356
Inline: True
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff81371f90-ffffffff8137216f: __configfs_open_file.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (ffffffff8137efd0)
Location: fs/configfs/file.c:356
Inline: True
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff8137efd0-ffffffff8137f1af: __configfs_open_file.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (ffffffff81392ad0)
Location: fs/configfs/file.c:356
Inline: True
Direct callers:
  - fs/configfs/file.c:configfs_open_bin_file
  - fs/configfs/file.c:configfs_open_file
```
**Symbols:**

```
ffffffff81392ad0-ffffffff81392caf: __configfs_open_file.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
