# Function: <code>__kstat_incr_irqs_this_cpu</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81109fab)
Location: kernel/irq/internals.h:252
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff8110a1c2)
Location: kernel/irq/internals.h:252
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff8110f739)
Location: kernel/irq/internals.h:252
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff8111637b)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff81116592)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff8111b9f9)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff81122027)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff811221be)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff81127d29)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff8111e0a7)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff8111e19e)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff811238cf)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff8111e347)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff8111e4ae)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff81123c2f)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff8113e7c7)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff8113e94e)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff8114421f)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff81161d77)
Location: kernel/irq/internals.h:252
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff81161f5e)
Location: kernel/irq/internals.h:252
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff81167d5f)
Location: kernel/irq/internals.h:252
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff81195587)
Location: kernel/irq/internals.h:254
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff811959ae)
Location: kernel/irq/internals.h:254
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff8119c1ef)
Location: kernel/irq/internals.h:254
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff811a6f57)
Location: kernel/irq/internals.h:259
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff811a737e)
Location: kernel/irq/internals.h:259
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff811ae04f)
Location: kernel/irq/internals.h:259
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff811b6ab7)
Location: kernel/irq/internals.h:259
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff811b6ede)
Location: kernel/irq/internals.h:259
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff811bdc4f)
Location: kernel/irq/internals.h:259
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffff800010177fe0)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffff80001017840c)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffff80001017ecc0)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (c03c9908)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (c03c9b98)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (c03cfd90)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (c0000000001d1aa4)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (c0000000001d224c)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (c0000000001da810)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffe000112ba4)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffe000112e68)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffe000117fa8)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff8110e95b)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff8110eb72)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff81113fd9)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff810ff6ab)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff810ff8c2)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff81104ce9)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff8110c84b)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff8110ca62)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff81111ec9)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff81117d5b)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff81117f92)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff8111d4b9)
Location: kernel/irq/internals.h:250
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
</details>
</li>
</ul>

## Differences
