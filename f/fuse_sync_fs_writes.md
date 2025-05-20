# Function: <code>fuse_sync_fs_writes</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_sync_fs_writes(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f5d40)
Location: fs/fuse/inode.c:516
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sync_fs
```
**Symbols:**

```
ffffffff814f5d40-ffffffff814f5e99: fuse_sync_fs_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_sync_fs_writes(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81584b10)
Location: fs/fuse/inode.c:554
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sync_fs
```
**Symbols:**

```
ffffffff81584b10-ffffffff81584ca7: fuse_sync_fs_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_sync_fs_writes(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162ac80)
Location: fs/fuse/inode.c:567
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sync_fs
```
**Symbols:**

```
ffffffff8162ac80-ffffffff8162ae17: fuse_sync_fs_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_sync_fs_writes(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81662ea0)
Location: fs/fuse/inode.c:567
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sync_fs
```
**Symbols:**

```
ffffffff81662ea0-ffffffff81663035: fuse_sync_fs_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_sync_fs_writes(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169ca40)
Location: fs/fuse/inode.c:636
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sync_fs
```
**Symbols:**

```
ffffffff8169ca40-ffffffff8169cba2: fuse_sync_fs_writes (STB_LOCAL)
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
