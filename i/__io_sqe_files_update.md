# Function: <code>__io_sqe_files_update</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __io_sqe_files_update(struct io_ring_ctx *ctx, struct io_uring_files_update *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81380580)
Location: fs/io_uring.c:6916
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81380580-ffffffff813808a2: __io_sqe_files_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __io_sqe_files_update(struct io_ring_ctx *ctx, struct io_uring_files_update *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138ee50)
Location: fs/io_uring.c:7983
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8138ee50-ffffffff8138f16d: __io_sqe_files_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __io_sqe_files_update(struct io_ring_ctx *ctx, struct io_uring_rsrc_update2 *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139b9d0)
Location: fs/io_uring.c:7804
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_rsrc_update
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8139b9d0-ffffffff8139be2b: __io_sqe_files_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __io_sqe_files_update(struct io_ring_ctx *ctx, struct io_uring_rsrc_update2 *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e73e0)
Location: fs/io_uring.c:8526
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_rsrc_update
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff813e73e0-ffffffff813e766c: __io_sqe_files_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __io_sqe_files_update(struct io_ring_ctx *ctx, struct io_uring_rsrc_update2 *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d4900)
Location: io_uring/io_uring.c:9801
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_register_rsrc_update
  - io_uring/io_uring.c:io_files_update
  - io_uring/io_uring.c:io_files_update
```
**Symbols:**

```
ffffffff816d4900-ffffffff816d4c02: __io_sqe_files_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __io_sqe_files_update(struct io_ring_ctx *ctx, struct io_uring_rsrc_update2 *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a1670)
Location: io_uring/rsrc.c:448
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_register_rsrc_update
  - io_uring/rsrc.c:io_register_files_update
```
**Symbols:**

```
ffffffff817a1670-ffffffff817a19b8: __io_sqe_files_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __io_sqe_files_update(struct io_ring_ctx *ctx, struct io_uring_rsrc_update2 *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e2890)
Location: io_uring/rsrc.c:349
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_register_rsrc_update
  - io_uring/rsrc.c:io_register_files_update
```
**Symbols:**

```
ffffffff817e2890-ffffffff817e2b58: __io_sqe_files_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __io_sqe_files_update(struct io_ring_ctx *ctx, struct io_uring_rsrc_update2 *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81826810)
Location: io_uring/rsrc.c:354
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_register_rsrc_update
  - io_uring/rsrc.c:io_register_files_update
```
**Symbols:**

```
ffffffff81826810-ffffffff81826ab9: __io_sqe_files_update (STB_LOCAL)
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct io_uring_files_update *up</code> ➡️ <code>struct io_uring_rsrc_update2 *up</code>
</li>
</ul>
</details>
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
