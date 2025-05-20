# Function: <code>irq_put_desc_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810dac90)
Location: kernel/irq/internals.h:158
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:enable_percpu_irq
```
```
In kernel/irq/chip.c (ffffffff810dd86c)
Location: kernel/irq/internals.h:158
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_msi_desc_off
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e08fa)
Location: kernel/irq/internals.h:165
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff810e3254)
Location: kernel/irq/internals.h:165
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e731a)
Location: kernel/irq/internals.h:165
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff810e9b1e)
Location: kernel/irq/internals.h:165
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e691a)
Location: kernel/irq/internals.h:180
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff810e9037)
Location: kernel/irq/internals.h:180
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810eed7a)
Location: kernel/irq/internals.h:183
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff810f1497)
Location: kernel/irq/internals.h:183
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f716a)
Location: kernel/irq/internals.h:183
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff810f98de)
Location: kernel/irq/internals.h:183
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811028da)
Location: kernel/irq/internals.h:183
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff8110508e)
Location: kernel/irq/internals.h:183
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110d67a)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff8110e374)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81119a66)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff8111a634)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81125336)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff811266b4)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81121196)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff811222e8)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81121476)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff81122668)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811419f6)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff81142c18)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811654a5)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_apply_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff811668c0)
Location: kernel/irq/internals.h:190
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8119939b)
Location: kernel/irq/internals.h:192
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_apply_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff8119ab70)
Location: kernel/irq/internals.h:192
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811ab07b)
Location: kernel/irq/internals.h:197
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_apply_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff811ac8d0)
Location: kernel/irq/internals.h:197
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
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
In kernel/irq/manage.c (ffffffff811bacbb)
Location: kernel/irq/internals.h:197
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:__irq_apply_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff811bc4d0)
Location: kernel/irq/internals.h:197
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc
  - kernel/irq/chip.c:irq_set_handler_data
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017c82c)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffff80001017dcc4)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cd704)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (c03ce4b0)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d750c)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:irq_set_parent
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (c0000000001d85e4)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000115dca)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffe0001168b4)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81112046)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff81112c14)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81102d76)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff81103934)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110ff36)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff81110b04)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111b4a0)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/manage.c:teardown_percpu_nmi
  - kernel/irq/manage.c:prepare_percpu_nmi
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:irq_set_affinity_hint
```
```
In kernel/irq/chip.c (ffffffff8111c084)
Location: kernel/irq/internals.h:188
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
  - kernel/irq/chip.c:irq_set_chip_data
  - kernel/irq/chip.c:irq_set_msi_desc_off
  - kernel/irq/chip.c:irq_set_handler_data
  - kernel/irq/chip.c:irq_set_chip
```
</details>
</li>
</ul>

## Differences
