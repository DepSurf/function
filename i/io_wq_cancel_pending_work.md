# Function: <code>io_wq_cancel_pending_work</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void io_wq_cancel_pending_work(struct io_wq *wq, struct io_cb_cancel_data *match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:1038
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_cancel_cb
```
**Symbols:**

```
ffffffff817e6c70-ffffffff817e6ce7: io_wq_cancel_pending_work (STB_LOCAL)
ffffffff820f7bb5-ffffffff820f7bca: io_wq_cancel_pending_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void io_wq_cancel_pending_work(struct io_wq *wq, struct io_cb_cancel_data *match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:1059
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_cancel_cb
```
**Symbols:**

```
ffffffff8182ca30-ffffffff8182caa7: io_wq_cancel_pending_work (STB_LOCAL)
ffffffff821d558d-ffffffff821d55a2: io_wq_cancel_pending_work.cold (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
