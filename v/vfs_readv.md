# Function: <code>vfs_readv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120cbf0)
Location: fs/read_write.c:850
Inline: False
Direct callers:
  - fs/read_write.c:SyS_readv
  - fs/read_write.c:SyS_preadv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff8120cbf0-ffffffff8120cc31: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81233020)
Location: fs/read_write.c:885
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff81233020-ffffffff81233064: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81245ba0)
Location: fs/read_write.c:914
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff81245ba0-ffffffff81245be4: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81250f80)
Location: fs/read_write.c:970
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff81250f80-ffffffff81251042: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81274630)
Location: fs/read_write.c:975
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff81274630-ffffffff812746f2: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129b4a0)
Location: fs/read_write.c:1002
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff8129b4a0-ffffffff8129b543: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812b03a0)
Location: fs/read_write.c:999
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff812b03a0-ffffffff812b0443: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cccc0)
Location: fs/read_write.c:1013
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff812cccc0-ffffffff812ccd66: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812de6e0)
Location: fs/read_write.c:1013
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff812de6e0-ffffffff812de786: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81315460)
Location: fs/read_write.c:1097
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
```
**Symbols:**

```
ffffffff81315460-ffffffff8131550d: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131e250)
Location: fs/read_write.c:913
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
```
**Symbols:**

```
ffffffff8131e250-ffffffff8131e2fd: vfs_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81323c90)
Location: fs/read_write.c:911
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
```
**Symbols:**

```
ffffffff81323c90-ffffffff81323d35: vfs_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813718b0)
Location: fs/read_write.c:902
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
```
**Symbols:**

```
ffffffff813718b0-ffffffff81371955: vfs_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813ef8c0)
Location: fs/read_write.c:913
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
```
**Symbols:**

```
ffffffff813ef8c0-ffffffff813ef9ad: vfs_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81477e90)
Location: fs/read_write.c:906
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
```
**Symbols:**

```
ffffffff81477e90-ffffffff81477f7d: vfs_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ac420)
Location: fs/read_write.c:905
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
```
**Symbols:**

```
ffffffff814ac420-ffffffff814ac50d: vfs_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ddd20)
Location: fs/read_write.c:904
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_preadv
  - fs/read_write.c:__x64_sys_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
```
**Symbols:**

```
ffffffff814ddd20-ffffffff814ddf74: vfs_readv (STB_LOCAL)
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
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010384c88)
Location: fs/read_write.c:1013
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffff800010384c88-ffff800010384d44: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056d630)
Location: fs/read_write.c:1013
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
c056d630-c056d6d8: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c00000000047ac70)
Location: fs/read_write.c:1013
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
c00000000047ac70-c00000000047ad44: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe0002578e8)
Location: fs/read_write.c:1013
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffe0002578e8-ffffffe00025796a: vfs_readv (STB_GLOBAL)
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
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d6cc0)
Location: fs/read_write.c:1013
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff812d6cc0-ffffffff812d6d66: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c7940)
Location: fs/read_write.c:1013
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff812c7940-ffffffff812c79e6: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4ad0)
Location: fs/read_write.c:1013
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff812d4ad0-ffffffff812d4b76: vfs_readv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t vfs_readv(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e5930)
Location: fs/read_write.c:1013
Inline: False
Direct callers:
  - fs/read_write.c:do_preadv
  - fs/read_write.c:do_readv
  - fs/read_write.c:do_readv
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff812e5930-ffffffff812e59d6: vfs_readv (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int flags</code> ➡️ <code>rwf_t flags</code>
</li>
</ul>
</details>
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
