# Function: <code>exportfs_decode_fh_raw</code>

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
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dentry *exportfs_decode_fh_raw(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (0)
Location: fs/exportfs/expfs.c:421
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81bef71e-ffffffff81bef736: exportfs_decode_fh_raw.cold (STB_LOCAL)
ffffffff814866c0-ffffffff814869ec: exportfs_decode_fh_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dentry *exportfs_decode_fh_raw(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (0)
Location: fs/exportfs/expfs.c:421
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81be17c6-ffffffff81be17de: exportfs_decode_fh_raw.cold (STB_LOCAL)
ffffffff8148c120-ffffffff8148c411: exportfs_decode_fh_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *exportfs_decode_fh_raw(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (0)
Location: fs/exportfs/expfs.c:421
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81cd1fc4-ffffffff81cd1fdc: exportfs_decode_fh_raw.cold (STB_LOCAL)
ffffffff814e3930-ffffffff814e3c21: exportfs_decode_fh_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dentry *exportfs_decode_fh_raw(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (0)
Location: fs/exportfs/expfs.c:421
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81e850d1-ffffffff81e850e9: exportfs_decode_fh_raw.cold (STB_LOCAL)
ffffffff81571d00-ffffffff81572019: exportfs_decode_fh_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh_raw(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81617130)
Location: fs/exportfs/expfs.c:420
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81617130-ffffffff81617475: exportfs_decode_fh_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh_raw(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8164f220)
Location: fs/exportfs/expfs.c:445
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff8164f220-ffffffff8164f549: exportfs_decode_fh_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh_raw(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81688760)
Location: fs/exportfs/expfs.c:429
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81688760-ffffffff81688b28: exportfs_decode_fh_raw (STB_GLOBAL)
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
