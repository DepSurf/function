# Function: <code>io_assign_current_work</code>

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
void io_assign_current_work(struct io_worker *worker, struct io_wq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8138a460)
Location: fs/io-wq.c:467
Inline: False
Direct callers:
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff8138a460-ffffffff8138a4bd: io_assign_current_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void io_assign_current_work(struct io_worker *worker, struct io_wq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139bf50)
Location: fs/io-wq.c:507
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
Direct callers:
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff8139b460-ffffffff8139b4ee: io_assign_current_work (STB_LOCAL)
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
In fs/io-wq.c (ffffffff813a2d50)
Location: fs/io-wq.c:473
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
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
In fs/io-wq.c (ffffffff813f234d)
Location: fs/io-wq.c:524
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
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
In io_uring/io-wq.c (ffffffff816dadf8)
Location: io_uring/io-wq.c:533
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a6f14)
Location: io_uring/io-wq.c:523
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e8047)
Location: io_uring/io-wq.c:520
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182ddfc)
Location: io_uring/io-wq.c:532
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
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
</ul>
