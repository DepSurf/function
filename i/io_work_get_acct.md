# Function: <code>io_work_get_acct</code>

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
In fs/io-wq.c (ffffffff8138a235)
Location: fs/io-wq.c:181
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_enqueue
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
In fs/io-wq.c (ffffffff8139b165)
Location: fs/io-wq.c:200
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_enqueue
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
In fs/io-wq.c (ffffffff813a29b5)
Location: fs/io-wq.c:152
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_enqueue
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
In fs/io-wq.c (ffffffff813f1f92)
Location: fs/io-wq.c:162
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:io_wqe_enqueue
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
In io_uring/io-wq.c (ffffffff816d9e8a)
Location: io_uring/io-wq.c:165
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_wqe_enqueue
  - io_uring/io-wq.c:io_wqe_enqueue
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
In io_uring/io-wq.c (ffffffff817a5efa)
Location: io_uring/io-wq.c:167
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_wqe_enqueue
  - io_uring/io-wq.c:io_wqe_enqueue
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
In io_uring/io-wq.c (ffffffff817e6a7a)
Location: io_uring/io-wq.c:160
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:io_wq_enqueue
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
In io_uring/io-wq.c (ffffffff8182c83a)
Location: io_uring/io-wq.c:160
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:io_wq_enqueue
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
