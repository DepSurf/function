# Function: <code>fuse_io_alloc</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81427fa0)
Location: fs/fuse/file.c:649
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff81427fa0-ffffffff81428019: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81477710)
Location: fs/fuse/file.c:665
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff81477710-ffffffff81477789: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81492a60)
Location: fs/fuse/file.c:688
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff81492a60-ffffffff81492ad9: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81496a10)
Location: fs/fuse/file.c:692
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff81496a10-ffffffff81496a89: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814ee330)
Location: fs/fuse/file.c:696
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff814ee330-ffffffff814ee3a9: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157e3a0)
Location: fs/fuse/file.c:705
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff8157e3a0-ffffffff8157e429: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81623b00)
Location: fs/fuse/file.c:705
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff81623b00-ffffffff81623b89: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165bee0)
Location: fs/fuse/file.c:706
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff8165bee0-ffffffff8165bf69: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81695e00)
Location: fs/fuse/file.c:707
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff81695e00-ffffffff81695eb7: fuse_io_alloc (STB_LOCAL)
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
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050a710)
Location: fs/fuse/file.c:649
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffff80001050a710-ffff80001050a78c: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c7788)
Location: fs/fuse/file.c:649
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
c06c7788-c06c7808: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c000000000652590)
Location: fs/fuse/file.c:649
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
c000000000652590-c000000000652644: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe00037606c)
Location: fs/fuse/file.c:649
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffe00037606c-ffffffe0003760ee: fuse_io_alloc (STB_LOCAL)
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
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81420580)
Location: fs/fuse/file.c:649
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff81420580-ffffffff814205f9: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81411000)
Location: fs/fuse/file.c:649
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff81411000-ffffffff81411079: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141c720)
Location: fs/fuse/file.c:649
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff8141c720-ffffffff8141c799: fuse_io_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fuse_io_args *fuse_io_alloc(struct fuse_io_priv *io, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81433500)
Location: fs/fuse/file.c:649
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff81433500-ffffffff81433579: fuse_io_alloc (STB_LOCAL)
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
