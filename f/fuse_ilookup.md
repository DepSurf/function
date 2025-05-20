# Function: <code>fuse_ilookup</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *fuse_ilookup(struct fuse_conn *fc, u64 nodeid, struct fuse_mount **fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81499950)
Location: fs/fuse/inode.c:369
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81499950-ffffffff814999e0: fuse_ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *fuse_ilookup(struct fuse_conn *fc, u64 nodeid, struct fuse_mount **fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149eb80)
Location: fs/fuse/inode.c:369
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff8149eb80-ffffffff8149ec10: fuse_ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *fuse_ilookup(struct fuse_conn *fc, u64 nodeid, struct fuse_mount **fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f6de0)
Location: fs/fuse/inode.c:371
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff814f6de0-ffffffff814f6e70: fuse_ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *fuse_ilookup(struct fuse_conn *fc, u64 nodeid, struct fuse_mount **fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81586c50)
Location: fs/fuse/inode.c:409
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81586c50-ffffffff81586cfb: fuse_ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *fuse_ilookup(struct fuse_conn *fc, u64 nodeid, struct fuse_mount **fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162ced0)
Location: fs/fuse/inode.c:416
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff8162ced0-ffffffff8162cf7b: fuse_ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *fuse_ilookup(struct fuse_conn *fc, u64 nodeid, struct fuse_mount **fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81665100)
Location: fs/fuse/inode.c:416
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81665100-ffffffff816651ab: fuse_ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *fuse_ilookup(struct fuse_conn *fc, u64 nodeid, struct fuse_mount **fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169f400)
Location: fs/fuse/inode.c:485
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff8169f400-ffffffff8169f4ab: fuse_ilookup (STB_GLOBAL)
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
