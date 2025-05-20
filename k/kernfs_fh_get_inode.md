# Function: <code>kernfs_fh_get_inode</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *kernfs_fh_get_inode(struct super_block *sb, u64 ino, u32 generation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812fcec0)
Location: fs/kernfs/mount.c:87
Inline: False
```
**Symbols:**

```
ffffffff812fcec0-ffffffff812fcf42: kernfs_fh_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *kernfs_fh_get_inode(struct super_block *sb, u64 ino, u32 generation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8132aad0)
Location: fs/kernfs/mount.c:87
Inline: False
```
**Symbols:**

```
ffffffff8132aad0-ffffffff8132ab45: kernfs_fh_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *kernfs_fh_get_inode(struct super_block *sb, u64 ino, u32 generation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81341e20)
Location: fs/kernfs/mount.c:87
Inline: False
```
**Symbols:**

```
ffffffff81341e20-ffffffff81341e95: kernfs_fh_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *kernfs_fh_get_inode(struct super_block *sb, u64 ino, u32 generation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8136a240)
Location: fs/kernfs/mount.c:75
Inline: False
```
**Symbols:**

```
ffffffff8136a240-ffffffff8136a2b4: kernfs_fh_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *kernfs_fh_get_inode(struct super_block *sb, u64 ino, u32 generation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81382430)
Location: fs/kernfs/mount.c:75
Inline: False
```
**Symbols:**

```
ffffffff81382430-ffffffff813824a4: kernfs_fh_get_inode (STB_LOCAL)
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
struct inode *kernfs_fh_get_inode(struct super_block *sb, u64 ino, u32 generation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffff8000104507f0)
Location: fs/kernfs/mount.c:75
Inline: False
```
**Symbols:**

```
ffff8000104507f0-ffff800010450884: kernfs_fh_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *kernfs_fh_get_inode(struct super_block *sb, u64 ino, u32 generation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c0613800)
Location: fs/kernfs/mount.c:75
Inline: False
```
**Symbols:**

```
c0613800-c0613898: kernfs_fh_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *kernfs_fh_get_inode(struct super_block *sb, u64 ino, u32 generation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c000000000568990)
Location: fs/kernfs/mount.c:75
Inline: False
```
**Symbols:**

```
c000000000568990-c000000000568aa4: kernfs_fh_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *kernfs_fh_get_inode(struct super_block *sb, u64 ino, u32 generation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffe0002e37b4)
Location: fs/kernfs/mount.c:75
Inline: False
```
**Symbols:**

```
ffffffe0002e37b4-ffffffe0002e3834: kernfs_fh_get_inode (STB_LOCAL)
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
struct inode *kernfs_fh_get_inode(struct super_block *sb, u64 ino, u32 generation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8137aa10)
Location: fs/kernfs/mount.c:75
Inline: False
```
**Symbols:**

```
ffffffff8137aa10-ffffffff8137aa84: kernfs_fh_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *kernfs_fh_get_inode(struct super_block *sb, u64 ino, u32 generation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8136b4e0)
Location: fs/kernfs/mount.c:75
Inline: False
```
**Symbols:**

```
ffffffff8136b4e0-ffffffff8136b554: kernfs_fh_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *kernfs_fh_get_inode(struct super_block *sb, u64 ino, u32 generation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813784e0)
Location: fs/kernfs/mount.c:75
Inline: False
```
**Symbols:**

```
ffffffff813784e0-ffffffff81378554: kernfs_fh_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *kernfs_fh_get_inode(struct super_block *sb, u64 ino, u32 generation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8138bf90)
Location: fs/kernfs/mount.c:75
Inline: False
```
**Symbols:**

```
ffffffff8138bf90-ffffffff8138c004: kernfs_fh_get_inode (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
