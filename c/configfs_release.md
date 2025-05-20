# Function: <code>configfs_release</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff812de3e0)
Location: fs/configfs/file.c:451
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff812de3e0-ffffffff812de445: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff81302d20)
Location: fs/configfs/file.c:451
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff81302d20-ffffffff81302d85: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff81330c70)
Location: fs/configfs/file.c:451
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff81330c70-ffffffff81330cd5: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff81348060)
Location: fs/configfs/file.c:451
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff81348060-ffffffff813480c5: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff81370510)
Location: fs/configfs/file.c:447
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff81370510-ffffffff8137054b: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff813889f0)
Location: fs/configfs/file.c:447
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff813889f0-ffffffff81388a2b: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff813d3f48)
Location: fs/configfs/file.c:447
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff813d3730-ffffffff813d376d: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff813e5c88)
Location: fs/configfs/file.c:445
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff813e5470-ffffffff813e54ad: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff813ec8b3)
Location: fs/configfs/file.c:443
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff813ec080-ffffffff813ec0bd: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff8143e7da)
Location: fs/configfs/file.c:379
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff8143de40-ffffffff8143de7d: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff814ba10a)
Location: fs/configfs/file.c:379
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff814b9750-ffffffff814b9792: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff8155192a)
Location: fs/configfs/file.c:379
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff81550ef0-ffffffff81550f32: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff8158964a)
Location: fs/configfs/file.c:379
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff81588bd0-ffffffff81588c12: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff815c225a)
Location: fs/configfs/file.c:379
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff815c17a0-ffffffff815c17e2: configfs_release (STB_LOCAL)
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
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffff800010458dc0)
Location: fs/configfs/file.c:447
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffff800010458dc0-ffff800010458e0c: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (c061aaa8)
Location: fs/configfs/file.c:447
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
c061aaa8-c061aaec: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (c000000000573a60)
Location: fs/configfs/file.c:447
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
c000000000573a60-c000000000573acc: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffe0002e9d34)
Location: fs/configfs/file.c:447
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffe0002e9d34-ffffffe0002e9d7a: configfs_release (STB_LOCAL)
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
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff81380fd0)
Location: fs/configfs/file.c:447
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff81380fd0-ffffffff8138100b: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff81371a60)
Location: fs/configfs/file.c:447
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff81371a60-ffffffff81371a9b: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff8137eaa0)
Location: fs/configfs/file.c:447
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff8137eaa0-ffffffff8137eadb: configfs_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int configfs_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff813925a0)
Location: fs/configfs/file.c:447
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release_bin_file
```
**Symbols:**

```
ffffffff813925a0-ffffffff813925db: configfs_release (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
