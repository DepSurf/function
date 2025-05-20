# Function: <code>__io_async_wake</code>

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
int __io_async_wake(struct io_kiocb *req, struct io_poll_iocb *poll, __poll_t mask, task_work_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137d8c0)
Location: fs/io_uring.c:4161
Inline: False
Direct callers:
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_async_wake
  - fs/io_uring.c:io_poll_double_wake
```
**Symbols:**

```
ffffffff8137d8c0-ffffffff8137da29: __io_async_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __io_async_wake(struct io_kiocb *req, struct io_poll_iocb *poll, __poll_t mask, task_work_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138cd10)
Location: fs/io_uring.c:5149
Inline: False
Direct callers:
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_async_wake
```
**Symbols:**

```
ffffffff8138cd10-ffffffff8138ce33: __io_async_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __io_async_wake(struct io_kiocb *req, struct io_poll_iocb *poll, __poll_t mask, task_work_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81393000)
Location: fs/io_uring.c:4848
Inline: False
Direct callers:
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_async_wake
```
**Symbols:**

```
ffffffff81393000-ffffffff813930ef: __io_async_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __io_async_wake(struct io_kiocb *req, struct io_poll_iocb *poll, __poll_t mask, io_req_tw_func_t func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e0820)
Location: fs/io_uring.c:5305
Inline: False
Direct callers:
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_async_wake
```
**Symbols:**

```
ffffffff813e0820-ffffffff813e08c7: __io_async_wake (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>task_work_func_t func</code> ➡️ <code>io_req_tw_func_t func</code>
</li>
</ul>
</details>
</li>
</ul>
