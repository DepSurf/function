# Function: <code>ecryptfs_dir_open</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff81335220)
Location: fs/ecryptfs/file.c:263
Inline: True
```
**Symbols:**

```
ffffffff81335220-ffffffff813352e4: ecryptfs_dir_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff8134aff0)
Location: fs/ecryptfs/file.c:263
Inline: True
```
**Symbols:**

```
ffffffff8134aff0-ffffffff8134b0b4: ecryptfs_dir_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff8135fb80)
Location: fs/ecryptfs/file.c:263
Inline: True
```
**Symbols:**

```
ffffffff8135fb80-ffffffff8135fc44: ecryptfs_dir_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff81384840)
Location: fs/ecryptfs/file.c:263
Inline: True
```
**Symbols:**

```
ffffffff81384840-ffffffff81384904: ecryptfs_dir_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/file.c (0)
Location: fs/ecryptfs/file.c:274
Inline: True
```
**Symbols:**

```
ffffffff813b3620-ffffffff813b36b1: ecryptfs_dir_open (STB_LOCAL)
ffffffff813b36ea-ffffffff813b371a: ecryptfs_dir_open.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff813ccb77)
Location: fs/ecryptfs/file.c:274
Inline: True
```
**Symbols:**

```
ffffffff813ccb00-ffffffff813ccb91: ecryptfs_dir_open (STB_LOCAL)
ffffffff813ccbca-ffffffff813ccbfa: ecryptfs_dir_open.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff813f76d7)
Location: fs/ecryptfs/file.c:260
Inline: True
```
**Symbols:**

```
ffffffff813f7660-ffffffff813f76f8: ecryptfs_dir_open (STB_LOCAL)
ffffffff813f7731-ffffffff813f7761: ecryptfs_dir_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff814115a7)
Location: fs/ecryptfs/file.c:260
Inline: True
```
**Symbols:**

```
ffffffff81411530-ffffffff814115c8: ecryptfs_dir_open (STB_LOCAL)
ffffffff81411601-ffffffff81411631: ecryptfs_dir_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/file.c (0)
Location: fs/ecryptfs/file.c:260
Inline: False
```
**Symbols:**

```
ffffffff8145ee70-ffffffff8145ef08: ecryptfs_dir_open (STB_LOCAL)
ffffffff8145f53e-ffffffff8145f56e: ecryptfs_dir_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/file.c (0)
Location: fs/ecryptfs/file.c:260
Inline: False
```
**Symbols:**

```
ffffffff8147ab10-ffffffff8147aba8: ecryptfs_dir_open (STB_LOCAL)
ffffffff81bedf6f-ffffffff81bedf9f: ecryptfs_dir_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/file.c (0)
Location: fs/ecryptfs/file.c:260
Inline: False
```
**Symbols:**

```
ffffffff81480550-ffffffff814805e8: ecryptfs_dir_open (STB_LOCAL)
ffffffff81be0079-ffffffff81be00a9: ecryptfs_dir_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/file.c (0)
Location: fs/ecryptfs/file.c:260
Inline: False
```
**Symbols:**

```
ffffffff814d7df0-ffffffff814d7e88: ecryptfs_dir_open (STB_LOCAL)
ffffffff81cd07a1-ffffffff81cd07d1: ecryptfs_dir_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/file.c (0)
Location: fs/ecryptfs/file.c:260
Inline: False
```
**Symbols:**

```
ffffffff81565460-ffffffff81565510: ecryptfs_dir_open (STB_LOCAL)
ffffffff81e83a30-ffffffff81e83a60: ecryptfs_dir_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff81608640)
Location: fs/ecryptfs/file.c:254
Inline: False
```
**Symbols:**

```
ffffffff81608640-ffffffff81608719: ecryptfs_dir_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff81640480)
Location: fs/ecryptfs/file.c:279
Inline: False
```
**Symbols:**

```
ffffffff81640480-ffffffff8164055c: ecryptfs_dir_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff81679a30)
Location: fs/ecryptfs/file.c:279
Inline: False
```
**Symbols:**

```
ffffffff81679a30-ffffffff81679b0f: ecryptfs_dir_open (STB_LOCAL)
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
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/file.c (ffff8000104f2860)
Location: fs/ecryptfs/file.c:260
Inline: True
```
**Symbols:**

```
ffff8000104f2860-ffff8000104f2944: ecryptfs_dir_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/file.c (c06afe98)
Location: fs/ecryptfs/file.c:260
Inline: True
```
**Symbols:**

```
c06afe98-c06aff60: ecryptfs_dir_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/file.c (c000000000632560)
Location: fs/ecryptfs/file.c:260
Inline: True
```
**Symbols:**

```
c000000000632560-c000000000632698: ecryptfs_dir_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/file.c (ffffffe000361f50)
Location: fs/ecryptfs/file.c:260
Inline: True
```
**Symbols:**

```
ffffffe000361f50-ffffffe000362012: ecryptfs_dir_open (STB_LOCAL)
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
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff81409b87)
Location: fs/ecryptfs/file.c:260
Inline: True
```
**Symbols:**

```
ffffffff81409b10-ffffffff81409ba8: ecryptfs_dir_open (STB_LOCAL)
ffffffff81409be1-ffffffff81409c11: ecryptfs_dir_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff813fa607)
Location: fs/ecryptfs/file.c:260
Inline: True
```
**Symbols:**

```
ffffffff813fa590-ffffffff813fa628: ecryptfs_dir_open (STB_LOCAL)
ffffffff813fa661-ffffffff813fa691: ecryptfs_dir_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff81406f07)
Location: fs/ecryptfs/file.c:260
Inline: True
```
**Symbols:**

```
ffffffff81406e90-ffffffff81406f28: ecryptfs_dir_open (STB_LOCAL)
ffffffff81406f61-ffffffff81406f91: ecryptfs_dir_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_dir_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/file.c (ffffffff8141cbc7)
Location: fs/ecryptfs/file.c:260
Inline: True
```
**Symbols:**

```
ffffffff8141cb50-ffffffff8141cbe8: ecryptfs_dir_open (STB_LOCAL)
ffffffff8141cc21-ffffffff8141cc51: ecryptfs_dir_open.cold (STB_LOCAL)
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
