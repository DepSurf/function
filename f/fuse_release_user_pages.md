# Function: <code>fuse_release_user_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff813157d0)
Location: fs/fuse/file.c:519
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_aio_complete_req
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff813157d0-ffffffff8131582a: fuse_release_user_pages.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_req *req, bool should_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134b2b0)
Location: fs/fuse/file.c:533
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffffffff8134b2b0-ffffffff8134b35c: fuse_release_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_req *req, bool should_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81360bc0)
Location: fs/fuse/file.c:534
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffffffff81360bc0-ffffffff81360c6c: fuse_release_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_req *req, bool should_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813750d0)
Location: fs/fuse/file.c:529
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffffffff813750d0-ffffffff81375146: fuse_release_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_req *req, bool should_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139a380)
Location: fs/fuse/file.c:529
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffffffff8139a380-ffffffff8139a432: fuse_release_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_req *req, bool should_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813c8960)
Location: fs/fuse/file.c:529
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffffffff813c8960-ffffffff813c8a16: fuse_release_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_req *req, bool should_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e1b10)
Location: fs/fuse/file.c:534
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffffffff813e1b10-ffffffff813e1bc6: fuse_release_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_req *req, bool should_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140d7d0)
Location: fs/fuse/file.c:546
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffffffff8140d7d0-ffffffff8140d887: fuse_release_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_args_pages *ap, bool should_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814269d0)
Location: fs/fuse/file.c:571
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffffffff814269d0-ffffffff81426a83: fuse_release_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814797da)
Location: fs/fuse/file.c:587
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814944fd)
Location: fs/fuse/file.c:610
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814993e6)
Location: fs/fuse/file.c:614
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f0ed2)
Location: fs/fuse/file.c:618
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81580783)
Location: fs/fuse/file.c:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81626501)
Location: fs/fuse/file.c:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165e8db)
Location: fs/fuse/file.c:628
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8169867d)
Location: fs/fuse/file.c:629
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffff80001050a648)
Location: fs/fuse/file.c:571
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffff80001050a648-ffff80001050a710: fuse_release_user_pages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_args_pages *ap, bool should_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c6958)
Location: fs/fuse/file.c:571
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
c06c6958-c06c69f8: fuse_release_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (c0000000006510b0)
Location: fs/fuse/file.c:571
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
c0000000006510b0-c0000000006511fc: fuse_release_user_pages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffe000375bba)
Location: fs/fuse/file.c:571
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffffffe000375bba-ffffffe000375c72: fuse_release_user_pages.isra.0 (STB_LOCAL)
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
void fuse_release_user_pages(struct fuse_args_pages *ap, bool should_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141efb0)
Location: fs/fuse/file.c:571
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffffffff8141efb0-ffffffff8141f063: fuse_release_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_args_pages *ap, bool should_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140fa30)
Location: fs/fuse/file.c:571
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffffffff8140fa30-ffffffff8140fae3: fuse_release_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_args_pages *ap, bool should_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141b150)
Location: fs/fuse/file.c:571
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffffffff8141b150-ffffffff8141b203: fuse_release_user_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_args_pages *ap, bool should_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814326a0)
Location: fs/fuse/file.c:571
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_aio_complete_req
```
**Symbols:**

```
ffffffff814326a0-ffffffff81432753: fuse_release_user_pages (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>struct fuse_args_pages *ap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_req *req</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
