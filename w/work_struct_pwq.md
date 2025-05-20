# Function: <code>work_struct_pwq</code>

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
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111ee46)
Location: kernel/workqueue.c:743
Inline: True
Inline callers:
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_activate_inactive_work
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
In kernel/workqueue.c (ffffffff811299e6)
Location: kernel/workqueue.c:740
Inline: True
Inline callers:
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:pwq_activate_inactive_work
  - kernel/workqueue.c:kick_pool
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
