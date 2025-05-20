# Function: <code>eventfd_signal_mask</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
__u64 eventfd_signal_mask(struct eventfd_ctx *ctx, __u64 n, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff814eca60)
Location: fs/eventfd.c:46
Inline: False
Direct callers:
  - fs/eventfd.c:eventfd_signal
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_eventfd_ops
```
**Symbols:**

```
ffffffff814eca60-ffffffff814ecb2e: eventfd_signal_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__u64 eventfd_signal_mask(struct eventfd_ctx *ctx, __u64 n, __poll_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81523700)
Location: fs/eventfd.c:46
Inline: False
Direct callers:
  - fs/eventfd.c:eventfd_signal
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_eventfd_ops
```
**Symbols:**

```
ffffffff81523700-ffffffff815237ce: eventfd_signal_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void eventfd_signal_mask(struct eventfd_ctx *ctx, __poll_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81557270)
Location: fs/eventfd.c:56
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_eventfd_ops
  - drivers/gpu/drm/drm_syncobj.c:syncobj_eventfd_entry_fence_func
```
**Symbols:**

```
ffffffff81557270-ffffffff81557333: eventfd_signal_mask (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int mask</code> ➡️ <code>__poll_t mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>__u64 n</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, n, mask</code> ➡️ <code>ctx, mask</code>
</li>
<li>
<b>Return type changed. </b>
<code>__u64</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
