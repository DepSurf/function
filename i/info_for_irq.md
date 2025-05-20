# Function: <code>info_for_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c78bc)
Location: drivers/xen/events/events_base.c:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
**Symbols:**

```
ffffffff814c80b0-ffffffff814c80d1: info_for_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8151832c)
Location: drivers/xen/events/events_base.c:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
**Symbols:**

```
ffffffff81518b50-ffffffff81518b71: info_for_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8154483c)
Location: drivers/xen/events/events_base.c:155
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
**Symbols:**

```
ffffffff81545040-ffffffff81545061: info_for_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8155863c)
Location: drivers/xen/events/events_base.c:155
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
**Symbols:**

```
ffffffff81558f80-ffffffff81558fa1: info_for_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bca7c)
Location: drivers/xen/events/events_base.c:155
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
**Symbols:**

```
ffffffff815bd360-ffffffff815bd381: info_for_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f512c)
Location: drivers/xen/events/events_base.c:155
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
**Symbols:**

```
ffffffff815f5a10-ffffffff815f5a31: info_for_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8161021c)
Location: drivers/xen/events/events_base.c:155
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
**Symbols:**

```
ffffffff81610ae0-ffffffff81610afd: info_for_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81643e8c)
Location: drivers/xen/events/events_base.c:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
**Symbols:**

```
ffffffff81644760-ffffffff8164477d: info_for_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8166643c)
Location: drivers/xen/events/events_base.c:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
**Symbols:**

```
ffffffff81666d10-ffffffff81666d2d: info_for_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8171605c)
Location: drivers/xen/events/events_base.c:159
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:cpu_from_evtchn
```
**Symbols:**

```
ffffffff81716b50-ffffffff81716b7f: info_for_irq (STB_GLOBAL)
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
In drivers/xen/events/events_base.c (ffffffff817330bc)
Location: drivers/xen/events/events_base.c:255
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:cpu_from_evtchn
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
In drivers/xen/events/events_base.c (ffffffff817198c8)
Location: drivers/xen/events/events_base.c:265
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:cpu_from_evtchn
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
In drivers/xen/events/events_base.c (ffffffff8179777c)
Location: drivers/xen/events/events_base.c:265
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:cpu_from_evtchn
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
In drivers/xen/events/events_base.c (ffffffff818d07eb)
Location: drivers/xen/events/events_base.c:265
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:cpu_from_evtchn
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
In drivers/xen/events/events_base.c (ffffffff81a21fea)
Location: drivers/xen/events/events_base.c:266
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:cpu_from_evtchn
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
In drivers/xen/events/events_base.c (ffffffff81a6b381)
Location: drivers/xen/events/events_base.c:267
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:cpu_from_evtchn
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
In drivers/xen/events/events_base.c (ffffffff81abd450)
Location: drivers/xen/events/events_base.c:251
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:startup_pirq
  - drivers/xen/events/events_base.c:startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_base.c:irq_evtchn_from_virq
  - drivers/xen/events/events_base.c:irq_evtchn_from_virq
  - drivers/xen/events/events_base.c:evtchn_to_info
  - drivers/xen/events/events_base.c:evtchn_to_info
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff80001082fdf8)
Location: drivers/xen/events/events_base.c:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
**Symbols:**

```
ffff800010830968-ffff8000108309a0: info_for_irq (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162c16c)
Location: drivers/xen/events/events_base.c:160
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
**Symbols:**

```
ffffffff8162ca40-ffffffff8162ca5d: info_for_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165a27c)
Location: drivers/xen/events/events_base.c:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
**Symbols:**

```
ffffffff8165ab50-ffffffff8165ab6d: info_for_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct irq_info *info_for_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8167484c)
Location: drivers/xen/events/events_base.c:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
**Symbols:**

```
ffffffff81675140-ffffffff8167515d: info_for_irq (STB_GLOBAL)
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
