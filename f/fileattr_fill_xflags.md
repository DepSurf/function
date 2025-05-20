# Function: <code>fileattr_fill_xflags</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
void fileattr_fill_xflags(struct fileattr *fa, u32 xflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8133c870)
Location: fs/ioctl.c:671
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff8133c870-ffffffff8133c8ef: fileattr_fill_xflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fileattr_fill_xflags(struct fileattr *fa, u32 xflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8138a570)
Location: fs/ioctl.c:468
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff8138a570-ffffffff8138a5ef: fileattr_fill_xflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fileattr_fill_xflags(struct fileattr *fa, u32 xflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8140b870)
Location: fs/ioctl.c:464
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff8140b870-ffffffff8140b8f7: fileattr_fill_xflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fileattr_fill_xflags(struct fileattr *fa, u32 xflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81496220)
Location: fs/ioctl.c:464
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff81496220-ffffffff814962a7: fileattr_fill_xflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fileattr_fill_xflags(struct fileattr *fa, u32 xflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814cb370)
Location: fs/ioctl.c:464
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff814cb370-ffffffff814cb3f7: fileattr_fill_xflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fileattr_fill_xflags(struct fileattr *fa, u32 xflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814fdc20)
Location: fs/ioctl.c:465
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
**Symbols:**

```
ffffffff814fdc20-ffffffff814fdca7: fileattr_fill_xflags (STB_GLOBAL)
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
