# Function: <code>weak_wrmsr_fence</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106e3b5)
Location: arch/x86/include/asm/barrier.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8107595a)
Location: arch/x86/include/asm/barrier.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075df5)
Location: arch/x86/include/asm/barrier.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/apic.c (ffffffff8106ef85)
Location: arch/x86/include/asm/barrier.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810763fa)
Location: arch/x86/include/asm/barrier.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076875)
Location: arch/x86/include/asm/barrier.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/apic.c (ffffffff8107a975)
Location: arch/x86/include/asm/barrier.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81083a4a)
Location: arch/x86/include/asm/barrier.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083fe5)
Location: arch/x86/include/asm/barrier.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/apic.c (ffffffff81089985)
Location: arch/x86/include/asm/barrier.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81093a2a)
Location: arch/x86/include/asm/barrier.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810940e5)
Location: arch/x86/include/asm/barrier.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/apic.c (ffffffff8109d885)
Location: arch/x86/include/asm/barrier.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a915a)
Location: arch/x86/include/asm/barrier.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9715)
Location: arch/x86/include/asm/barrier.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/apic.c (ffffffff810a0865)
Location: arch/x86/include/asm/barrier.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810ac31a)
Location: arch/x86/include/asm/barrier.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac925)
Location: arch/x86/include/asm/barrier.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/apic.c (ffffffff810a7fa5)
Location: arch/x86/include/asm/processor.h:765
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2eda)
Location: arch/x86/include/asm/processor.h:765
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b35a5)
Location: arch/x86/include/asm/processor.h:765
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
