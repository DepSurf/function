# Function: <code>__kernfs_fh_to_dentry</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *__kernfs_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, bool get_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813ccb10)
Location: fs/kernfs/mount.c:71
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff813ccb10-ffffffff813ccbbf: __kernfs_fh_to_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *__kernfs_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, bool get_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813de760)
Location: fs/kernfs/mount.c:71
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff813de760-ffffffff813de80f: __kernfs_fh_to_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *__kernfs_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, bool get_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813e54b0)
Location: fs/kernfs/mount.c:71
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff813e54b0-ffffffff813e555f: __kernfs_fh_to_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *__kernfs_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, bool get_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81437080)
Location: fs/kernfs/mount.c:71
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff81437080-ffffffff8143712f: __kernfs_fh_to_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *__kernfs_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, bool get_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff814b1c40)
Location: fs/kernfs/mount.c:71
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff814b1c40-ffffffff814b1d2b: __kernfs_fh_to_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *__kernfs_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, bool get_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81548710)
Location: fs/kernfs/mount.c:72
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff81548710-ffffffff815487fb: __kernfs_fh_to_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *__kernfs_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, bool get_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff815802d0)
Location: fs/kernfs/mount.c:72
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
```
**Symbols:**

```
ffffffff815802d0-ffffffff815803a7: __kernfs_fh_to_dentry (STB_LOCAL)
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
In fs/kernfs/mount.c (ffffffff815b8d15)
Location: fs/kernfs/mount.c:82
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
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
</ul>
