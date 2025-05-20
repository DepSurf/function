# Function: <code>vfs_fadvise</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81205fe0)
Location: mm/fadvise.c:182
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/readahead.c:ksys_readahead
```
**Symbols:**

```
ffffffff81205fe0-ffffffff81206262: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff8121d360)
Location: mm/fadvise.c:182
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/readahead.c:ksys_readahead
```
**Symbols:**

```
ffffffff8121d360-ffffffff8121d5e9: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff8122afa0)
Location: mm/fadvise.c:182
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff8122afa0-ffffffff8122afc7: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81257dc0)
Location: mm/fadvise.c:180
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
Direct callers:
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:madvise_willneed
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81257d60-ffffffff81257d87: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81262690)
Location: mm/fadvise.c:181
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
Direct callers:
  - mm/readahead.c:ksys_readahead
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81262630-ffffffff81262657: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81267120)
Location: mm/fadvise.c:181
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
Direct callers:
  - mm/readahead.c:ksys_readahead
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff812670c0-ffffffff812670e7: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812a3b60)
Location: mm/fadvise.c:181
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
Direct callers:
  - mm/readahead.c:ksys_readahead
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff812a3b00-ffffffff812a3b27: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812fba84)
Location: mm/fadvise.c:180
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
Direct callers:
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:madvise_vma_behavior
  - io_uring/io_uring.c:io_fadvise
```
**Symbols:**

```
ffffffff812fba10-ffffffff812fba4f: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81365c04)
Location: mm/fadvise.c:180
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
Direct callers:
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:madvise_vma_behavior
  - io_uring/advise.c:io_fadvise
```
**Symbols:**

```
ffffffff81365b80-ffffffff81365bbf: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff813980e4)
Location: mm/fadvise.c:180
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
Direct callers:
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:madvise_vma_behavior
  - io_uring/advise.c:io_fadvise
```
**Symbols:**

```
ffffffff81398050-ffffffff81398092: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff813c1f14)
Location: mm/fadvise.c:180
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
Direct callers:
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:madvise_vma_behavior
  - io_uring/advise.c:io_fadvise
```
**Symbols:**

```
ffffffff813c1e80-ffffffff813c1ec2: vfs_fadvise (STB_GLOBAL)
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
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffff8000102b9268)
Location: mm/fadvise.c:182
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:__arm64_sys_madvise
```
**Symbols:**

```
ffff8000102b9268-ffff8000102b92d4: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (c04e5a60)
Location: mm/fadvise.c:182
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c04e5a60-c04e5ac0: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (c0000000003715a0)
Location: mm/fadvise.c:182
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c0000000003715a0-c0000000003715f4: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffe0001dce42)
Location: mm/fadvise.c:182
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
ffffffe0001dce42-ffffffe0001dce9e: vfs_fadvise (STB_GLOBAL)
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
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812235f0)
Location: mm/fadvise.c:182
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812235f0-ffffffff81223617: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff812167a0)
Location: mm/fadvise.c:182
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812167a0-ffffffff812167c7: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81221390)
Location: mm/fadvise.c:182
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81221390-ffffffff812213b7: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_fadvise(struct file *file, loff_t offset, loff_t len, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffff81230550)
Location: mm/fadvise.c:182
Inline: False
Direct callers:
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/readahead.c:ksys_readahead
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81230550-ffffffff81230577: vfs_fadvise (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
