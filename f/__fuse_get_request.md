# Function: <code>__fuse_get_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __fuse_get_request(struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130dddb)
Location: fs/fuse/dev.c:116
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_send
Direct callers:
  - fs/fuse/file.c:fuse_async_req_send
```
**Symbols:**

```
ffffffff81311110-ffffffff8131111f: __fuse_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __fuse_get_request(struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813420ab)
Location: fs/fuse/dev.c:103
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_send
Direct callers:
  - fs/fuse/file.c:fuse_async_req_send
```
**Symbols:**

```
ffffffff81345570-ffffffff8134557f: __fuse_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __fuse_get_request(struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81357ffb)
Location: fs/fuse/dev.c:103
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_send
Direct callers:
  - fs/fuse/file.c:fuse_async_req_send
```
**Symbols:**

```
ffffffff8135b2b0-ffffffff8135b2bf: __fuse_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __fuse_get_request(struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136cc5b)
Location: fs/fuse/dev.c:104
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_send
Direct callers:
  - fs/fuse/file.c:fuse_async_req_send
```
**Symbols:**

```
ffffffff8136fc30-ffffffff8136fc3f: __fuse_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __fuse_get_request(struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81394480)
Location: fs/fuse/dev.c:104
Inline: False
Direct callers:
  - fs/fuse/dev.c:__fuse_request_send
  - fs/fuse/file.c:fuse_async_req_send
```
**Symbols:**

```
ffffffff81394480-ffffffff81394495: __fuse_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __fuse_get_request(struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c34c0)
Location: fs/fuse/dev.c:107
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_send_read
```
**Symbols:**

```
ffffffff813c34c0-ffffffff813c34d5: __fuse_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __fuse_get_request(struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813db0c0)
Location: fs/fuse/dev.c:143
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/file.c:fuse_async_req_send
```
**Symbols:**

```
ffffffff813db0c0-ffffffff813db0d5: __fuse_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __fuse_get_request(struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81407530)
Location: fs/fuse/dev.c:143
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/file.c:fuse_async_req_send
```
**Symbols:**

```
ffffffff81407530-ffffffff81407545: __fuse_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __fuse_get_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8141f0b0)
Location: fs/fuse/dev.c:66
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff8141f0b0-ffffffff8141f0c5: __fuse_get_request (STB_LOCAL)
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
In fs/fuse/dev.c (ffffffff8146efe1)
Location: fs/fuse/dev.c:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff81489741)
Location: fs/fuse/dev.c:67
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:__fuse_request_send
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
In fs/fuse/dev.c (ffffffff8148efc7)
Location: fs/fuse/dev.c:67
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff814e6a37)
Location: fs/fuse/dev.c:67
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff815747cf)
Location: fs/fuse/dev.c:67
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff8161a5d3)
Location: fs/fuse/dev.c:67
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff816528cf)
Location: fs/fuse/dev.c:67
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff8168bedf)
Location: fs/fuse/dev.c:67
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff800010505360)
Location: fs/fuse/dev.c:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06c172c)
Location: fs/fuse/dev.c:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c00000000064a7c0)
Location: fs/fuse/dev.c:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe00036fb84)
Location: fs/fuse/dev.c:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_simple_request
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
void __fuse_get_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81417690)
Location: fs/fuse/dev.c:66
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff81417690-ffffffff814176a5: __fuse_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __fuse_get_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81408110)
Location: fs/fuse/dev.c:66
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff81408110-ffffffff81408125: __fuse_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __fuse_get_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81413830)
Location: fs/fuse/dev.c:66
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff81413830-ffffffff81413845: __fuse_get_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __fuse_get_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142a660)
Location: fs/fuse/dev.c:66
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff8142a660-ffffffff8142a675: __fuse_get_request (STB_LOCAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
