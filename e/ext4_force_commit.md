# Function: <code>ext4_force_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812be530)
Location: fs/ext4/super.c:4456
Inline: False
Direct callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff812be530-ffffffff812be55c: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ede70)
Location: fs/ext4/super.c:4620
Inline: False
Direct callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff812ede70-ffffffff812ede9c: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81303e30)
Location: fs/ext4/super.c:4746
Inline: False
Direct callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff81303e30-ffffffff81303e5c: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81338f90)
Location: fs/ext4/super.c:4854
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81338f90-ffffffff81338fbd: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8135ccb0)
Location: fs/ext4/super.c:4863
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8135ccb0-ffffffff8135ccdd: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8138b830)
Location: fs/ext4/super.c:4978
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8138b830-ffffffff8138b85c: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813a4390)
Location: fs/ext4/super.c:5042
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813a4390-ffffffff813a43bc: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce590)
Location: fs/ext4/super.c:5132
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813ce590-ffffffff813ce5bc: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e7c70)
Location: fs/ext4/super.c:5163
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813e7c70-ffffffff813e7c9c: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81434730)
Location: fs/ext4/super.c:5350
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_shutdown
```
**Symbols:**

```
ffffffff81434730-ffffffff8143475c: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144d7e0)
Location: fs/ext4/super.c:5676
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_shutdown
```
**Symbols:**

```
ffffffff8144d7e0-ffffffff8144d80c: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814532a0)
Location: fs/ext4/super.c:5724
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_shutdown
```
**Symbols:**

```
ffffffff814532a0-ffffffff814532cc: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814a39b0)
Location: fs/ext4/super.c:5586
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_shutdown
```
**Symbols:**

```
ffffffff814a39b0-ffffffff814a39dc: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8152ae60)
Location: fs/ext4/super.c:6042
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_shutdown
```
**Symbols:**

```
ffffffff8152ae60-ffffffff8152ae9c: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c9cf0)
Location: fs/ext4/super.c:6194
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_shutdown
```
**Symbols:**

```
ffffffff815c9cf0-ffffffff815c9d2c: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81601bb0)
Location: fs/ext4/super.c:6283
Inline: False
Direct callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_force_shutdown
```
**Symbols:**

```
ffffffff81601bb0-ffffffff81601bec: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8163a950)
Location: fs/ext4/super.c:6311
Inline: False
Direct callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_force_shutdown
```
**Symbols:**

```
ffffffff8163a950-ffffffff8163a982: ext4_force_commit (STB_GLOBAL)
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
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104c0b68)
Location: fs/ext4/super.c:5163
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffff8000104c0b68-ffff8000104c0bc8: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0684ae4)
Location: fs/ext4/super.c:5163
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c0684ae4-c0684b24: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f7700)
Location: fs/ext4/super.c:5163
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c0000000005f7700-c0000000005f7768: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe00033c526)
Location: fs/ext4/super.c:5163
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffe00033c526-ffffffe00033c56e: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e0250)
Location: fs/ext4/super.c:5163
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813e0250-ffffffff813e027c: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d0cd0)
Location: fs/ext4/super.c:5163
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813d0cd0-ffffffff813d0cfc: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dd5d0)
Location: fs/ext4/super.c:5163
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813dd5d0-ffffffff813dd5fc: ext4_force_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_force_commit(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813f2a00)
Location: fs/ext4/super.c:5163
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813f2a00-ffffffff813f2a2c: ext4_force_commit (STB_GLOBAL)
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
