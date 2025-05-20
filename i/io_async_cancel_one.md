# Function: <code>io_async_cancel_one</code>

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
In fs/io_uring.c (ffffffff813824e5)
Location: fs/io_uring.c:4968
Inline: True
Inline callers:
  - fs/io_uring.c:io_async_find_and_cancel
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
In fs/io_uring.c (ffffffff81391880)
Location: fs/io_uring.c:5926
Inline: True
Inline callers:
  - fs/io_uring.c:io_async_find_and_cancel
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
In fs/io_uring.c (ffffffff81397784)
Location: fs/io_uring.c:5757
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_async_cancel
  - fs/io_uring.c:io_async_cancel
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
In fs/io_uring.c (ffffffff813ed53b)
Location: fs/io_uring.c:6291
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_try_cancel_userdata
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_async_cancel_one(struct io_uring_task *tctx, struct io_cancel_data *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c7240)
Location: io_uring/io_uring.c:7609
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:io_try_cancel
```
**Symbols:**

```
ffffffff816c7240-ffffffff816c72b7: io_async_cancel_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_async_cancel_one(struct io_uring_task *tctx, struct io_cancel_data *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/cancel.c (ffffffff8179e200)
Location: io_uring/cancel.c:54
Inline: False
Direct callers:
  - io_uring/cancel.c:__io_async_cancel
  - io_uring/cancel.c:io_try_cancel
  - io_uring/cancel.c:io_try_cancel
```
**Symbols:**

```
ffffffff8179e200-ffffffff8179e277: io_async_cancel_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_async_cancel_one(struct io_uring_task *tctx, struct io_cancel_data *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/cancel.c (ffffffff817df3f0)
Location: io_uring/cancel.c:54
Inline: False
Direct callers:
  - io_uring/cancel.c:__io_async_cancel
  - io_uring/cancel.c:io_try_cancel
  - io_uring/cancel.c:io_try_cancel
```
**Symbols:**

```
ffffffff817df3f0-ffffffff817df467: io_async_cancel_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_async_cancel_one(struct io_uring_task *tctx, struct io_cancel_data *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/cancel.c (ffffffff818237e0)
Location: io_uring/cancel.c:77
Inline: False
Direct callers:
  - io_uring/cancel.c:__io_async_cancel
  - io_uring/cancel.c:io_try_cancel
  - io_uring/cancel.c:io_try_cancel
```
**Symbols:**

```
ffffffff818237e0-ffffffff81823857: io_async_cancel_one (STB_LOCAL)
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
