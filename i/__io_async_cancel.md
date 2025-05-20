# Function: <code>__io_async_cancel</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d3913)
Location: io_uring/io_uring.c:7686
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_async_cancel
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __io_async_cancel(struct io_cancel_data *cd, struct io_uring_task *tctx, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/cancel.c (ffffffff8179e420)
Location: io_uring/cancel.c:130
Inline: False
Direct callers:
  - io_uring/cancel.c:__io_sync_cancel
  - io_uring/cancel.c:io_async_cancel
```
**Symbols:**

```
ffffffff8179e420-ffffffff8179e542: __io_async_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __io_async_cancel(struct io_cancel_data *cd, struct io_uring_task *tctx, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/cancel.c (ffffffff817df610)
Location: io_uring/cancel.c:130
Inline: False
Direct callers:
  - io_uring/cancel.c:__io_sync_cancel
  - io_uring/cancel.c:io_async_cancel
```
**Symbols:**

```
ffffffff817df610-ffffffff817df731: __io_async_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __io_async_cancel(struct io_cancel_data *cd, struct io_uring_task *tctx, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/cancel.c (ffffffff81823a70)
Location: io_uring/cancel.c:166
Inline: False
Direct callers:
  - io_uring/cancel.c:__io_sync_cancel
  - io_uring/cancel.c:io_async_cancel
```
**Symbols:**

```
ffffffff81823a70-ffffffff81823b91: __io_async_cancel (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
