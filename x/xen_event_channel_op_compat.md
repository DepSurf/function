# Function: <code>xen_event_channel_op_compat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xen_event_channel_op_compat(int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/fallback.c (ffffffff814c46b0)
Location: drivers/xen/fallback.c:8
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
**Symbols:**

```
ffffffff814c46b0-ffffffff814c4766: xen_event_channel_op_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xen_event_channel_op_compat(int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/fallback.c (ffffffff81514e30)
Location: drivers/xen/fallback.c:8
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
**Symbols:**

```
ffffffff81514e30-ffffffff81514ee6: xen_event_channel_op_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xen_event_channel_op_compat(int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/fallback.c (ffffffff815412c0)
Location: drivers/xen/fallback.c:8
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
**Symbols:**

```
ffffffff815412c0-ffffffff81541376: xen_event_channel_op_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_event_channel_op_compat(int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/fallback.c (ffffffff81555150)
Location: drivers/xen/fallback.c:8
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
**Symbols:**

```
ffffffff81555150-ffffffff815551ef: xen_event_channel_op_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_event_channel_op_compat(int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/fallback.c (ffffffff815b8ca0)
Location: drivers/xen/fallback.c:8
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
**Symbols:**

```
ffffffff815b8ca0-ffffffff815b8d45: xen_event_channel_op_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_event_channel_op_compat(int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/fallback.c (ffffffff815f1260)
Location: drivers/xen/fallback.c:8
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
**Symbols:**

```
ffffffff815f1260-ffffffff815f1305: xen_event_channel_op_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xen_event_channel_op_compat(int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/fallback.c (ffffffff8160bea0)
Location: drivers/xen/fallback.c:8
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
**Symbols:**

```
ffffffff8160bea0-ffffffff8160bf4d: xen_event_channel_op_compat (STB_GLOBAL)
```
</details>
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
</ul>
