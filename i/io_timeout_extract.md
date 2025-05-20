# Function: <code>io_timeout_extract</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct io_kiocb *io_timeout_extract(struct io_ring_ctx *ctx, __u64 user_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81389470)
Location: fs/io_uring.c:5720
Inline: False
Direct callers:
  - fs/io_uring.c:io_timeout_remove
  - fs/io_uring.c:io_timeout_cancel
```
**Symbols:**

```
ffffffff81389470-ffffffff813894fd: io_timeout_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct io_kiocb *io_timeout_extract(struct io_ring_ctx *ctx, __u64 user_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813903c0)
Location: fs/io_uring.c:5544
Inline: False
Direct callers:
  - fs/io_uring.c:io_timeout_cancel
```
**Symbols:**

```
ffffffff813903c0-ffffffff8139044d: io_timeout_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct io_kiocb *io_timeout_extract(struct io_ring_ctx *ctx, __u64 user_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813ddb50)
Location: fs/io_uring.c:6008
Inline: False
Direct callers:
  - fs/io_uring.c:io_timeout_cancel
```
**Symbols:**

```
ffffffff813ddb50-ffffffff813ddbe0: io_timeout_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct io_kiocb *io_timeout_extract(struct io_ring_ctx *ctx, struct io_cancel_data *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c72e0)
Location: io_uring/io_uring.c:7290
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_try_cancel
  - io_uring/io_uring.c:io_timeout_remove
  - io_uring/io_uring.c:io_timeout_remove
```
**Symbols:**

```
ffffffff816c72e0-ffffffff816c73a4: io_timeout_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct io_kiocb *io_timeout_extract(struct io_ring_ctx *ctx, struct io_cancel_data *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff81798d00)
Location: io_uring/timeout.c:220
Inline: False
Direct callers:
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_remove
```
**Symbols:**

```
ffffffff81798d00-ffffffff81798dde: io_timeout_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct io_kiocb *io_timeout_extract(struct io_ring_ctx *ctx, struct io_cancel_data *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff817d9b90)
Location: io_uring/timeout.c:260
Inline: False
Direct callers:
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_remove
```
**Symbols:**

```
ffffffff817d9b90-ffffffff817d9c86: io_timeout_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct io_kiocb *io_timeout_extract(struct io_ring_ctx *ctx, struct io_cancel_data *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff8181e070)
Location: io_uring/timeout.c:260
Inline: False
Direct callers:
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_remove
```
**Symbols:**

```
ffffffff8181e070-ffffffff8181e13b: io_timeout_extract (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_cancel_data *cd</code>
</li>
<li>
<b>Param removed. </b>
<code>__u64 user_data</code>
</li>
</ul>
</details>
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
