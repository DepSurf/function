# Function: <code>fuse_priv_ioctl_prepare</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff814a21a5)
Location: fs/fuse/ioctl.c:403
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff814fa245)
Location: fs/fuse/ioctl.c:406
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff8158a504)
Location: fs/fuse/ioctl.c:417
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fuse_file *fuse_priv_ioctl_prepare(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff8162fdf0)
Location: fs/fuse/ioctl.c:417
Inline: False
Direct callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff8162fdf0-ffffffff8162fe9e: fuse_priv_ioctl_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fuse_file *fuse_priv_ioctl_prepare(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff81667ff0)
Location: fs/fuse/ioctl.c:422
Inline: False
Direct callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff81667ff0-ffffffff8166809e: fuse_priv_ioctl_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fuse_file *fuse_priv_ioctl_prepare(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff816a22f0)
Location: fs/fuse/ioctl.c:422
Inline: False
Direct callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff816a22f0-ffffffff816a239e: fuse_priv_ioctl_prepare (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
