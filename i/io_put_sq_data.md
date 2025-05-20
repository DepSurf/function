# Function: <code>io_put_sq_data</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138cc15)
Location: fs/io_uring.c:7410
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread_stop
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
In fs/io_uring.c (ffffffff81392f56)
Location: fs/io_uring.c:7297
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void io_put_sq_data(struct io_sq_data *sqd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dff10)
Location: fs/io_uring.c:7998
Inline: True
Direct callers:
  - fs/io_uring.c:io_register_iowq_max_workers
  - fs/io_uring.c:io_register_iowq_max_workers
  - fs/io_uring.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff813dff10-ffffffff813dffb7: io_put_sq_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void io_put_sq_data(struct io_sq_data *sqd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8f71e)
Location: io_uring/io_uring.c:9348
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff81e8f71e-ffffffff81e8f7a9: io_put_sq_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void io_put_sq_data(struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff8179aa90)
Location: io_uring/sqpoll.c:67
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/sqpoll.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff8179aa90-ffffffff8179ab04: io_put_sq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void io_put_sq_data(struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff817dbb40)
Location: io_uring/sqpoll.c:67
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/sqpoll.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff817dbb40-ffffffff817dbbb4: io_put_sq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void io_put_sq_data(struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff8181fec0)
Location: io_uring/sqpoll.c:67
Inline: True
Direct callers:
  - io_uring/sqpoll.c:io_sq_thread_finish
  - io_uring/register.c:io_register_iowq_max_workers
  - io_uring/register.c:io_register_iowq_max_workers
```
**Symbols:**

```
ffffffff8181fec0-ffffffff8181ff34: io_put_sq_data (STB_GLOBAL)
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
