# Function: <code>vfs_getattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_getattr(struct path *path, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812114f0)
Location: fs/stat.c:65
Inline: False
Direct callers:
  - kernel/kexec_file.c:copy_file_from_fd
  - fs/stat.c:vfs_fstat
  - fs/stat.c:vfs_fstatat
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
```
**Symbols:**

```
ffffffff812114f0-ffffffff8121151b: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_getattr(struct path *path, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81237fa0)
Location: fs/stat.c:65
Inline: False
Direct callers:
  - fs/stat.c:vfs_fstatat
  - fs/stat.c:vfs_fstat
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
```
**Symbols:**

```
ffffffff81237fa0-ffffffff81237fcb: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_getattr(struct path *path, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8124ac60)
Location: fs/stat.c:65
Inline: False
Direct callers:
  - fs/stat.c:vfs_fstatat
  - fs/stat.c:vfs_fstat
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
```
**Symbols:**

```
ffffffff8124ac60-ffffffff8124ac8b: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81256720)
Location: fs/stat.c:107
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
```
**Symbols:**

```
ffffffff81256720-ffffffff8125675f: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81278970)
Location: fs/stat.c:108
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
```
**Symbols:**

```
ffffffff81278970-ffffffff812789af: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129f2b0)
Location: fs/stat.c:108
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
```
**Symbols:**

```
ffffffff8129f2b0-ffffffff8129f2ef: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b4290)
Location: fs/stat.c:108
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812b4290-ffffffff812b42cf: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d0ff0)
Location: fs/stat.c:110
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812d0ff0-ffffffff812d1031: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e2b80)
Location: fs/stat.c:110
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812e2b80-ffffffff812e2bc1: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131a805)
Location: fs/stat.c:116
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff81319e90-ffffffff81319ed1: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81325e8e)
Location: fs/stat.c:116
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
Direct callers:
  - fs/init.c:init_stat
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff81325520-ffffffff81325561: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132bf9e)
Location: fs/stat.c:134
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
Direct callers:
  - fs/init.c:init_stat
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
```
**Symbols:**

```
ffffffff8132b660-ffffffff8132b6a1: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8137970e)
Location: fs/stat.c:152
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
Direct callers:
  - fs/init.c:init_stat
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
```
**Symbols:**

```
ffffffff81378dd0-ffffffff81378e11: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f8d5a)
Location: fs/stat.c:152
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
Direct callers:
  - fs/init.c:init_stat
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
```
**Symbols:**

```
ffffffff813f8240-ffffffff813f828b: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81482355)
Location: fs/stat.c:156
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
Direct callers:
  - fs/init.c:init_stat
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
```
**Symbols:**

```
ffffffff81481720-ffffffff8148176b: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b6f65)
Location: fs/stat.c:162
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
Direct callers:
  - fs/init.c:init_stat
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
```
**Symbols:**

```
ffffffff814b6320-ffffffff814b636b: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e928d)
Location: fs/stat.c:165
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
Direct callers:
  - fs/init.c:init_stat
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/loop.c:loop_get_status
```
**Symbols:**

```
ffffffff814e8620-ffffffff814e8696: vfs_getattr (STB_GLOBAL)
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
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038a550)
Location: fs/stat.c:110
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffff80001038a550-ffff80001038a5a8: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c0572744)
Location: fs/stat.c:110
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
c0572744-c057278c: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000481760)
Location: fs/stat.c:110
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
c000000000481760-c000000000481800: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025c4a0)
Location: fs/stat.c:110
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffe00025c4a0-ffffffe00025c4ee: vfs_getattr (STB_GLOBAL)
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
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812db160)
Location: fs/stat.c:110
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812db160-ffffffff812db1a1: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cbde0)
Location: fs/stat.c:110
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812cbde0-ffffffff812cbe21: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d8f70)
Location: fs/stat.c:110
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812d8f70-ffffffff812d8fb1: vfs_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e9e80)
Location: fs/stat.c:110
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812e9e80-ffffffff812e9ec1: vfs_getattr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 request_mask</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int query_flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
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
