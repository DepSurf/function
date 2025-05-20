# Function: <code>fuse_perform_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct file *file, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813191a0)
Location: fs/fuse/file.c:1094
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff813191a0-ffffffff813196c9: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct file *file, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134dc10)
Location: fs/fuse/file.c:1107
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8134dc10-ffffffff8134e222: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct file *file, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81363510)
Location: fs/fuse/file.c:1108
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81363510-ffffffff81363b22: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct file *file, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81377e30)
Location: fs/fuse/file.c:1103
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81377e30-ffffffff813783a2: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139cc00)
Location: fs/fuse/file.c:1111
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8139cc00-ffffffff8139d1dc: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813cc000)
Location: fs/fuse/file.c:1112
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff813cc000-ffffffff813cc5fd: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e5330)
Location: fs/fuse/file.c:1118
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff813e5330-ffffffff813e592a: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814111f0)
Location: fs/fuse/file.c:1130
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff814111f0-ffffffff8141176f: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8142ae00)
Location: fs/fuse/file.c:1213
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8142ae00-ffffffff8142b453: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8147afc0)
Location: fs/fuse/file.c:1186
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff8147afc0-ffffffff8147b1d6: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81495cf0)
Location: fs/fuse/file.c:1211
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff81495cf0-ffffffff81495f09: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8149ad50)
Location: fs/fuse/file.c:1223
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff8149ad50-ffffffff8149af98: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f2790)
Location: fs/fuse/file.c:1225
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff814f2790-ffffffff814f29d8: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff815821a0)
Location: fs/fuse/file.c:1245
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff815821a0-ffffffff815823c8: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81627ff0)
Location: fs/fuse/file.c:1245
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff81627ff0-ffffffff81628213: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct iov_iter *ii);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816603d0)
Location: fs/fuse/file.c:1246
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff816603d0-ffffffff8166061d: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct iov_iter *ii);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8169a230)
Location: fs/fuse/file.c:1247
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
```
**Symbols:**

```
ffffffff8169a230-ffffffff8169a47d: fuse_perform_write (STB_LOCAL)
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
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050ecd0)
Location: fs/fuse/file.c:1213
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffff80001050ecd0-ffff80001050f300: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06ca530)
Location: fs/fuse/file.c:1213
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
c06ca530-c06cab50: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c000000000656020)
Location: fs/fuse/file.c:1213
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
c000000000656020-c0000000006567e8: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe0003797ba)
Location: fs/fuse/file.c:1213
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffe0003797ba-ffffffe000379cdc: fuse_perform_write (STB_LOCAL)
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
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814233e0)
Location: fs/fuse/file.c:1213
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff814233e0-ffffffff81423a33: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81413e60)
Location: fs/fuse/file.c:1213
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81413e60-ffffffff814144b3: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141f580)
Location: fs/fuse/file.c:1213
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8141f580-ffffffff8141fbd3: fuse_perform_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t fuse_perform_write(struct kiocb *iocb, struct address_space *mapping, struct iov_iter *ii, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81436300)
Location: fs/fuse/file.c:1213
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81436300-ffffffff81436953: fuse_perform_write (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kiocb *iocb</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *file</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct address_space *mapping</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t pos</code>
</li>
<li>
<b>Param reordered. </b>
<code>iocb, mapping, ii, pos</code> ➡️ <code>iocb, ii</code>
</li>
</ul>
</details>
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
