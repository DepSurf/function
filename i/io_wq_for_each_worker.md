# Function: <code>io_wq_for_each_worker</code>

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
In fs/io-wq.c (ffffffff81389fa0)
Location: fs/io-wq.c:867
Inline: True
Direct callers:
  - fs/io-wq.c:__io_wq_destroy
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_cancel_all
```
**Symbols:**

```
ffffffff81389fa0-ffffffff8138a053: io_wq_for_each_worker.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io-wq.c (ffffffff8139ae00)
Location: fs/io-wq.c:730
Inline: True
Direct callers:
  - fs/io-wq.c:io_wq_cpu_online
  - fs/io-wq.c:__io_wq_destroy
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_manager
```
**Symbols:**

```
ffffffff8139ae00-ffffffff8139aeb3: io_wq_for_each_worker.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io-wq.c (ffffffff813a21e0)
Location: fs/io-wq.c:700
Inline: True
Direct callers:
  - fs/io-wq.c:io_wq_cpu_online
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:io_wq_cancel_cb
```
**Symbols:**

```
ffffffff813a21e0-ffffffff813a228f: io_wq_for_each_worker.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io-wq.c (ffffffff813f1030)
Location: fs/io-wq.c:839
Inline: True
Direct callers:
  - fs/io-wq.c:__io_wq_cpu_online
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_cancel_cb
```
**Symbols:**

```
ffffffff813f1030-ffffffff813f10c7: io_wq_for_each_worker.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (ffffffff816d9c30)
Location: io_uring/io-wq.c:851
Inline: True
Direct callers:
  - io_uring/io-wq.c:__io_wq_cpu_online
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_cancel_cb
```
**Symbols:**

```
ffffffff816d9c30-ffffffff816d9cda: io_wq_for_each_worker.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a5c70)
Location: io_uring/io-wq.c:838
Inline: True
Direct callers:
  - io_uring/io-wq.c:__io_wq_cpu_online
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_cancel_cb
```
**Symbols:**

```
ffffffff817a5c70-ffffffff817a5d1a: io_wq_for_each_worker.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e6f10)
Location: io_uring/io-wq.c:837
Inline: True
Direct callers:
  - io_uring/io-wq.c:io_wq_cpu_offline
  - io_uring/io-wq.c:io_wq_cpu_online
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_cancel_cb
```
**Symbols:**

```
ffffffff817e6f10-ffffffff817e6fbc: io_wq_for_each_worker.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182cb30)
Location: io_uring/io-wq.c:861
Inline: True
Direct callers:
  - io_uring/io-wq.c:io_wq_cpu_offline
  - io_uring/io-wq.c:io_wq_cpu_online
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_cancel_cb
```
**Symbols:**

```
ffffffff8182cb30-ffffffff8182cbdc: io_wq_for_each_worker.isra.0 (STB_LOCAL)
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
