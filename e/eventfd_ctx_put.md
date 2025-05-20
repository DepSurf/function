# Function: <code>eventfd_ctx_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81259289)
Location: fs/eventfd.c:102
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:memcg_write_event_control
  - fs/aio.c:kiocb_free
```
**Symbols:**

```
ffffffff812592b0-ffffffff812592c7: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81281c69)
Location: fs/eventfd.c:102
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:kiocb_free
```
**Symbols:**

```
ffffffff81281c80-ffffffff81281c97: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81295799)
Location: fs/eventfd.c:102
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:kiocb_free
```
**Symbols:**

```
ffffffff812957b0-ffffffff812957c7: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812a2890)
Location: fs/eventfd.c:102
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/eventfd.c:eventfd_release
  - fs/aio.c:kiocb_free
```
**Symbols:**

```
ffffffff812a2890-ffffffff812a28a7: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812c5d19)
Location: fs/eventfd.c:102
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:kiocb_free
```
**Symbols:**

```
ffffffff812c5d40-ffffffff812c5d5b: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812eefe9)
Location: fs/eventfd.c:89
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff812ef040-ffffffff812ef05d: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81303979)
Location: fs/eventfd.c:89
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff813039a0-ffffffff813039bd: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81324f3b)
Location: fs/eventfd.c:96
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff81324f60-ffffffff81324f7c: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81337ccb)
Location: fs/eventfd.c:111
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
**Symbols:**

```
ffffffff81337cf0-ffffffff81337d0c: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81371a0b)
Location: fs/eventfd.c:112
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff81371970-ffffffff813719d1: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8137f7cb)
Location: fs/eventfd.c:112
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff8137f730-ffffffff8137f791: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8138644b)
Location: fs/eventfd.c:112
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff813863b0-ffffffff81386411: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813d371b)
Location: fs/eventfd.c:110
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_close_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_close_device
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff813d3680-ffffffff813d36e1: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8145cf89)
Location: fs/eventfd.c:110
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - io_uring/io_uring.c:io_eventfd_put
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_close_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_close_device
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_ctx_trigger_single
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
**Symbols:**

```
ffffffff8145cee0-ffffffff8145cf5e: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff814ec719)
Location: fs/eventfd.c:115
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - io_uring/io_uring.c:io_eventfd_ops
```
**Symbols:**

```
ffffffff814ec660-ffffffff814ec6de: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81523669)
Location: fs/eventfd.c:115
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - io_uring/io_uring.c:io_eventfd_ops
```
**Symbols:**

```
ffffffff815235b0-ffffffff8152362e: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81557d99)
Location: fs/eventfd.c:103
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - io_uring/io_uring.c:io_eventfd_ops
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_eventfd_ioctl
  - drivers/gpu/drm/drm_syncobj.c:syncobj_eventfd_entry_fence_func
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_free
```
**Symbols:**

```
ffffffff81557ce0-ffffffff81557d5e: eventfd_ctx_put (STB_GLOBAL)
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
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffff8000103f5bb8)
Location: fs/eventfd.c:111
Inline: False
Direct callers:
  - virt/kvm/eventfd.c:kvm_deassign_ioeventfd_idx
  - virt/kvm/eventfd.c:kvm_deassign_ioeventfd_idx
  - virt/kvm/eventfd.c:kvm_assign_ioeventfd_idx
  - virt/kvm/eventfd.c:ioeventfd_destructor
  - virt/kvm/eventfd.c:kvm_irqfd
  - virt/kvm/eventfd.c:kvm_irqfd_assign
  - virt/kvm/eventfd.c:kvm_irqfd_assign
  - virt/kvm/eventfd.c:irqfd_shutdown
  - virt/kvm/eventfd.c:irqfd_shutdown
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/eventfd.c:eventfd_release
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffff8000103f5bb8-ffff8000103f5bf4: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (c05ca7a0)
Location: fs/eventfd.c:111
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/eventfd.c:eventfd_release
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
c05ca7a0-c05ca7d0: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (c0000000004fdd10)
Location: fs/eventfd.c:111
Inline: False
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/eventfd.c:eventfd_release
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
**Symbols:**

```
c0000000004fdd10-c0000000004fdd48: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffe0002a67f2)
Location: fs/eventfd.c:111
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffe0002a65d4-ffffffe0002a6616: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813302ab)
Location: fs/eventfd.c:111
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff813302d0-ffffffff813302ec: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81320ecb)
Location: fs/eventfd.c:111
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
**Symbols:**

```
ffffffff81320ef0-ffffffff81320f0c: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8132dd7b)
Location: fs/eventfd.c:111
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
**Symbols:**

```
ffffffff8132dda0-ffffffff8132ddbc: eventfd_ctx_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_put(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81340b5b)
Location: fs/eventfd.c:111
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
**Symbols:**

```
ffffffff81340b80-ffffffff81340b9c: eventfd_ctx_put (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
