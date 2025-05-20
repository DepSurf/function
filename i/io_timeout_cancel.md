# Function: <code>io_timeout_cancel</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138258f)
Location: fs/io_uring.c:4822
Inline: True
Inline callers:
  - fs/io_uring.c:io_async_find_and_cancel
  - fs/io_uring.c:io_timeout_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_timeout_cancel(struct io_ring_ctx *ctx, __u64 user_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813908b0)
Location: fs/io_uring.c:5745
Inline: False
Direct callers:
  - fs/io_uring.c:io_async_find_and_cancel
  - fs/io_uring.c:io_timeout_remove
```
**Symbols:**

```
ffffffff813908b0-ffffffff8139096f: io_timeout_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_timeout_cancel(struct io_ring_ctx *ctx, __u64 user_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813939c0)
Location: fs/io_uring.c:5567
Inline: False
Direct callers:
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_async_cancel
```
**Symbols:**

```
ffffffff813939c0-ffffffff81393a4d: io_timeout_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_timeout_cancel(struct io_ring_ctx *ctx, __u64 user_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e1170)
Location: fs/io_uring.c:6031
Inline: False
Direct callers:
  - fs/io_uring.c:io_try_cancel_userdata
```
**Symbols:**

```
ffffffff813e1170-ffffffff813e11ed: io_timeout_cancel (STB_LOCAL)
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
In io_uring/io_uring.c (ffffffff816d3293)
Location: io_uring/io_uring.c:7320
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_try_cancel
  - io_uring/io_uring.c:io_timeout_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int io_timeout_cancel(struct io_ring_ctx *ctx, struct io_cancel_data *cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff8179994a)
Location: io_uring/timeout.c:253
Inline: True
Inline callers:
  - io_uring/timeout.c:io_timeout_remove
Direct callers:
  - io_uring/cancel.c:io_try_cancel
```
**Symbols:**

```
ffffffff81799790-ffffffff817997f2: io_timeout_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int io_timeout_cancel(struct io_ring_ctx *ctx, struct io_cancel_data *cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff817daa1a)
Location: io_uring/timeout.c:293
Inline: True
Inline callers:
  - io_uring/timeout.c:io_timeout_remove
Direct callers:
  - io_uring/cancel.c:io_try_cancel
```
**Symbols:**

```
ffffffff817da860-ffffffff817da8c2: io_timeout_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int io_timeout_cancel(struct io_ring_ctx *ctx, struct io_cancel_data *cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff8181ed0e)
Location: io_uring/timeout.c:287
Inline: True
Inline callers:
  - io_uring/timeout.c:io_timeout_remove
Direct callers:
  - io_uring/cancel.c:io_try_cancel
```
**Symbols:**

```
ffffffff8181eb50-ffffffff8181ebb2: io_timeout_cancel (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
