# Function: <code>wake_up_worker</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81098046)
Location: kernel/workqueue.c:811
Inline: True
Inline callers:
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_unbind_fn
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:rescuer_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109c18e)
Location: kernel/workqueue.c:831
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbind_fn
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a11ee)
Location: kernel/workqueue.c:833
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbind_fn
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109e71c)
Location: kernel/workqueue.c:833
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbind_fn
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a8fb2)
Location: kernel/workqueue.c:835
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810af6d7)
Location: kernel/workqueue.c:833
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8847)
Location: kernel/workqueue.c:833
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810be354)
Location: kernel/workqueue.c:836
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c48f4)
Location: kernel/workqueue.c:837
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c81a3)
Location: kernel/workqueue.c:832
Inline: True
Inline callers:
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
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
In kernel/workqueue.c (ffffffff810c3303)
Location: kernel/workqueue.c:832
Inline: True
Inline callers:
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
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
In kernel/workqueue.c (ffffffff810c8f12)
Location: kernel/workqueue.c:833
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
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
In kernel/workqueue.c (ffffffff810dbb67)
Location: kernel/workqueue.c:850
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
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
In kernel/workqueue.c (ffffffff810f0436)
Location: kernel/workqueue.c:851
Inline: True
Inline callers:
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
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
In kernel/workqueue.c (ffffffff81111cf6)
Location: kernel/workqueue.c:851
Inline: True
Inline callers:
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_sleeping
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
In kernel/workqueue.c (ffffffff8112492b)
Location: kernel/workqueue.c:896
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_tick
  - kernel/workqueue.c:wq_worker_sleeping
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010122d44)
Location: kernel/workqueue.c:837
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0376678)
Location: kernel/workqueue.c:837
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016ca7c)
Location: kernel/workqueue.c:837
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000db640)
Location: kernel/workqueue.c:837
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bec64)
Location: kernel/workqueue.c:837
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ad48e)
Location: kernel/workqueue.c:837
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810be1c4)
Location: kernel/workqueue.c:837
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6524)
Location: kernel/workqueue.c:837
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
</details>
</li>
</ul>

## Differences
