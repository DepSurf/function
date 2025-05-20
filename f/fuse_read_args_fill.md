# Function: <code>fuse_read_args_fill</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81429809)
Location: fs/fuse/file.c:551
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8142a0b0-ffffffff8142a0fb: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81479906)
Location: fs/fuse/file.c:567
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8147a160-ffffffff8147a1ab: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81494626)
Location: fs/fuse/file.c:590
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81494e50-ffffffff81494e9b: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8149933e)
Location: fs/fuse/file.c:594
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81499ea0-ffffffff81499ef4: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f1082)
Location: fs/fuse/file.c:598
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff814f18c0-ffffffff814f1914: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81580924)
Location: fs/fuse/file.c:607
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff815812f0-ffffffff81581358: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816266d0)
Location: fs/fuse/file.c:607
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81627130-ffffffff81627198: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165eaa9)
Location: fs/fuse/file.c:608
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8165f4f0-ffffffff8165f55a: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8169888f)
Location: fs/fuse/file.c:609
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81699330-ffffffff8169939a: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050d78c)
Location: fs/fuse/file.c:551
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffff80001050e048-ffff80001050e0d4: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c91fc)
Location: fs/fuse/file.c:551
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
c06c9694-c06c9704: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c00000000065446c)
Location: fs/fuse/file.c:551
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
c000000000654f80-c000000000654fe0: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe000378462)
Location: fs/fuse/file.c:551
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe000378d54-ffffffe000378dc8: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81421de9)
Location: fs/fuse/file.c:551
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81422690-ffffffff814226db: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81412869)
Location: fs/fuse/file.c:551
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81413110-ffffffff8141315b: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141df89)
Location: fs/fuse/file.c:551
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8141e830-ffffffff8141e87b: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fuse_read_args_fill(struct fuse_io_args *ia, struct file *file, loff_t pos, size_t count, int opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81434ce9)
Location: fs/fuse/file.c:551
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff814355a0-ffffffff814355eb: fuse_read_args_fill (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
