# Function: <code>io_run_cancel</code>

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
In fs/io-wq.c (ffffffff81389e10)
Location: fs/io-wq.c:776
Inline: True
Direct callers:
  - fs/io-wq.c:io_wqe_cancel_pending_work
  - fs/io-wq.c:io_wqe_enqueue
```
**Symbols:**

```
ffffffff81389e10-ffffffff81389e71: io_run_cancel.isra.0 (STB_LOCAL)
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
In fs/io-wq.c (ffffffff8139ad70)
Location: fs/io-wq.c:846
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_cancel_pending_work
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
In fs/io-wq.c (ffffffff813a2143)
Location: fs/io-wq.c:733
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_cancel_pending_work
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
In fs/io-wq.c (ffffffff813f20ed)
Location: fs/io-wq.c:867
Inline: True
Inline callers:
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
In io_uring/io-wq.c (ffffffff816d9ee1)
Location: io_uring/io-wq.c:879
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
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
In io_uring/io-wq.c (ffffffff817a5f51)
Location: io_uring/io-wq.c:866
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
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
In io_uring/io-wq.c (ffffffff817e6acc)
Location: io_uring/io-wq.c:865
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
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
In io_uring/io-wq.c (ffffffff8182c88c)
Location: io_uring/io-wq.c:889
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
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
