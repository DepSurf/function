# Function: <code>__irq_put_desc_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810da3c0)
Location: kernel/irq/irqdesc.c:561
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
ffffffff810da3c0-ffffffff810da3fd: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810df8c0)
Location: kernel/irq/irqdesc.c:622
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
ffffffff810df8c0-ffffffff810df900: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e61a0)
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
ffffffff810e61a0-ffffffff810e61e0: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e57f0)
Location: kernel/irq/irqdesc.c:827
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
ffffffff810e57f0-ffffffff810e5830: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810edab0)
Location: kernel/irq/irqdesc.c:816
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
ffffffff810edab0-ffffffff810edaf3: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810f5ef0)
Location: kernel/irq/irqdesc.c:833
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
ffffffff810f5ef0-ffffffff810f5f33: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81101680)
Location: kernel/irq/irqdesc.c:838
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
ffffffff81101680-ffffffff811016c3: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81109e80)
Location: kernel/irq/irqdesc.c:893
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
ffffffff81109e80-ffffffff81109ec3: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81116250)
Location: kernel/irq/irqdesc.c:893
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
ffffffff81116250-ffffffff81116293: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81121f00)
Location: kernel/irq/irqdesc.c:899
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
ffffffff81121f00-ffffffff81121f43: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111df80)
Location: kernel/irq/irqdesc.c:850
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
ffffffff8111df80-ffffffff8111dfc3: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111e220)
Location: kernel/irq/irqdesc.c:850
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
ffffffff8111e220-ffffffff8111e263: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113e6a0)
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
ffffffff8113e6a0-ffffffff8113e6e3: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81161c50)
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
ffffffff81161c50-ffffffff81161c9c: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81195430)
Location: kernel/irq/irqdesc.c:866
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
ffffffff81195430-ffffffff8119547c: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a6e00)
Location: kernel/irq/irqdesc.c:885
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
ffffffff811a6e00-ffffffff811a6e4c: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b6920)
Location: kernel/irq/irqdesc.c:885
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
ffffffff811b6920-ffffffff811b696c: __irq_put_desc_unlock (STB_GLOBAL)
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
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff800010177e78)
Location: kernel/irq/irqdesc.c:893
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
ffff800010177e78-ffff800010177edc: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c03c97d8)
Location: kernel/irq/irqdesc.c:893
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
c03c97d8-c03c9820: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c0000000001d18c0)
Location: kernel/irq/irqdesc.c:893
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
c0000000001d18c0-c0000000001d1948: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe000112a6a)
Location: kernel/irq/irqdesc.c:893
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
ffffffe000112a6a-ffffffe000112ab6: __irq_put_desc_unlock (STB_GLOBAL)
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
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110e830)
Location: kernel/irq/irqdesc.c:893
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
ffffffff8110e830-ffffffff8110e873: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810ff580)
Location: kernel/irq/irqdesc.c:893
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
ffffffff810ff580-ffffffff810ff5c3: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110c720)
Location: kernel/irq/irqdesc.c:893
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
ffffffff8110c720-ffffffff8110c763: __irq_put_desc_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __irq_put_desc_unlock(struct irq_desc *desc, long unsigned int flags, bool bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81117c30)
Location: kernel/irq/irqdesc.c:893
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
ffffffff81117c30-ffffffff81117c73: __irq_put_desc_unlock (STB_GLOBAL)
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
