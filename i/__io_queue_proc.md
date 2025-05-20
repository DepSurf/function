# Function: <code>__io_queue_proc</code>

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
In fs/io_uring.c (ffffffff8138022a)
Location: fs/io_uring.c:4343
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_async_queue_proc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __io_queue_proc(struct io_poll_iocb *poll, struct io_poll_table *pt, struct wait_queue_head *head, struct io_poll_iocb **poll_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138fc10)
Location: fs/io_uring.c:5308
Inline: False
Direct callers:
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_async_queue_proc
```
**Symbols:**

```
ffffffff8138fc10-ffffffff8138fd53: __io_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __io_queue_proc(struct io_poll_iocb *poll, struct io_poll_table *pt, struct wait_queue_head *head, struct io_poll_iocb **poll_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81396e90)
Location: fs/io_uring.c:5035
Inline: False
Direct callers:
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_async_queue_proc
```
**Symbols:**

```
ffffffff81396e90-ffffffff81396faf: __io_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __io_queue_proc(struct io_poll_iocb *poll, struct io_poll_table *pt, struct wait_queue_head *head, struct io_poll_iocb **poll_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813de020)
Location: fs/io_uring.c:5505
Inline: False
Direct callers:
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_async_queue_proc
```
**Symbols:**

```
ffffffff813de020-ffffffff813de152: __io_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __io_queue_proc(struct io_poll_iocb *poll, struct io_poll_table *pt, struct wait_queue_head *head, struct io_poll_iocb **poll_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c8480)
Location: io_uring/io_uring.c:6845
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_async_queue_proc
  - io_uring/io_uring.c:io_poll_queue_proc
```
**Symbols:**

```
ffffffff816c8480-ffffffff816c85c8: __io_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __io_queue_proc(struct io_poll *poll, struct io_poll_table *pt, struct wait_queue_head *head, struct io_poll **poll_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff8179c5b0)
Location: io_uring/poll.c:477
Inline: False
Direct callers:
  - io_uring/poll.c:io_async_queue_proc
  - io_uring/poll.c:io_poll_queue_proc
```
**Symbols:**

```
ffffffff8179c5b0-ffffffff8179c766: __io_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __io_queue_proc(struct io_poll *poll, struct io_poll_table *pt, struct wait_queue_head *head, struct io_poll **poll_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff817dd900)
Location: io_uring/poll.c:479
Inline: False
Direct callers:
  - io_uring/poll.c:io_async_queue_proc
  - io_uring/poll.c:io_poll_queue_proc
```
**Symbols:**

```
ffffffff817dd900-ffffffff817ddab8: __io_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __io_queue_proc(struct io_poll *poll, struct io_poll_table *pt, struct wait_queue_head *head, struct io_poll **poll_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff81821c50)
Location: io_uring/poll.c:491
Inline: False
Direct callers:
  - io_uring/poll.c:io_async_queue_proc
  - io_uring/poll.c:io_poll_queue_proc
```
**Symbols:**

```
ffffffff81821c50-ffffffff81821e55: __io_queue_proc (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct io_poll_iocb *poll</code> ➡️ <code>struct io_poll *poll</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct io_poll_iocb **poll_ptr</code> ➡️ <code>struct io_poll **poll_ptr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
