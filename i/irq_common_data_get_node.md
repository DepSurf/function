# Function: <code>irq_common_data_get_node</code>

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
In arch/x86/kernel/apic/vector.c (ffffffff810555ee)
Location: include/linux/irq.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/manage.c (0)
Location: include/linux/irq.h:658
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irq.h:658
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/irq.h:658
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff8105588f)
Location: include/linux/irq.h:687
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/manage.c (0)
Location: include/linux/irq.h:687
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irq.h:687
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/irq.h:687
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff8105850f)
Location: include/linux/irq.h:704
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/manage.c (0)
Location: include/linux/irq.h:704
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irq.h:704
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/irq.h:704
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff81057df5)
Location: include/linux/irq.h:754
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/manage.c (0)
Location: include/linux/irq.h:754
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irq.h:754
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/irq.h:754
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff8105bfd2)
Location: include/linux/irq.h:783
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/manage.c (0)
Location: include/linux/irq.h:783
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irq.h:783
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/irq.h:783
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff8105eee1)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/manage.c (ffffffff810f7ec5)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff810fd725)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffffffff810fe5b5)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff810648c1)
Location: include/linux/irq.h:786
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/manage.c (ffffffff81103615)
Location: include/linux/irq.h:786
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff81108b75)
Location: include/linux/irq.h:786
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffffffff81109d85)
Location: include/linux/irq.h:786
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff81067fa6)
Location: include/linux/irq.h:799
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/manage.c (ffffffff8110c035)
Location: include/linux/irq.h:799
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff8111215c)
Location: include/linux/irq.h:799
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffffffff81113476)
Location: include/linux/irq.h:799
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff810688e6)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109849f)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/manage.c (ffffffff81118465)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff8111e3dc)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffffffff8111f5f6)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff8106fe83)
Location: include/linux/irq.h:847
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109dc8f)
Location: include/linux/irq.h:847
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/manage.c (ffffffff81123d55)
Location: include/linux/irq.h:847
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff8112b0bc)
Location: include/linux/irq.h:847
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffffffff8112bb36)
Location: include/linux/irq.h:847
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff810712d7)
Location: include/linux/irq.h:860
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109985f)
Location: include/linux/irq.h:860
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/manage.c (ffffffff8111fbb5)
Location: include/linux/irq.h:860
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff81126b4c)
Location: include/linux/irq.h:860
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffffffff81127556)
Location: include/linux/irq.h:860
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff81071b63)
Location: include/linux/irq.h:862
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109a06f)
Location: include/linux/irq.h:862
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/manage.c (ffffffff8111fe75)
Location: include/linux/irq.h:862
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff81126b8c)
Location: include/linux/irq.h:862
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffffffff81127816)
Location: include/linux/irq.h:862
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff8107d963)
Location: include/linux/irq.h:864
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810aa08f)
Location: include/linux/irq.h:864
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/manage.c (ffffffff81140385)
Location: include/linux/irq.h:864
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff811470fc)
Location: include/linux/irq.h:864
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffffffff81147d86)
Location: include/linux/irq.h:864
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff8108d19c)
Location: include/linux/irq.h:868
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810bfabf)
Location: include/linux/irq.h:868
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/manage.c (ffffffff81163ce2)
Location: include/linux/irq.h:868
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff8116b96c)
Location: include/linux/irq.h:868
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffffffff8116c765)
Location: include/linux/irq.h:868
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff810a0e0b)
Location: include/linux/irq.h:870
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810db99f)
Location: include/linux/irq.h:870
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/manage.c (ffffffff81197a02)
Location: include/linux/irq.h:870
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff811a0b3c)
Location: include/linux/irq.h:870
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
```
```
In kernel/irq/proc.c (ffffffff811a1785)
Location: include/linux/irq.h:870
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff810a3e0c)
Location: include/linux/irq.h:883
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810e6f2f)
Location: include/linux/irq.h:883
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/manage.c (ffffffff811a96c2)
Location: include/linux/irq.h:883
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff811b29ef)
Location: include/linux/irq.h:883
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
```
```
In kernel/irq/proc.c (ffffffff811b35a5)
Location: include/linux/irq.h:883
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff810ab80a)
Location: include/linux/irq.h:865
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810ef2af)
Location: include/linux/irq.h:865
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/manage.c (ffffffff811b9222)
Location: include/linux/irq.h:865
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff811c27df)
Location: include/linux/irq.h:865
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
```
```
In kernel/irq/proc.c (ffffffff811c3425)
Location: include/linux/irq.h:865
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In kernel/irq/manage.c (ffff80001017acd8)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffff800010183ba8)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffff800010185258)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In kernel/irq/manage.c (0)
Location: include/linux/irq.h:817
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irq.h:817
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/irq.h:817
Inline: True
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
In kernel/irq/manage.c (c0000000001d5248)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (c0000000001df6b0)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In kernel/irq/manage.c (0)
Location: include/linux/irq.h:817
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irq.h:817
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/irq.h:817
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff810683d6)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/manage.c (ffffffff81110a45)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff811169bc)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffffffff81117bd6)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff81058746)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/manage.c (ffffffff81101775)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff811076ac)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffffffff81108c46)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff81068886)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/manage.c (ffffffff8110e935)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff811148ac)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffffffff81115ac6)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
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
In arch/x86/kernel/apic/vector.c (ffffffff81069fd6)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109996f)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/manage.c (ffffffff81119e65)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/irqdomain.c (ffffffff8111fedc)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/irq/proc.c (ffffffff811210f6)
Location: include/linux/irq.h:817
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_node_proc_show
```
</details>
</li>
</ul>

## Differences
