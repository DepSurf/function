# Function: <code>generic_file_direct_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118f060)
Location: mm/filemap.c:2399
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8118f060-ffffffff8118f1dd: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a2670)
Location: mm/filemap.c:2576
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff811a2670-ffffffff811a27da: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b24b0)
Location: mm/filemap.c:2692
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff811b24b0-ffffffff811b261a: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b9130)
Location: mm/filemap.c:2829
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff811b9130-ffffffff811b9285: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cf5b0)
Location: mm/filemap.c:2999
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff811cf5b0-ffffffff811cf710: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811f06c0)
Location: mm/filemap.c:2999
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff811f06c0-ffffffff811f0826: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81200eb0)
Location: mm/filemap.c:3068
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81200eb0-ffffffff81201016: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218ac0)
Location: mm/filemap.c:3187
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81218ac0-ffffffff81218c21: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226370)
Location: mm/filemap.c:3144
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81226370-ffffffff812264d1: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812512c0)
Location: mm/filemap.c:3174
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff812512c0-ffffffff8125147e: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125ca90)
Location: mm/filemap.c:3268
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff8125ca90-ffffffff8125cc51: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81261710)
Location: mm/filemap.c:3515
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff81261710-ffffffff812618e0: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129a000)
Location: mm/filemap.c:3632
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff8129a000-ffffffff8129a1d9: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f70b0)
Location: mm/filemap.c:3660
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff812f70b0-ffffffff812f724e: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81360930)
Location: mm/filemap.c:3654
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff81360930-ffffffff81360aca: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81392e60)
Location: mm/filemap.c:3833
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff81392e60-ffffffff81392f54: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813bcb10)
Location: mm/filemap.c:3840
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff813bcb10-ffffffff813bcc04: generic_file_direct_write (STB_GLOBAL)
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
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b3680)
Location: mm/filemap.c:3144
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffff8000102b3680-ffff8000102b3808: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e0864)
Location: mm/filemap.c:3144
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
c04e0864-c04e0a64: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c00000000036a290)
Location: mm/filemap.c:3144
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
c00000000036a290-c00000000036a4a0: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d8d46)
Location: mm/filemap.c:3144
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffe0001d8d46-ffffffe0001d8e78: generic_file_direct_write (STB_GLOBAL)
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
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121e9c0)
Location: mm/filemap.c:3144
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8121e9c0-ffffffff8121eb21: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81211b80)
Location: mm/filemap.c:3144
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81211b80-ffffffff81211ce1: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c760)
Location: mm/filemap.c:3144
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8121c760-ffffffff8121c8c1: generic_file_direct_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t generic_file_direct_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122b7f0)
Location: mm/filemap.c:3144
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8122b7f0-ffffffff8122b951: generic_file_direct_write (STB_GLOBAL)
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
<b>Param removed. </b>
<code>loff_t pos</code>
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
