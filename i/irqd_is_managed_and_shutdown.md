# Function: <code>irqd_is_managed_and_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:365
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
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/irq.h:377
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:377
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
In arch/x86/kernel/apic/vector.c (ffffffff8105f21f)
Location: include/linux/irq.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff810ff777)
Location: include/linux/irq.h:372
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81064e8f)
Location: include/linux/irq.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff8110af77)
Location: include/linux/irq.h:373
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8106862a)
Location: include/linux/irq.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff81114639)
Location: include/linux/irq.h:373
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81068f6a)
Location: include/linux/irq.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff81120799)
Location: include/linux/irq.h:376
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8106f866)
Location: include/linux/irq.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112cd36)
Location: include/linux/irq.h:392
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81070d76)
Location: include/linux/irq.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff81128766)
Location: include/linux/irq.h:402
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8107150a)
Location: include/linux/irq.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff811289c4)
Location: include/linux/irq.h:402
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8107d2fa)
Location: include/linux/irq.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff81148fa4)
Location: include/linux/irq.h:404
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8108c9cc)
Location: include/linux/irq.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff8116db24)
Location: include/linux/irq.h:404
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff810a0fc4)
Location: include/linux/irq.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a2d54)
Location: include/linux/irq.h:406
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff810a3fb4)
Location: include/linux/irq.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b4c54)
Location: include/linux/irq.h:409
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff810aafe4)
Location: include/linux/irq.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c4ad4)
Location: include/linux/irq.h:406
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In kernel/irq/cpuhotplug.c (ffff8000101865ec)
Location: include/linux/irq.h:376
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In kernel/irq/cpuhotplug.c (c03d5354)
Location: include/linux/irq.h:376
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In kernel/irq/cpuhotplug.c (c0000000001e0de4)
Location: include/linux/irq.h:376
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/apic/vector.c (ffffffff81068a5a)
Location: include/linux/irq.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff81118d79)
Location: include/linux/irq.h:376
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81058dca)
Location: include/linux/irq.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff81109de9)
Location: include/linux/irq.h:376
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81068f0a)
Location: include/linux/irq.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff81116c69)
Location: include/linux/irq.h:376
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8106a60e)
Location: include/linux/irq.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/irq/cpuhotplug.c (ffffffff811222e9)
Location: include/linux/irq.h:376
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
</details>
</li>
</ul>

## Differences
