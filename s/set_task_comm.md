# Function: <code>set_task_comm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81095bae)
Location: include/linux/sched.h:2638
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In kernel/workqueue.c (ffffffff8109a57b)
Location: include/linux/sched.h:2638
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810a0cf6)
Location: include/linux/sched.h:2638
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In fs/proc/base.c (ffffffff8127c1ea)
Location: include/linux/sched.h:2638
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81098f4e)
Location: include/linux/sched.h:2907
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In kernel/workqueue.c (ffffffff8109db5e)
Location: include/linux/sched.h:2907
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810a43e6)
Location: include/linux/sched.h:2907
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In fs/proc/base.c (ffffffff812a91af)
Location: include/linux/sched.h:2907
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109defe)
Location: include/linux/sched.h:3021
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In kernel/workqueue.c (ffffffff810a26cf)
Location: include/linux/sched.h:3021
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810a9cb6)
Location: include/linux/sched.h:3021
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In fs/proc/base.c (ffffffff812beaaf)
Location: include/linux/sched.h:3021
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109b53d)
Location: include/linux/sched.h:1460
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In kernel/workqueue.c (ffffffff8109fb30)
Location: include/linux/sched.h:1460
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810a68d6)
Location: include/linux/sched.h:1460
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In fs/proc/base.c (ffffffff812cb701)
Location: include/linux/sched.h:1460
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a2222)
Location: include/linux/sched.h:1490
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In kernel/workqueue.c (ffffffff810a6362)
Location: include/linux/sched.h:1490
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810ad046)
Location: include/linux/sched.h:1490
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In fs/proc/base.c (ffffffff812effa1)
Location: include/linux/sched.h:1490
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a8671)
Location: include/linux/sched.h:1606
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810ad1b0)
Location: include/linux/sched.h:1606
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810b3dd4)
Location: include/linux/sched.h:1606
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffffffff8131d06e)
Location: include/linux/sched.h:1606
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b173f)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810b5f90)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810bcf24)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffffffff8133422e)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b6e8b)
Location: include/linux/sched.h:1692
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810bbddb)
Location: include/linux/sched.h:1692
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810c2df4)
Location: include/linux/sched.h:1692
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffffffff8135c426)
Location: include/linux/sched.h:1692
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bd3b6)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810c207b)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810c93c4)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffffffff81374886)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c4bc0)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810c9c28)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810d17b4)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffffffff813bc4dc)
Location: include/linux/sched.h:1727
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bff53)
Location: include/linux/sched.h:1788
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810c4d78)
Location: include/linux/sched.h:1788
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810cc254)
Location: include/linux/sched.h:1788
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffffffff813ce0ac)
Location: include/linux/sched.h:1788
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c1983)
Location: include/linux/sched.h:1810
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810c660f)
Location: include/linux/sched.h:1810
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810cdd34)
Location: include/linux/sched.h:1810
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/io_uring.c (ffffffff813a0ece)
Location: include/linux/sched.h:1810
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
```
```
In fs/io-wq.c (ffffffff813a312f)
Location: include/linux/sched.h:1810
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_worker
```
```
In fs/proc/base.c (ffffffff813d4f4b)
Location: include/linux/sched.h:1810
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d478c)
Location: include/linux/sched.h:1927
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810d92ce)
Location: include/linux/sched.h:1927
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810e0f84)
Location: include/linux/sched.h:1927
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/io_uring.c (ffffffff813f0730)
Location: include/linux/sched.h:1927
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
```
```
In fs/io-wq.c (ffffffff813f2606)
Location: include/linux/sched.h:1927
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_worker
```
```
In fs/proc/base.c (ffffffff8142696b)
Location: include/linux/sched.h:1927
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ed450)
Location: include/linux/sched.h:1949
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810f2e98)
Location: include/linux/sched.h:1949
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810fb358)
Location: include/linux/sched.h:1949
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffffffff814a02f2)
Location: include/linux/sched.h:1949
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
```
In io_uring/io_uring.c (ffffffff816d9010)
Location: include/linux/sched.h:1949
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sq_thread
```
```
In io_uring/io-wq.c (ffffffff816db12a)
Location: include/linux/sched.h:1949
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_worker
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110e870)
Location: include/linux/sched.h:1976
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff811144b8)
Location: include/linux/sched.h:1976
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff8111e288)
Location: include/linux/sched.h:1976
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffffffff815351f2)
Location: include/linux/sched.h:1976
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
```
In io_uring/sqpoll.c (ffffffff8179a490)
Location: include/linux/sched.h:1976
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/io-wq.c (ffffffff817a71f7)
Location: include/linux/sched.h:1976
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_worker
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8111a980)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff81122005)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff8112b4e4)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In fs/proc/base.c (ffffffff8156d3b5)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
```
In io_uring/sqpoll.c (ffffffff817db4f0)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/io-wq.c (ffffffff817e8318)
Location: include/linux/sched.h:1987
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff811243f0)
Location: include/linux/sched.h:1889
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In kernel/workqueue.c (ffffffff8112ae47)
Location: include/linux/sched.h:1889
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff81135c34)
Location: include/linux/sched.h:1889
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In fs/proc/base.c (ffffffff815a59b5)
Location: include/linux/sched.h:1889
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
```
In io_uring/sqpoll.c (ffffffff8181f830)
Location: include/linux/sched.h:1889
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/io-wq.c (ffffffff8182e0f5)
Location: include/linux/sched.h:1889
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff80001011a414)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_prctl
```
```
In kernel/workqueue.c (ffff800010120580)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffff8000101290a4)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffff80001043f570)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036e7cc)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prctl
```
```
In kernel/workqueue.c (c0374444)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (c037b608)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (c0605b00)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c000000000161cc8)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prctl
```
```
In kernel/workqueue.c (c000000000168b88)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (c0000000001738b8)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (c000000000553990)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d4c9c)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prctl
```
```
In kernel/workqueue.c (ffffffe0000d925c)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffe0000dff08)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffffffe0002d5ebc)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b7726)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810bc3eb)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810c3744)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffffffff8136ce66)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a6066)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810aac6f)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810b1f74)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffffffff8135d8f6)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b6c86)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810bb94b)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810c2c94)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffffffff8136a936)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bf006)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In kernel/workqueue.c (ffffffff810c3d2b)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
```
In kernel/kthread.c (ffffffff810cb0d4)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In fs/proc/base.c (ffffffff8137e226)
Location: include/linux/sched.h:1685
Inline: True
Inline callers:
  - fs/proc/base.c:comm_write
```
</details>
</li>
</ul>

## Differences
