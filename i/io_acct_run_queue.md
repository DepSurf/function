# Function: <code>io_acct_run_queue</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f2652)
Location: fs/io-wq.c:238
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_wqe_dec_running
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
In io_uring/io-wq.c (ffffffff816db176)
Location: io_uring/io-wq.c:240
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_wqe_dec_running
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
In io_uring/io-wq.c (ffffffff817a7262)
Location: io_uring/io-wq.c:242
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_wqe_dec_running
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
In io_uring/io-wq.c (ffffffff817e838a)
Location: io_uring/io-wq.c:245
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_wq_dec_running
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool io_acct_run_queue(struct io_wq_acct *acct);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182e14e)
Location: io_uring/io-wq.c:255
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_wq_dec_running
Direct callers:
  - io_uring/io-wq.c:io_wq_worker
```
**Symbols:**

```
ffffffff8182c1b0-ffffffff8182c1f3: io_acct_run_queue (STB_LOCAL)
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
</ul>
