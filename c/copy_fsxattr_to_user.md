# Function: <code>copy_fsxattr_to_user</code>

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
int copy_fsxattr_to_user(const struct fileattr *fa, struct fsxattr *ufa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8133ca90)
Location: fs/ioctl.c:750
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8133ca90-ffffffff8133cafc: copy_fsxattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_fsxattr_to_user(const struct fileattr *fa, struct fsxattr *ufa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8138a790)
Location: fs/ioctl.c:547
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8138a790-ffffffff8138a7fc: copy_fsxattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_fsxattr_to_user(const struct fileattr *fa, struct fsxattr *ufa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8140b7f0)
Location: fs/ioctl.c:543
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8140b7f0-ffffffff8140b868: copy_fsxattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_fsxattr_to_user(const struct fileattr *fa, struct fsxattr *ufa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81496190)
Location: fs/ioctl.c:543
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff81496190-ffffffff81496208: copy_fsxattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_fsxattr_to_user(const struct fileattr *fa, struct fsxattr *ufa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814cb1d0)
Location: fs/ioctl.c:543
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff814cb1d0-ffffffff814cb248: copy_fsxattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_fsxattr_to_user(const struct fileattr *fa, struct fsxattr *ufa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814fda80)
Location: fs/ioctl.c:544
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff814fda80-ffffffff814fdaf8: copy_fsxattr_to_user (STB_GLOBAL)
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
