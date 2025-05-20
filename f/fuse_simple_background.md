# Function: <code>fuse_simple_background</code>

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
int fuse_simple_background(struct fuse_conn *fc, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8141fd50)
Location: fs/fuse/dev.c:543
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff8141fd50-ffffffff8141ff39: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_conn *fc, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146e7d0)
Location: fs/fuse/dev.c:543
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff8146e7d0-ffffffff8146e8d6: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_mount *fm, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81488f50)
Location: fs/fuse/dev.c:556
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff81488f50-ffffffff81489058: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_mount *fm, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148e850)
Location: fs/fuse/dev.c:556
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff8148e850-ffffffff8148ea77: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_mount *fm, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e62c0)
Location: fs/fuse/dev.c:556
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff814e62c0-ffffffff814e64e7: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_mount *fm, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81574e50)
Location: fs/fuse/dev.c:548
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff81574e50-ffffffff81575022: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_mount *fm, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8161a9a0)
Location: fs/fuse/dev.c:548
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff8161a9a0-ffffffff8161ab19: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_mount *fm, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff816523a0)
Location: fs/fuse/dev.c:550
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff816523a0-ffffffff81652501: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_mount *fm, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168b9b0)
Location: fs/fuse/dev.c:550
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff8168b9b0-ffffffff8168bb11: fuse_simple_background (STB_GLOBAL)
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
int fuse_simple_background(struct fuse_conn *fc, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff800010502618)
Location: fs/fuse/dev.c:543
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffff800010502618-ffff80001050282c: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_conn *fc, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06beccc)
Location: fs/fuse/dev.c:543
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
c06beccc-c06beee4: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_conn *fc, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c000000000646d90)
Location: fs/fuse/dev.c:543
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
c000000000646d90-c000000000646fd4: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_conn *fc, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe00036f666)
Location: fs/fuse/dev.c:543
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffe00036f666-ffffffe00036f812: fuse_simple_background (STB_GLOBAL)
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
int fuse_simple_background(struct fuse_conn *fc, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81418330)
Location: fs/fuse/dev.c:543
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff81418330-ffffffff81418519: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_conn *fc, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81408db0)
Location: fs/fuse/dev.c:543
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff81408db0-ffffffff81408f99: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_conn *fc, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814144d0)
Location: fs/fuse/dev.c:543
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff814144d0-ffffffff814146b9: fuse_simple_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_simple_background(struct fuse_conn *fc, struct fuse_args *args, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142b7d0)
Location: fs/fuse/dev.c:543
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff8142b7d0-ffffffff8142b9a6: fuse_simple_background (STB_GLOBAL)
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
