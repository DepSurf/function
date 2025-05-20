# Function: <code>unbind_from_irqhandler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c8bc0)
Location: drivers/xen/events/events_base.c:1106
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff814c8bc0-ffffffff814c8c12: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815196e0)
Location: drivers/xen/events/events_base.c:1117
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815196e0-ffffffff81519732: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81545bb0)
Location: drivers/xen/events/events_base.c:1116
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff81545bb0-ffffffff81545c02: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81559a10)
Location: drivers/xen/events/events_base.c:1108
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81559a10-ffffffff81559a53: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bde60)
Location: drivers/xen/events/events_base.c:1108
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815bde60-ffffffff815bdea3: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f64c0)
Location: drivers/xen/events/events_base.c:1106
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_teardown_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815f64c0-ffffffff815f6500: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81611560)
Location: drivers/xen/events/events_base.c:1106
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_teardown_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81611560-ffffffff816115a0: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1107
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_teardown_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81646471-ffffffff81646484: unbind_from_irqhandler.cold (STB_LOCAL)
ffffffff81645320-ffffffff81645369: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816678c0)
Location: drivers/xen/events/events_base.c:1107
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_teardown_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff816678c0-ffffffff81667909: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81717880)
Location: drivers/xen/events/events_base.c:1122
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:setup_netfront_split
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff81717880-ffffffff817178fa: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81733ee0)
Location: drivers/xen/events/events_base.c:1504
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:setup_netfront_split
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff81733ee0-ffffffff81733f5a: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817179a0)
Location: drivers/xen/events/events_base.c:1541
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff817179a0-ffffffff81717a1a: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81795190)
Location: drivers/xen/events/events_base.c:1547
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff81795190-ffffffff8179521f: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cde80)
Location: drivers/xen/events/events_base.c:1547
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff818cde80-ffffffff818cdf21: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1f4b0)
Location: drivers/xen/events/events_base.c:1549
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff81a1f4b0-ffffffff81a1f551: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a686b0)
Location: drivers/xen/events/events_base.c:1542
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff81a686b0-ffffffff81a68751: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81ababe0)
Location: drivers/xen/events/events_base.c:1542
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff81ababe0-ffffffff81abaccc: unbind_from_irqhandler (STB_GLOBAL)
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
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010831740)
Location: drivers/xen/events/events_base.c:1107
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffff800010831740-ffff8000108317a4: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162d5f0)
Location: drivers/xen/events/events_base.c:1111
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_teardown_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8162d5f0-ffffffff8162d639: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165b700)
Location: drivers/xen/events/events_base.c:1107
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_teardown_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8165b700-ffffffff8165b749: unbind_from_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81675cf0)
Location: drivers/xen/events/events_base.c:1107
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_teardown_timer
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp.c:xen_smp_intr_free
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv
  - arch/x86/xen/spinlock.c:xen_uninit_lock_cpu
  - drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81675cf0-ffffffff81675d39: unbind_from_irqhandler (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
