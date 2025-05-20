# Function: <code>irq_get_desc_lock</code>

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
In kernel/irq/manage.c (ffffffff810dac36)
Location: kernel/irq/internals.h:152
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_vcpu_affinity
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_set_affinity_hint
  - kernel/irq/manage.c:can_request_irq
  - kernel/irq/manage.c:enable_percpu_irq
```
```
In kernel/irq/chip.c (ffffffff810dd836)
Location: kernel/irq/internals.h:152
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
In kernel/irq/manage.c (ffffffff810e08b6)
Location: kernel/irq/internals.h:159
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
In kernel/irq/chip.c (ffffffff810e31a6)
Location: kernel/irq/internals.h:159
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
In kernel/irq/manage.c (ffffffff810e72d6)
Location: kernel/irq/internals.h:159
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
In kernel/irq/chip.c (ffffffff810e9a86)
Location: kernel/irq/internals.h:159
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
In kernel/irq/manage.c (ffffffff810e68d6)
Location: kernel/irq/internals.h:174
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
In kernel/irq/chip.c (ffffffff810e8f76)
Location: kernel/irq/internals.h:174
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
In kernel/irq/manage.c (ffffffff810eed36)
Location: kernel/irq/internals.h:177
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
In kernel/irq/chip.c (ffffffff810f13d6)
Location: kernel/irq/internals.h:177
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
In kernel/irq/manage.c (ffffffff810f7152)
Location: kernel/irq/internals.h:177
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
In kernel/irq/chip.c (ffffffff810f983d)
Location: kernel/irq/internals.h:177
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
In kernel/irq/manage.c (ffffffff811028b7)
Location: kernel/irq/internals.h:177
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
In kernel/irq/chip.c (ffffffff81104fed)
Location: kernel/irq/internals.h:177
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
In kernel/irq/manage.c (ffffffff8110d649)
Location: kernel/irq/internals.h:184
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
In kernel/irq/chip.c (ffffffff8110e2cd)
Location: kernel/irq/internals.h:184
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
In kernel/irq/manage.c (ffffffff81119a39)
Location: kernel/irq/internals.h:182
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
In kernel/irq/chip.c (ffffffff8111a58d)
Location: kernel/irq/internals.h:182
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
In kernel/irq/manage.c (ffffffff81125309)
Location: kernel/irq/internals.h:182
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
In kernel/irq/chip.c (ffffffff8112660d)
Location: kernel/irq/internals.h:182
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
In kernel/irq/manage.c (ffffffff81121169)
Location: kernel/irq/internals.h:182
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
In kernel/irq/chip.c (ffffffff8112224d)
Location: kernel/irq/internals.h:182
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
In kernel/irq/manage.c (ffffffff81121449)
Location: kernel/irq/internals.h:182
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
In kernel/irq/chip.c (ffffffff811225cd)
Location: kernel/irq/internals.h:182
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
In kernel/irq/manage.c (ffffffff811419c9)
Location: kernel/irq/internals.h:182
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
In kernel/irq/chip.c (ffffffff81142b7d)
Location: kernel/irq/internals.h:182
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
In kernel/irq/manage.c (ffffffff8116546e)
Location: kernel/irq/internals.h:184
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
In kernel/irq/chip.c (ffffffff81166825)
Location: kernel/irq/internals.h:184
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
In kernel/irq/manage.c (ffffffff81199361)
Location: kernel/irq/internals.h:186
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
In kernel/irq/chip.c (ffffffff8119aad5)
Location: kernel/irq/internals.h:186
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
In kernel/irq/manage.c (ffffffff811ab041)
Location: kernel/irq/internals.h:191
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
In kernel/irq/chip.c (ffffffff811ac835)
Location: kernel/irq/internals.h:191
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
In kernel/irq/manage.c (ffffffff811bac81)
Location: kernel/irq/internals.h:191
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
In kernel/irq/chip.c (ffffffff811bc435)
Location: kernel/irq/internals.h:191
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
In kernel/irq/manage.c (ffff80001017c7f8)
Location: kernel/irq/internals.h:182
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
In kernel/irq/chip.c (ffff80001017dbfc)
Location: kernel/irq/internals.h:182
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
In kernel/irq/manage.c (c03cd6d4)
Location: kernel/irq/internals.h:182
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
In kernel/irq/chip.c (c03ce3e4)
Location: kernel/irq/internals.h:182
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
In kernel/irq/manage.c (c0000000001d74bc)
Location: kernel/irq/internals.h:182
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
In kernel/irq/chip.c (c0000000001d84f4)
Location: kernel/irq/internals.h:182
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
In kernel/irq/manage.c (ffffffe000115d9c)
Location: kernel/irq/internals.h:182
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
In kernel/irq/chip.c (ffffffe00011680a)
Location: kernel/irq/internals.h:182
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
In kernel/irq/manage.c (ffffffff81112019)
Location: kernel/irq/internals.h:182
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
In kernel/irq/chip.c (ffffffff81112b6d)
Location: kernel/irq/internals.h:182
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
In kernel/irq/manage.c (ffffffff81102d49)
Location: kernel/irq/internals.h:182
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
In kernel/irq/chip.c (ffffffff8110388d)
Location: kernel/irq/internals.h:182
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
In kernel/irq/manage.c (ffffffff8110ff09)
Location: kernel/irq/internals.h:182
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
In kernel/irq/chip.c (ffffffff81110a5d)
Location: kernel/irq/internals.h:182
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
In kernel/irq/manage.c (ffffffff8111b468)
Location: kernel/irq/internals.h:182
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
In kernel/irq/chip.c (ffffffff8111bfdd)
Location: kernel/irq/internals.h:182
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
