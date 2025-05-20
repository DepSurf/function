# Function: <code>configfs_lookup</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812e0d50)
Location: fs/configfs/dir.c:440
Inline: True
```
**Symbols:**

```
ffffffff812e0d50-ffffffff812e0ea5: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813056e0)
Location: fs/configfs/dir.c:440
Inline: True
```
**Symbols:**

```
ffffffff813056e0-ffffffff81305835: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81332580)
Location: fs/configfs/dir.c:440
Inline: True
```
**Symbols:**

```
ffffffff81332580-ffffffff813326fe: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81349ca0)
Location: fs/configfs/dir.c:440
Inline: True
```
**Symbols:**

```
ffffffff81349ca0-ffffffff81349e1e: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (ffffffff813727c7)
Location: fs/configfs/dir.c:456
Inline: True
```
**Symbols:**

```
ffffffff81372750-ffffffff813728de: configfs_lookup (STB_LOCAL)
ffffffff81373637-ffffffff8137365d: configfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8138a030)
Location: fs/configfs/dir.c:451
Inline: True
```
**Symbols:**

```
ffffffff8138a030-ffffffff8138a1dc: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813d5c10)
Location: fs/configfs/dir.c:451
Inline: False
```
**Symbols:**

```
ffffffff813d5c10-ffffffff813d5dc8: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813e78e0)
Location: fs/configfs/dir.c:452
Inline: False
```
**Symbols:**

```
ffffffff813e78e0-ffffffff813e7a98: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813ee500)
Location: fs/configfs/dir.c:450
Inline: False
```
**Symbols:**

```
ffffffff813ee500-ffffffff813ee6bb: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81440420)
Location: fs/configfs/dir.c:428
Inline: False
```
**Symbols:**

```
ffffffff81440420-ffffffff814405eb: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff814bb200)
Location: fs/configfs/dir.c:428
Inline: False
```
**Symbols:**

```
ffffffff814bb200-ffffffff814bb3dc: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81552b40)
Location: fs/configfs/dir.c:430
Inline: False
```
**Symbols:**

```
ffffffff81552b40-ffffffff81552d1c: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8158a8c0)
Location: fs/configfs/dir.c:430
Inline: False
```
**Symbols:**

```
ffffffff8158a8c0-ffffffff8158aa9c: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815c3590)
Location: fs/configfs/dir.c:430
Inline: False
```
**Symbols:**

```
ffffffff815c3590-ffffffff815c3772: configfs_lookup (STB_LOCAL)
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
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff80001045afd8)
Location: fs/configfs/dir.c:451
Inline: True
```
**Symbols:**

```
ffff80001045afd8-ffff80001045b254: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061dad0)
Location: fs/configfs/dir.c:451
Inline: True
```
**Symbols:**

```
c061dad0-c061dcd8: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c0000000005784d0)
Location: fs/configfs/dir.c:451
Inline: True
```
**Symbols:**

```
c0000000005784d0-c0000000005788ec: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002ece0c)
Location: fs/configfs/dir.c:451
Inline: True
```
**Symbols:**

```
ffffffe0002ece0c-ffffffe0002ecfd6: configfs_lookup (STB_LOCAL)
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
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81382610)
Location: fs/configfs/dir.c:451
Inline: True
```
**Symbols:**

```
ffffffff81382610-ffffffff813827bc: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813730a0)
Location: fs/configfs/dir.c:451
Inline: True
```
**Symbols:**

```
ffffffff813730a0-ffffffff8137324c: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813800e0)
Location: fs/configfs/dir.c:451
Inline: True
```
**Symbols:**

```
ffffffff813800e0-ffffffff8138028c: configfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dentry *configfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81393bd0)
Location: fs/configfs/dir.c:451
Inline: True
```
**Symbols:**

```
ffffffff81393bd0-ffffffff81393d7c: configfs_lookup (STB_LOCAL)
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
