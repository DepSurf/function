# Function: <code>__fuse_request_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fuse_req *__fuse_request_alloc(unsigned int npages, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130d810)
Location: fs/fuse/dev.c:55
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_request_alloc_nofs
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
**Symbols:**

```
ffffffff8130d810-ffffffff8130d8dd: __fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fuse_req *__fuse_request_alloc(unsigned int npages, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81341b20)
Location: fs/fuse/dev.c:55
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc_nofs
```
**Symbols:**

```
ffffffff81341b20-ffffffff81341bdc: __fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fuse_req *__fuse_request_alloc(unsigned int npages, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81357970)
Location: fs/fuse/dev.c:55
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc_nofs
```
**Symbols:**

```
ffffffff81357970-ffffffff81357a2c: __fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fuse_req *__fuse_request_alloc(unsigned int npages, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136c4d0)
Location: fs/fuse/dev.c:56
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc_nofs
```
**Symbols:**

```
ffffffff8136c4d0-ffffffff8136c58c: __fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fuse_req *__fuse_request_alloc(unsigned int npages, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813910b0)
Location: fs/fuse/dev.c:56
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc_nofs
```
**Symbols:**

```
ffffffff813910b0-ffffffff8139116c: __fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fuse_req *__fuse_request_alloc(unsigned int npages, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c0950)
Location: fs/fuse/dev.c:56
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc_nofs
```
**Symbols:**

```
ffffffff813c0950-ffffffff813c0a0c: __fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fuse_req *__fuse_request_alloc(unsigned int npages, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813d9620)
Location: fs/fuse/dev.c:69
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc_nofs
```
**Symbols:**

```
ffffffff813d9620-ffffffff813d970f: __fuse_request_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct fuse_req *__fuse_request_alloc(unsigned int npages, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:69
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc_nofs
```
**Symbols:**

```
ffffffff814051c0-ffffffff814052bb: __fuse_request_alloc (STB_LOCAL)
ffffffff81409403-ffffffff81409416: __fuse_request_alloc.cold (STB_LOCAL)
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
