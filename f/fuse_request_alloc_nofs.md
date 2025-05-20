# Function: <code>fuse_request_alloc_nofs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc_nofs(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130edf0)
Location: fs/fuse/dev.c:89
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff8130edf0-ffffffff8130ee05: fuse_request_alloc_nofs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc_nofs(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81343200)
Location: fs/fuse/dev.c:89
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81343200-ffffffff81343215: fuse_request_alloc_nofs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc_nofs(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81359010)
Location: fs/fuse/dev.c:89
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81359010-ffffffff81359025: fuse_request_alloc_nofs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc_nofs(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136d820)
Location: fs/fuse/dev.c:90
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8136d820-ffffffff8136d835: fuse_request_alloc_nofs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc_nofs(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813923f0)
Location: fs/fuse/dev.c:90
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff813923f0-ffffffff81392405: fuse_request_alloc_nofs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc_nofs(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c1390)
Location: fs/fuse/dev.c:93
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff813c1390-ffffffff813c13a5: fuse_request_alloc_nofs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc_nofs(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813da900)
Location: fs/fuse/dev.c:100
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff813da900-ffffffff813da915: fuse_request_alloc_nofs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fuse_req *fuse_request_alloc_nofs(unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814064d0)
Location: fs/fuse/dev.c:100
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff814064d0-ffffffff814064e5: fuse_request_alloc_nofs (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
