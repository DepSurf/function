# Function: <code>exportfs_decode_fh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8130cc50)
Location: fs/exportfs/expfs.c:412
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff8130cc50-ffffffff8130cf30: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81340f30)
Location: fs/exportfs/expfs.c:416
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff81340f30-ffffffff81341207: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81356cd0)
Location: fs/exportfs/expfs.c:416
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff81356cd0-ffffffff81357057: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8136b8d0)
Location: fs/exportfs/expfs.c:418
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff8136b8d0-ffffffff8136bc59: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81390440)
Location: fs/exportfs/expfs.c:418
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff81390440-ffffffff81390836: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (0)
Location: fs/exportfs/expfs.c:418
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff813bf835-ffffffff813bf84d: exportfs_decode_fh.cold.6 (STB_LOCAL)
ffffffff813bf4e0-ffffffff813bf835: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (0)
Location: fs/exportfs/expfs.c:419
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff813d8e3b-ffffffff813d8e53: exportfs_decode_fh.cold.6 (STB_LOCAL)
ffffffff813d8b40-ffffffff813d8e3b: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (0)
Location: fs/exportfs/expfs.c:420
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff8140379a-ffffffff814037b2: exportfs_decode_fh.cold (STB_LOCAL)
ffffffff81403500-ffffffff8140379a: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (0)
Location: fs/exportfs/expfs.c:420
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff8141d74c-ffffffff8141d764: exportfs_decode_fh.cold (STB_LOCAL)
ffffffff8141d410-ffffffff8141d74c: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (0)
Location: fs/exportfs/expfs.c:420
Inline: False
Direct callers:
  - fs/fhandle.c:handle_to_path
```
**Symbols:**

```
ffffffff8146c32c-ffffffff8146c344: exportfs_decode_fh.cold (STB_LOCAL)
ffffffff8146bf70-ffffffff8146c32c: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff814869f0)
Location: fs/exportfs/expfs.c:568
Inline: False
Direct callers:
  - fs/fhandle.c:handle_to_path
```
**Symbols:**

```
ffffffff814869f0-ffffffff81486a27: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8148c420)
Location: fs/exportfs/expfs.c:568
Inline: False
Direct callers:
  - fs/fhandle.c:handle_to_path
```
**Symbols:**

```
ffffffff8148c420-ffffffff8148c457: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff814e3c30)
Location: fs/exportfs/expfs.c:568
Inline: False
Direct callers:
  - fs/fhandle.c:handle_to_path
```
**Symbols:**

```
ffffffff814e3c30-ffffffff814e3c67: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81572020)
Location: fs/exportfs/expfs.c:569
Inline: False
Direct callers:
  - fs/fhandle.c:handle_to_path
```
**Symbols:**

```
ffffffff81572020-ffffffff8157208d: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81617490)
Location: fs/exportfs/expfs.c:568
Inline: False
Direct callers:
  - fs/fhandle.c:handle_to_path
```
**Symbols:**

```
ffffffff81617490-ffffffff816174fd: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8164f560)
Location: fs/exportfs/expfs.c:593
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff8164f560-ffffffff8164f5cd: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81688b40)
Location: fs/exportfs/expfs.c:577
Inline: False
Direct callers:
  - fs/fhandle.c:handle_to_path
```
**Symbols:**

```
ffffffff81688b40-ffffffff81688bad: exportfs_decode_fh (STB_GLOBAL)
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
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffff8000104ff170)
Location: fs/exportfs/expfs.c:420
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffff8000104ff170-ffff8000104ff40c: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (c06bc104)
Location: fs/exportfs/expfs.c:420
Inline: False
Direct callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
**Symbols:**

```
c06bc104-c06bc388: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (c000000000642860)
Location: fs/exportfs/expfs.c:420
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
c000000000642860-c000000000642c10: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffe00036cefa)
Location: fs/exportfs/expfs.c:420
Inline: False
Direct callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
**Symbols:**

```
ffffffe00036cefa-ffffffe00036d0e4: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (0)
Location: fs/exportfs/expfs.c:420
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff81415d2c-ffffffff81415d44: exportfs_decode_fh.cold (STB_LOCAL)
ffffffff814159f0-ffffffff81415d2c: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (0)
Location: fs/exportfs/expfs.c:420
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff814067ac-ffffffff814067c4: exportfs_decode_fh.cold (STB_LOCAL)
ffffffff81406470-ffffffff814067ac: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (0)
Location: fs/exportfs/expfs.c:420
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff814130ac-ffffffff814130c4: exportfs_decode_fh.cold (STB_LOCAL)
ffffffff81412d70-ffffffff814130ac: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dentry *exportfs_decode_fh(struct vfsmount *mnt, struct fid *fid, int fh_len, int fileid_type, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (0)
Location: fs/exportfs/expfs.c:420
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff81428d2c-ffffffff81428d44: exportfs_decode_fh.cold (STB_LOCAL)
ffffffff814289f0-ffffffff81428d2c: exportfs_decode_fh (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
