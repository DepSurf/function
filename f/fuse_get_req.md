# Function: <code>fuse_get_req</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130f230)
Location: fs/fuse/dev.c:202
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_request
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8130f230-ffffffff8130f242: fuse_get_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81343ba7)
Location: fs/fuse/dev.c:182
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_simple_request
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff813435a0-ffffffff813435b2: fuse_get_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81359870)
Location: fs/fuse/dev.c:182
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_request
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81359390-ffffffff813593a2: fuse_get_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136e064)
Location: fs/fuse/dev.c:182
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_request
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff8136dba0-ffffffff8136dbb2: fuse_get_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81392c41)
Location: fs/fuse/dev.c:182
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_request
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81392770-ffffffff81392782: fuse_get_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c28b6)
Location: fs/fuse/dev.c:192
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_simple_request
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff813c1780-ffffffff813c1792: fuse_get_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813dc396)
Location: fs/fuse/dev.c:232
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_simple_request
Direct callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813dae50-ffffffff813dae62: fuse_get_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8140724a)
Location: fs/fuse/dev.c:232
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_request
Direct callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81406a30-ffffffff81406a42: fuse_get_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8141fb00)
Location: fs/fuse/dev.c:105
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff8141fb00-ffffffff8141fd47: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146e540)
Location: fs/fuse/dev.c:105
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff8146e540-ffffffff8146e7ce: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_mount *fm, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81488cb0)
Location: fs/fuse/dev.c:106
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff81488cb0-ffffffff81488f4d: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_mount *fm, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148e5b0)
Location: fs/fuse/dev.c:106
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff8148e5b0-ffffffff8148e84e: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_mount *fm, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e6020)
Location: fs/fuse/dev.c:106
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff814e6020-ffffffff814e62be: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_mount *fm, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81574b80)
Location: fs/fuse/dev.c:106
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff81574b80-ffffffff81574e48: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_mount *fm, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81619f60)
Location: fs/fuse/dev.c:106
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff81619f60-ffffffff8161a1e1: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_mount *fm, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81652100)
Location: fs/fuse/dev.c:106
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff81652100-ffffffff81652381: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_mount *fm, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168b710)
Location: fs/fuse/dev.c:106
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff8168b710-ffffffff8168b991: fuse_get_req (STB_LOCAL)
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
struct fuse_req *fuse_get_req(struct fuse_conn *fc, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff800010502410)
Location: fs/fuse/dev.c:105
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffff800010502410-ffff800010502618: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06bea88)
Location: fs/fuse/dev.c:105
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_retrieve
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
c06bea88-c06beccc: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c000000000646ac0)
Location: fs/fuse/dev.c:105
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
c000000000646ac0-c000000000646d84: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe00036f49e)
Location: fs/fuse/dev.c:105
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffe00036f49e-ffffffe00036f666: fuse_get_req (STB_LOCAL)
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
struct fuse_req *fuse_get_req(struct fuse_conn *fc, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814180e0)
Location: fs/fuse/dev.c:105
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff814180e0-ffffffff81418327: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81408b60)
Location: fs/fuse/dev.c:105
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff81408b60-ffffffff81408da7: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81414280)
Location: fs/fuse/dev.c:105
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff81414280-ffffffff814144c7: fuse_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req(struct fuse_conn *fc, bool for_background);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142b5f0)
Location: fs/fuse/dev.c:105
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff8142b5f0-ffffffff8142b7cf: fuse_get_req (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool for_background</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int npages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_mount *fm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_conn *fc</code>
</li>
</ul>
</details>
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
