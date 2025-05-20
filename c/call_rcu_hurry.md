# Function: <code>call_rcu_hurry</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void call_rcu_hurry(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8110fecd)
Location: include/linux/rcupdate.h:114
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
```
```
In kernel/rcu/sync.c (ffffffff811ac5ac)
Location: include/linux/rcupdate.h:114
Inline: True
Inline callers:
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
```
```
In kernel/rcu/tree.c (ffffffff811b9150)
Location: include/linux/rcupdate.h:114
Inline: False
```
```
In io_uring/io_uring.c (ffffffff8178894a)
Location: include/linux/rcupdate.h:114
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In lib/percpu-refcount.c (ffffffff817d8d01)
Location: include/linux/rcupdate.h:114
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7b9c6)
Location: include/linux/rcupdate.h:114
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In net/core/dst.c (ffffffff81dd3d30)
Location: include/linux/rcupdate.h:114
Inline: True
Inline callers:
  - net/core/dst.c:dst_release
```
**Symbols:**

```
ffffffff811b9150-ffffffff811b9163: call_rcu_hurry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void call_rcu_hurry(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111c4cd)
Location: include/linux/rcupdate.h:115
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
```
```
In kernel/rcu/sync.c (ffffffff811be4cc)
Location: include/linux/rcupdate.h:115
Inline: True
Inline callers:
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
```
```
In kernel/rcu/tree.c (ffffffff811cb170)
Location: include/linux/rcupdate.h:115
Inline: False
```
```
In io_uring/io_uring.c (ffffffff817c902a)
Location: include/linux/rcupdate.h:115
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In lib/percpu-refcount.c (ffffffff81817ce1)
Location: include/linux/rcupdate.h:115
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcf6d6)
Location: include/linux/rcupdate.h:115
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In net/core/dst.c (ffffffff81e44cba)
Location: include/linux/rcupdate.h:115
Inline: True
```
**Symbols:**

```
ffffffff811cb170-ffffffff811cb183: call_rcu_hurry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void call_rcu_hurry(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811e0bc0)
Location: kernel/rcu/tree.c:2779
Inline: False
Direct callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - io_uring/io_uring.c:io_eventfd_signal
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
**Symbols:**

```
ffffffff811e0bc0-ffffffff811e0bdc: call_rcu_hurry (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
