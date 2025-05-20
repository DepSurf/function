# Function: <code>fuse_sync_bucket_alloc</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f6886)
Location: fs/fuse/inode.c:503
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_sync_fs_writes
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
In fs/fuse/inode.c (ffffffff815866b6)
Location: fs/fuse/inode.c:541
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162c946)
Location: fs/fuse/inode.c:554
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81664b76)
Location: fs/fuse/inode.c:554
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fuse_sync_bucket *fuse_sync_bucket_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169c9a0)
Location: fs/fuse/inode.c:623
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
**Symbols:**

```
ffffffff8169c9a0-ffffffff8169ca27: fuse_sync_bucket_alloc (STB_LOCAL)
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
</ul>
