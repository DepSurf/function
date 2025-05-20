# Function: <code>ext4_fc_commit</code>

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
int ext4_fc_commit(journal_t *journal, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81457120)
Location: fs/ext4/fast_commit.c:1137
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
```
**Symbols:**

```
ffffffff81457120-ffffffff81457423: ext4_fc_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_fc_commit(journal_t *journal, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145cad0)
Location: fs/ext4/fast_commit.c:1133
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
```
**Symbols:**

```
ffffffff8145cad0-ffffffff8145cdbd: ext4_fc_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_fc_commit(journal_t *journal, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814b0320)
Location: fs/ext4/fast_commit.c:1123
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
```
**Symbols:**

```
ffffffff814b0320-ffffffff814b04e2: ext4_fc_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_fc_commit(journal_t *journal, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81538be0)
Location: fs/ext4/fast_commit.c:1199
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
```
**Symbols:**

```
ffffffff81538be0-ffffffff81538dd9: ext4_fc_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_fc_commit(journal_t *journal, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d6eb0)
Location: fs/ext4/fast_commit.c:1189
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
```
**Symbols:**

```
ffffffff815d6eb0-ffffffff815d70a9: ext4_fc_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_fc_commit(journal_t *journal, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160ea80)
Location: fs/ext4/fast_commit.c:1189
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_writepages
```
**Symbols:**

```
ffffffff8160ea80-ffffffff8160ec79: ext4_fc_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_fc_commit(journal_t *journal, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81647840)
Location: fs/ext4/fast_commit.c:1189
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_do_writepages
```
**Symbols:**

```
ffffffff81647840-ffffffff81647a39: ext4_fc_commit (STB_GLOBAL)
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
