# Function: <code>d_alloc_parallel</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124df50)
Location: fs/dcache.c:2397
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
  - fs/proc/base.c:proc_fill_cache
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff8124df50-ffffffff8124e429: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81261030)
Location: fs/dcache.c:2406
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
  - fs/proc/base.c:proc_fill_cache
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81261030-ffffffff81261509: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126e830)
Location: fs/dcache.c:2436
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
  - fs/proc/base.c:proc_fill_cache
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff8126e830-ffffffff8126ed5a: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81291160)
Location: fs/dcache.c:2448
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
  - fs/proc/base.c:proc_fill_cache
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81291160-ffffffff8129165d: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b7820)
Location: fs/dcache.c:2462
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
  - fs/fuse/dir.c:fuse_readdir
```
**Symbols:**

```
ffffffff812b7820-ffffffff812b7cab: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cc980)
Location: fs/dcache.c:2443
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff812cc980-ffffffff812cce0b: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e9560)
Location: fs/dcache.c:2513
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff812e9560-ffffffff812e9a05: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fb100)
Location: fs/dcache.c:2513
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff812fb100-ffffffff812fb5a5: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81333de0)
Location: fs/dcache.c:2534
Inline: False
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff81333de0-ffffffff81334273: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133f760)
Location: fs/dcache.c:2541
Inline: False
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff8133f760-ffffffff8133fc2d: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81345be0)
Location: fs/dcache.c:2568
Inline: False
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff81345be0-ffffffff813460a1: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81393800)
Location: fs/dcache.c:2569
Inline: False
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff81393800-ffffffff81393cab: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81414fa0)
Location: fs/dcache.c:2594
Inline: False
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff81414fa0-ffffffff81415544: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814a04b0)
Location: fs/dcache.c:2631
Inline: False
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff814a04b0-ffffffff814a08e1: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d57d0)
Location: fs/dcache.c:2631
Inline: False
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff814d57d0-ffffffff814d5bfc: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81507c20)
Location: fs/dcache.c:2455
Inline: False
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff81507c20-ffffffff81508000: d_alloc_parallel (STB_GLOBAL)
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
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103aa4c0)
Location: fs/dcache.c:2513
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
ffff8000103aa4c0-ffff8000103aa9cc: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058b460)
Location: fs/dcache.c:2513
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c058b460-c058b9c8: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a5440)
Location: fs/dcache.c:2513
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c0000000004a5440-c0000000004a5aa4: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe000270194)
Location: fs/dcache.c:2513
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe000270194-ffffffe0002705c4: d_alloc_parallel (STB_GLOBAL)
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
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f36e0)
Location: fs/dcache.c:2513
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff812f36e0-ffffffff812f3b85: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e4310)
Location: fs/dcache.c:2513
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff812e4310-ffffffff812e47b5: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f14f0)
Location: fs/dcache.c:2513
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff812f14f0-ffffffff812f1995: d_alloc_parallel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *d_alloc_parallel(struct dentry *parent, const struct qstr *name, wait_queue_head_t *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813026b0)
Location: fs/dcache.c:2513
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff813026b0-ffffffff81302bbb: d_alloc_parallel (STB_GLOBAL)
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
