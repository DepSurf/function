# Function: <code>irq_data_get_node</code>

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
Location: include/linux/irq.h:667
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irq.h:667
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
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irq.h:696
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
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irq.h:713
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
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irq.h:763
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
In arch/x86/kernel/apic/vector.c (ffffffff8105bfce)
Location: include/linux/irq.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/irqdomain.c (ffffffff810f5355)
Location: include/linux/irq.h:792
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
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
Location: include/linux/irq.h:794
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/irqdomain.c (ffffffff810fd725)
Location: include/linux/irq.h:794
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/irqdomain.c (ffffffff81108b75)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/irqdomain.c (ffffffff8111215c)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109849f)
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdomain.c (ffffffff8111e3dc)
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
Location: include/linux/irq.h:856
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109dc8f)
Location: include/linux/irq.h:856
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdomain.c (ffffffff8112b0bc)
Location: include/linux/irq.h:856
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
Location: include/linux/irq.h:869
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109985f)
Location: include/linux/irq.h:869
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdomain.c (ffffffff81126b4c)
Location: include/linux/irq.h:869
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
Location: include/linux/irq.h:871
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109a06f)
Location: include/linux/irq.h:871
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdomain.c (ffffffff81126b8c)
Location: include/linux/irq.h:871
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
Location: include/linux/irq.h:873
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810aa08f)
Location: include/linux/irq.h:873
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdomain.c (ffffffff811470fc)
Location: include/linux/irq.h:873
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
Location: include/linux/irq.h:877
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810bfabf)
Location: include/linux/irq.h:877
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdomain.c (ffffffff8116b96c)
Location: include/linux/irq.h:877
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
Location: include/linux/irq.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810db99f)
Location: include/linux/irq.h:879
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdomain.c (ffffffff811a0b3c)
Location: include/linux/irq.h:879
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
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
Location: include/linux/irq.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810e6f2f)
Location: include/linux/irq.h:892
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdomain.c (ffffffff811b29ef)
Location: include/linux/irq.h:892
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
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
Location: include/linux/irq.h:874
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810ef2af)
Location: include/linux/irq.h:874
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdomain.c (ffffffff811c27df)
Location: include/linux/irq.h:874
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010183ba8)
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/irq.h:826
Inline: True
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irq.h:826
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
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/irqdomain.c (ffffffff811169bc)
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/irqdomain.c (ffffffff811076ac)
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/irqdomain.c (ffffffff811148ac)
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109996f)
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdomain.c (ffffffff8111fedc)
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
</details>
</li>
</ul>

## Differences
