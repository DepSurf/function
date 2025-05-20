# Function: <code>fsverity_file_open</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (ffffffff81350e75)
Location: fs/verity/open.c:294
Inline: True
```
**Symbols:**

```
ffffffff81351060-ffffffff813510bf: fsverity_file_open.cold (STB_LOCAL)
ffffffff81350d90-ffffffff81350ea9: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813978b0)
Location: fs/verity/open.c:295
Inline: True
```
**Symbols:**

```
ffffffff813978b0-ffffffff813978f9: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813a9320)
Location: fs/verity/open.c:304
Inline: True
```
**Symbols:**

```
ffffffff813a9320-ffffffff813a9369: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813b03a0)
Location: fs/verity/open.c:345
Inline: True
```
**Symbols:**

```
ffffffff813b03a0-ffffffff813b047f: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813fff90)
Location: fs/verity/open.c:345
Inline: True
```
**Symbols:**

```
ffffffff813fff90-ffffffff8140006c: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81473da0)
Location: fs/verity/open.c:341
Inline: True
```
**Symbols:**

```
ffffffff81473da0-ffffffff81473e77: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81505fd0)
Location: fs/verity/open.c:341
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_file_open
```
**Symbols:**

```
ffffffff81505fd0-ffffffff815060a7: fsverity_file_open (STB_GLOBAL)
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
In fs/ext4/file.c (ffffffff815a19c4)
Location: include/linux/fsverity.h:297
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
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
In fs/ext4/file.c (ffffffff815daa64)
Location: include/linux/fsverity.h:297
Inline: True
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
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffff800010412ef0)
Location: fs/verity/open.c:294
Inline: True
```
**Symbols:**

```
ffff800010412ef0-ffff80001041308c: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (c05df28c)
Location: fs/verity/open.c:294
Inline: True
```
**Symbols:**

```
c05df28c-c05df400: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (c000000000520bf0)
Location: fs/verity/open.c:294
Inline: True
```
**Symbols:**

```
c000000000520bf0-c000000000520e48: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffe0002baad6)
Location: fs/verity/open.c:294
Inline: True
```
**Symbols:**

```
ffffffe0002baad6-ffffffe0002bac34: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (ffffffff81349455)
Location: fs/verity/open.c:294
Inline: True
```
**Symbols:**

```
ffffffff81349640-ffffffff8134969f: fsverity_file_open.cold (STB_LOCAL)
ffffffff81349370-ffffffff81349489: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (ffffffff8133a135)
Location: fs/verity/open.c:294
Inline: True
```
**Symbols:**

```
ffffffff8133a320-ffffffff8133a37f: fsverity_file_open.cold (STB_LOCAL)
ffffffff8133a050-ffffffff8133a169: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (ffffffff81346f25)
Location: fs/verity/open.c:294
Inline: True
```
**Symbols:**

```
ffffffff81347110-ffffffff8134716f: fsverity_file_open.cold (STB_LOCAL)
ffffffff81346e40-ffffffff81346f59: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fsverity_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (ffffffff8135a205)
Location: fs/verity/open.c:294
Inline: True
```
**Symbols:**

```
ffffffff8135a3f0-ffffffff8135a44f: fsverity_file_open.cold (STB_LOCAL)
ffffffff8135a120-ffffffff8135a239: fsverity_file_open (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
