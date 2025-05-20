# Function: <code>fuse_request_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_request_alloc(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130d8e0)
Location: fs/fuse/dev.c:83
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
Direct callers:
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff8130d8e0-ffffffff8130d8f5: fuse_request_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_request_alloc(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8134562d)
Location: fs/fuse/dev.c:83
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
Direct callers:
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81341be0-ffffffff81341bf5: fuse_request_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_request_alloc(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8135b321)
Location: fs/fuse/dev.c:83
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
Direct callers:
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81357a30-ffffffff81357a45: fuse_request_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_request_alloc(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136fc9f)
Location: fs/fuse/dev.c:84
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
Direct callers:
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff8136c590-ffffffff8136c5a5: fuse_request_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_request_alloc(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8139499f)
Location: fs/fuse/dev.c:84
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
Direct callers:
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81391170-ffffffff81391185: fuse_request_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_request_alloc(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c3a85)
Location: fs/fuse/dev.c:87
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
Direct callers:
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff813c0a10-ffffffff813c0a25: fuse_request_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_request_alloc(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813dd235)
Location: fs/fuse/dev.c:94
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
Direct callers:
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff813d9710-ffffffff813d9725: fuse_request_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct fuse_req *fuse_request_alloc(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81408d65)
Location: fs/fuse/dev.c:94
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
Direct callers:
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff814052c0-ffffffff814052d5: fuse_request_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8141f310)
Location: fs/fuse/dev.c:52
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff8141f310-ffffffff8141f37d: fuse_request_alloc (STB_LOCAL)
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
In fs/fuse/dev.c (ffffffff8146e7f8)
Location: fs/fuse/dev.c:52
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
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
In fs/fuse/dev.c (ffffffff81488f78)
Location: fs/fuse/dev.c:53
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
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
In fs/fuse/dev.c (ffffffff8148e87a)
Location: fs/fuse/dev.c:53
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
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
In fs/fuse/dev.c (ffffffff814e62ea)
Location: fs/fuse/dev.c:53
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
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
In fs/fuse/dev.c (ffffffff81574e78)
Location: fs/fuse/dev.c:53
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc(struct fuse_mount *fm, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81619510)
Location: fs/fuse/dev.c:53
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff81619510-ffffffff81619589: fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc(struct fuse_mount *fm, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81651660)
Location: fs/fuse/dev.c:53
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff81651660-ffffffff816516d9: fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc(struct fuse_mount *fm, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168ac70)
Location: fs/fuse/dev.c:53
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff8168ac70-ffffffff8168ace9: fuse_request_alloc (STB_LOCAL)
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
struct fuse_req *fuse_request_alloc(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff800010501588)
Location: fs/fuse/dev.c:52
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffff800010501588-ffff800010501608: fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06be384)
Location: fs/fuse/dev.c:52
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
c06be384-c06be3f8: fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c000000000645c50)
Location: fs/fuse/dev.c:52
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
c000000000645c50-c000000000645cfc: fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe00036ec22)
Location: fs/fuse/dev.c:52
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffe00036ec22-ffffffe00036ec90: fuse_request_alloc (STB_LOCAL)
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
struct fuse_req *fuse_request_alloc(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814178f0)
Location: fs/fuse/dev.c:52
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff814178f0-ffffffff8141795d: fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81408370)
Location: fs/fuse/dev.c:52
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff81408370-ffffffff814083dd: fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81413a90)
Location: fs/fuse/dev.c:52
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff81413a90-ffffffff81413afd: fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc(gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142a910)
Location: fs/fuse/dev.c:52
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
**Symbols:**

```
ffffffff8142a910-ffffffff8142a97d: fuse_request_alloc (STB_LOCAL)
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
<code>gfp_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int npages</code>
</li>
</ul>
</details>
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
