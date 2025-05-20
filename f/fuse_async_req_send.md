# Function: <code>fuse_async_req_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_req *req, size_t num_bytes, struct fuse_io_priv *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81316270)
Location: fs/fuse/file.c:618
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff81316270-ffffffff81316313: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_req *req, size_t num_bytes, struct fuse_io_priv *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134abc0)
Location: fs/fuse/file.c:631
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff8134abc0-ffffffff8134ac63: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_req *req, size_t num_bytes, struct fuse_io_priv *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813604d0)
Location: fs/fuse/file.c:632
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff813604d0-ffffffff81360573: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_req *req, size_t num_bytes, struct fuse_io_priv *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81373f20)
Location: fs/fuse/file.c:627
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81373f20-ffffffff81373f94: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_req *req, size_t num_bytes, struct fuse_io_priv *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81399c30)
Location: fs/fuse/file.c:627
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
```
**Symbols:**

```
ffffffff81399c30-ffffffff81399caa: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813ca5fb)
Location: fs/fuse/file.c:627
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_send_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_req *req, size_t num_bytes, struct fuse_io_priv *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e1d00)
Location: fs/fuse/file.c:632
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
```
**Symbols:**

```
ffffffff813e1d00-ffffffff813e1d7a: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_req *req, size_t num_bytes, struct fuse_io_priv *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140db90)
Location: fs/fuse/file.c:644
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
```
**Symbols:**

```
ffffffff8140db90-ffffffff8140dc0a: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81427f00)
Location: fs/fuse/file.c:702
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff81427f00-ffffffff81427f9b: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81478a60)
Location: fs/fuse/file.c:718
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
```
**Symbols:**

```
ffffffff81478a60-ffffffff81478b45: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fuse_async_req_send(struct fuse_mount *fm, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81493500)
Location: fs/fuse/file.c:741
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
```
**Symbols:**

```
ffffffff81493500-ffffffff814935e5: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fuse_async_req_send(struct fuse_mount *fm, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81498490)
Location: fs/fuse/file.c:745
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff81498490-ffffffff81498573: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_async_req_send(struct fuse_mount *fm, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:749
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff814f00f0-ffffffff814f01e6: fuse_async_req_send (STB_LOCAL)
ffffffff81cd2145-ffffffff81cd215a: fuse_async_req_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_async_req_send(struct fuse_mount *fm, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:758
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff8157e5e0-ffffffff8157e6e8: fuse_async_req_send (STB_LOCAL)
ffffffff81e85248-ffffffff81e8525d: fuse_async_req_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_async_req_send(struct fuse_mount *fm, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:758
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff81624570-ffffffff81624678: fuse_async_req_send (STB_LOCAL)
ffffffff82072756-ffffffff8207276b: fuse_async_req_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_async_req_send(struct fuse_mount *fm, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:759
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff8165c6c0-ffffffff8165c7c8: fuse_async_req_send (STB_LOCAL)
ffffffff820f23cf-ffffffff820f23e4: fuse_async_req_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_async_req_send(struct fuse_mount *fm, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:760
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff81696420-ffffffff81696528: fuse_async_req_send (STB_LOCAL)
ffffffff821cf67f-ffffffff821cf694: fuse_async_req_send.cold (STB_LOCAL)
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
ssize_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050b900)
Location: fs/fuse/file.c:702
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffff80001050b900-ffff80001050b9fc: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c6a9c)
Location: fs/fuse/file.c:702
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
c06c6a9c-c06c6b44: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c0000000006512f0)
Location: fs/fuse/file.c:702
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
c0000000006512f0-c000000000651420: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe000377998)
Location: fs/fuse/file.c:702
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffe000377998-ffffffe000377a60: fuse_async_req_send (STB_LOCAL)
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
ssize_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814204e0)
Location: fs/fuse/file.c:702
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff814204e0-ffffffff8142057b: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81410f60)
Location: fs/fuse/file.c:702
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff81410f60-ffffffff81410ffb: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141c680)
Location: fs/fuse/file.c:702
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff8141c680-ffffffff8141c71b: fuse_async_req_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t fuse_async_req_send(struct fuse_conn *fc, struct fuse_io_args *ia, size_t num_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814327f0)
Location: fs/fuse/file.c:702
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff814327f0-ffffffff81432889: fuse_async_req_send (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_io_args *ia</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_req *req</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_io_priv *io</code>
</li>
<li>
<b>Return type changed. </b>
<code>size_t</code> ➡️ <code>ssize_t</code>
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
