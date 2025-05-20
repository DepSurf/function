# Function: <code>__irq_get_desc_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810da330)
Location: kernel/irq/irqdesc.c:538
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/chip.c:irq_set_chip
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
```
**Symbols:**

```
ffffffff810da330-ffffffff810da3b7: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810df830)
Location: kernel/irq/irqdesc.c:599
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
```
**Symbols:**

```
ffffffff810df830-ffffffff810df8b7: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e6110)
Location: kernel/irq/irqdesc.c:787
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
```
**Symbols:**

```
ffffffff810e6110-ffffffff810e6191: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5760)
Location: kernel/irq/irqdesc.c:804
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
```
**Symbols:**

```
ffffffff810e5760-ffffffff810e57e5: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810eda20)
Location: kernel/irq/irqdesc.c:793
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
```
**Symbols:**

```
ffffffff810eda20-ffffffff810edaa8: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810f5e60)
Location: kernel/irq/irqdesc.c:810
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
```
**Symbols:**

```
ffffffff810f5e60-ffffffff810f5ee8: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811015f0)
Location: kernel/irq/irqdesc.c:815
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
```
**Symbols:**

```
ffffffff811015f0-ffffffff81101678: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81109df0)
Location: kernel/irq/irqdesc.c:870
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
```
**Symbols:**

```
ffffffff81109df0-ffffffff81109e79: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811161c0)
Location: kernel/irq/irqdesc.c:870
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffffffff811161c0-ffffffff81116249: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81121e70)
Location: kernel/irq/irqdesc.c:876
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffffffff81121e70-ffffffff81121ef9: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111def0)
Location: kernel/irq/irqdesc.c:827
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffffffff8111def0-ffffffff8111df79: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111e190)
Location: kernel/irq/irqdesc.c:827
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffffffff8111e190-ffffffff8111e219: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113e610)
Location: kernel/irq/irqdesc.c:839
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffffffff8113e610-ffffffff8113e699: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81161bb0)
Location: kernel/irq/irqdesc.c:816
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffffffff81161bb0-ffffffff81161c44: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81195380)
Location: kernel/irq/irqdesc.c:843
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffffffff81195380-ffffffff81195414: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a6d50)
Location: kernel/irq/irqdesc.c:862
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffffffff811a6d50-ffffffff811a6de4: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b6870)
Location: kernel/irq/irqdesc.c:862
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_apply_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffffffff811b6870-ffffffff811b6904: __irq_get_desc_lock (STB_GLOBAL)
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
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff800010177d70)
Location: kernel/irq/irqdesc.c:870
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffff800010177d70-ffff800010177e74: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c03c9728)
Location: kernel/irq/irqdesc.c:870
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
c03c9728-c03c97d8: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c0000000001d17c0)
Location: kernel/irq/irqdesc.c:870
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
c0000000001d17c0-c0000000001d18c0: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe0001129dc)
Location: kernel/irq/irqdesc.c:870
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
```
**Symbols:**

```
ffffffe0001129dc-ffffffe000112a6a: __irq_get_desc_lock (STB_GLOBAL)
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
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110e7a0)
Location: kernel/irq/irqdesc.c:870
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffffffff8110e7a0-ffffffff8110e829: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810ff4f0)
Location: kernel/irq/irqdesc.c:870
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffffffff810ff4f0-ffffffff810ff579: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110c690)
Location: kernel/irq/irqdesc.c:870
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffffffff8110c690-ffffffff8110c719: __irq_get_desc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irq_desc *__irq_get_desc_lock(unsigned int irq, long unsigned int *flags, bool bus, unsigned int check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81117ba0)
Location: kernel/irq/irqdesc.c:870
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_irqchip_state
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_irq_wake
  - kernel/irq/manage.c:enable_irq
  - kernel/irq/manage.c:__disable_irq_nosync
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_irq_type
  - kernel/irq/chip.c:irq_set_chip
  - kernel/irq/pm.c:rearm_wake_irq
```
**Symbols:**

```
ffffffff81117ba0-ffffffff81117c29: __irq_get_desc_lock (STB_GLOBAL)
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
