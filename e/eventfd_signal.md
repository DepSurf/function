# Function: <code>eventfd_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81258f80)
Location: fs/eventfd.c:54
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff81258f80-ffffffff81258ff4: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81281960)
Location: fs/eventfd.c:54
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff81281960-ffffffff812819d3: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81295490)
Location: fs/eventfd.c:54
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff81295490-ffffffff81295503: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812a2750)
Location: fs/eventfd.c:54
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff812a2750-ffffffff812a27c3: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812c5a60)
Location: fs/eventfd.c:54
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff812c5a60-ffffffff812c5ad3: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812eec90)
Location: fs/eventfd.c:54
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff812eec90-ffffffff812eed03: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81303620)
Location: fs/eventfd.c:54
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff81303620-ffffffff81303693: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81324b90)
Location: fs/eventfd.c:59
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_cqring_ev_posted
```
**Symbols:**

```
ffffffff81324b90-ffffffff81324c07: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813378f0)
Location: fs/eventfd.c:61
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_cqring_ev_posted
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_send_intx_eventfd
```
**Symbols:**

```
ffffffff813378f0-ffffffff81337993: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81371500)
Location: fs/eventfd.c:62
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
  - fs/io_uring.c:io_cqring_ev_posted
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
```
**Symbols:**

```
ffffffff81371500-ffffffff813715a2: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8137f2c0)
Location: fs/eventfd.c:62
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
  - fs/io_uring.c:io_cqring_ev_posted_iopoll
  - fs/io_uring.c:io_cqring_ev_posted
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
```
**Symbols:**

```
ffffffff8137f2c0-ffffffff8137f362: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81385f40)
Location: fs/eventfd.c:62
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_cqring_ev_posted
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
```
**Symbols:**

```
ffffffff81385f40-ffffffff81385fe3: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813d3200)
Location: fs/eventfd.c:60
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_cqring_ev_posted
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_request
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
```
**Symbols:**

```
ffffffff813d3200-ffffffff813d32b6: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8145c730)
Location: fs/eventfd.c:60
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
  - io_uring/io_uring.c:__io_commit_cqring_flush
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_aer_err_detected
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_request
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_unmask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
```
**Symbols:**

```
ffffffff8145c730-ffffffff8145c7fe: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff814ecb40)
Location: fs/eventfd.c:88
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff814ecb40-ffffffff814ecb5c: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff815237e0)
Location: fs/eventfd.c:88
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff815237e0-ffffffff815237fc: eventfd_signal (STB_GLOBAL)
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
In mm/memcontrol.c (ffffffff814b7976)
Location: include/linux/eventfd.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
```
```
In mm/vmpressure.c (ffffffff814c0faa)
Location: include/linux/eventfd.h:87
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In fs/aio.c (ffffffff8155d830)
Location: include/linux/eventfd.h:87
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81caf1ef)
Location: include/linux/eventfd.h:87
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:syncobj_eventfd_entry_fence_func
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffff8000103f6110)
Location: fs/eventfd.c:61
Inline: False
Direct callers:
  - virt/kvm/eventfd.c:ioeventfd_write
  - virt/kvm/eventfd.c:irqfd_resampler_ack
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
  - fs/io_uring.c:io_cqring_ev_posted
```
**Symbols:**

```
ffff8000103f6110-ffff8000103f6274: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (c05ca558)
Location: fs/eventfd.c:61
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
  - fs/io_uring.c:io_cqring_ev_posted
```
**Symbols:**

```
c05ca558-c05ca698: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (c0000000004fd9f0)
Location: fs/eventfd.c:61
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_cqring_ev_posted
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_send_intx_eventfd
```
**Symbols:**

```
c0000000004fd9f0-c0000000004fdb5c: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffe0002a63f6)
Location: fs/eventfd.c:61
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:aio_complete
  - fs/io_uring.c:io_cqring_ev_posted
```
**Symbols:**

```
ffffffe0002a63f6-ffffffe0002a64ec: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8132fed0)
Location: fs/eventfd.c:61
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_cqring_ev_posted
```
**Symbols:**

```
ffffffff8132fed0-ffffffff8132ff73: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81320af0)
Location: fs/eventfd.c:61
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_cqring_ev_posted
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_send_intx_eventfd
```
**Symbols:**

```
ffffffff81320af0-ffffffff81320b93: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8132d9a0)
Location: fs/eventfd.c:61
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_cqring_ev_posted
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_send_intx_eventfd
```
**Symbols:**

```
ffffffff8132d9a0-ffffffff8132da43: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__u64 eventfd_signal(struct eventfd_ctx *ctx, __u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81340310)
Location: fs/eventfd.c:61
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/vmpressure.c:vmpressure_work_fn
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:io_cqring_ev_posted
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_request
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msihandler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_send_intx_eventfd
```
**Symbols:**

```
ffffffff81340310-ffffffff813403b3: eventfd_signal (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
