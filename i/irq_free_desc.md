# Function: <code>irq_free_desc</code>

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
In kernel/irq/irqdomain.c (ffffffff810e06eb)
Location: include/linux/irq.h:706
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_dispose_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff814c79b4)
Location: include/linux/irq.h:706
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff810e6fa0)
Location: include/linux/irq.h:735
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff81518424)
Location: include/linux/irq.h:735
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff810ed990)
Location: include/linux/irq.h:752
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff81544934)
Location: include/linux/irq.h:752
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff810ed370)
Location: include/linux/irq.h:844
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff81558730)
Location: include/linux/irq.h:844
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff810f5d70)
Location: include/linux/irq.h:873
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff815bcb70)
Location: include/linux/irq.h:873
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff810fe11f)
Location: include/linux/irq.h:875
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff815f5215)
Location: include/linux/irq.h:875
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff811098ef)
Location: include/linux/irq.h:877
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff81610305)
Location: include/linux/irq.h:877
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff81112ee9)
Location: include/linux/irq.h:890
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff816440e3)
Location: include/linux/irq.h:890
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff8111f175)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff8166668b)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff8112b6b7)
Location: include/linux/irq.h:938
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff81716224)
Location: include/linux/irq.h:938
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff81127177)
Location: include/linux/irq.h:958
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff81733c95)
Location: include/linux/irq.h:958
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff811273f9)
Location: include/linux/irq.h:960
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff81717745)
Location: include/linux/irq.h:960
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff81147970)
Location: include/linux/irq.h:962
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff81794b59)
Location: include/linux/irq.h:962
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff8116bd3a)
Location: include/linux/irq.h:966
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff818cd7e3)
Location: include/linux/irq.h:966
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff811a0f3a)
Location: include/linux/irq.h:982
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
```
```
In drivers/xen/events/events_base.c (ffffffff81a1ede3)
Location: include/linux/irq.h:982
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff811b2daa)
Location: include/linux/irq.h:995
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
```
```
In drivers/xen/events/events_base.c (ffffffff81a67fc3)
Location: include/linux/irq.h:995
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff811c2bca)
Location: include/linux/irq.h:977
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
```
```
In drivers/xen/events/events_base.c (ffffffff81abc05e)
Location: include/linux/irq.h:977
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:xen_allocate_irq_dynamic
  - drivers/xen/events/events_base.c:delayed_free_irq
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
In kernel/irq/irqdomain.c (ffff800010184cd4)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffff80001082ffd0)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d3d74)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001ded0c)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011bb68)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
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
In kernel/irq/irqdomain.c (ffffffff81117755)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff8162c3bb)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81108445)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
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
In kernel/irq/irqdomain.c (ffffffff81115645)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff8165a4cb)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
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
In kernel/irq/irqdomain.c (ffffffff81120c75)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
```
```
In drivers/xen/events/events_base.c (ffffffff81674abb)
Location: include/linux/irq.h:908
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
```
</details>
</li>
</ul>

## Differences
