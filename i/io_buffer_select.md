# Function: <code>io_buffer_select</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8137bf35)
Location: fs/io_uring.c:2336
Inline: True
Inline callers:
  - fs/io_uring.c:io_recv_buffer_select
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_compat_import
Direct callers:
  - fs/io_uring.c:io_recv_buffer_select
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_compat_import
```
**Symbols:**

```
ffffffff8137be00-ffffffff8137bf1d: io_buffer_select.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff81393320)
Location: fs/io_uring.c:3087
Inline: True
Inline callers:
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_compat_import
Direct callers:
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_compat_import
```
**Symbols:**

```
ffffffff8138a370-ffffffff8138a48d: io_buffer_select.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8139639f)
Location: fs/io_uring.c:2889
Inline: True
Inline callers:
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_import_iovec
Direct callers:
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_import_iovec
```
**Symbols:**

```
ffffffff81390f10-ffffffff8139102d: io_buffer_select.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff813eae3f)
Location: fs/io_uring.c:3111
Inline: True
Inline callers:
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_import_iovec
Direct callers:
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_import_iovec
  - fs/io_uring.c:io_import_iovec
```
**Symbols:**

```
ffffffff813de9e0-ffffffff813deaf7: io_buffer_select.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *io_buffer_select(struct io_kiocb *req, size_t *len, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816ccc60)
Location: io_uring/io_uring.c:3649
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_recv
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:__io_import_iovec
  - io_uring/io_uring.c:__io_import_iovec
  - io_uring/io_uring.c:__io_import_iovec
```
**Symbols:**

```
ffffffff816ccc60-ffffffff816cce68: io_buffer_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *io_buffer_select(struct io_kiocb *req, size_t *len, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff8179f1e0)
Location: io_uring/kbuf.c:171
Inline: False
Direct callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/rw.c:__io_import_iovec
```
**Symbols:**

```
ffffffff8179f1e0-ffffffff8179f40d: io_buffer_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *io_buffer_select(struct io_kiocb *req, size_t *len, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff817e0450)
Location: io_uring/kbuf.c:172
Inline: False
Direct callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/rw.c:__io_import_iovec
```
**Symbols:**

```
ffffffff817e0450-ffffffff817e067a: io_buffer_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *io_buffer_select(struct io_kiocb *req, size_t *len, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff818248d0)
Location: io_uring/kbuf.c:200
Inline: False
Direct callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/rw.c:__io_import_iovec
```
**Symbols:**

```
ffffffff818248d0-ffffffff81824b02: io_buffer_select (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
