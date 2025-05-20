# Function: <code>queue_kthread_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool queue_kthread_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a0560)
Location: kernel/kthread.c:638
Inline: False
Direct callers:
  - kernel/kthread.c:flush_kthread_worker
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/md/dm.c:dm_request_fn
  - drivers/md/dm.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff810a0560-ffffffff810a05db: queue_kthread_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool queue_kthread_work(struct kthread_worker *worker, struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a3c50)
Location: kernel/kthread.c:638
Inline: False
Direct callers:
  - kernel/kthread.c:flush_kthread_worker
  - drivers/block/loop.c:loop_queue_rq
  - drivers/spi/spi.c:__spi_queued_transfer
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff810a3c50-ffffffff810a3cce: queue_kthread_work (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
