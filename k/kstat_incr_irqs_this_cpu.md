# Function: <code>kstat_incr_irqs_this_cpu</code>

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
In kernel/irq/irqdesc.c (ffffffff810da49b)
Location: kernel/irq/internals.h:191
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff810da6b8)
Location: kernel/irq/internals.h:191
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff810ddbc8)
Location: kernel/irq/internals.h:191
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
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
In kernel/irq/irqdesc.c (ffffffff810dfa4b)
Location: kernel/irq/internals.h:202
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff810dfc78)
Location: kernel/irq/internals.h:202
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff810e3dcf)
Location: kernel/irq/internals.h:202
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff810e632b)
Location: kernel/irq/internals.h:202
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff810e65f9)
Location: kernel/irq/internals.h:202
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff810ea8f0)
Location: kernel/irq/internals.h:202
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff810e597b)
Location: kernel/irq/internals.h:242
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff810e5c4c)
Location: kernel/irq/internals.h:242
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff810e9fa9)
Location: kernel/irq/internals.h:242
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff810edbdb)
Location: kernel/irq/internals.h:245
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff810edde1)
Location: kernel/irq/internals.h:245
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff810f2509)
Location: kernel/irq/internals.h:245
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff810f601b)
Location: kernel/irq/internals.h:245
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff810f6245)
Location: kernel/irq/internals.h:245
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff810fa959)
Location: kernel/irq/internals.h:245
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff811017ab)
Location: kernel/irq/internals.h:245
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff811019b5)
Location: kernel/irq/internals.h:245
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff81106119)
Location: kernel/irq/internals.h:245
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/irqdesc.c (ffffffff81109fa7)
Location: kernel/irq/internals.h:258
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff8110a1be)
Location: kernel/irq/internals.h:258
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff8110ea55)
Location: kernel/irq/internals.h:258
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
In kernel/irq/irqdesc.c (ffffffff81116377)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff8111658e)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff8111ad15)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff811221be)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff81126f6e)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff8111e19e)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff81122b6e)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff8111e4ae)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff81122cae)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff8113e94e)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff8114327e)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
Location: kernel/irq/internals.h:258
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff81161f5e)
Location: kernel/irq/internals.h:258
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff8116717e)
Location: kernel/irq/internals.h:258
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
Location: kernel/irq/internals.h:260
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff811959ae)
Location: kernel/irq/internals.h:260
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff8119b4ce)
Location: kernel/irq/internals.h:260
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
Location: kernel/irq/internals.h:265
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff811a737e)
Location: kernel/irq/internals.h:265
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff811ad30e)
Location: kernel/irq/internals.h:265
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
Location: kernel/irq/internals.h:265
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff811b6ede)
Location: kernel/irq/internals.h:265
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff811bcf0e)
Location: kernel/irq/internals.h:265
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffff80001017840c)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffff80001017ecc0)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:handle_edge_irq
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
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (c03c9b98)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (c03ceff4)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (c0000000001d224c)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (c0000000001d9638)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffe000112e68)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffe000117114)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
In kernel/irq/irqdesc.c (ffffffff8110e957)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff8110eb6e)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff811132f5)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
In kernel/irq/irqdesc.c (ffffffff810ff6a7)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff810ff8be)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff81104005)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
In kernel/irq/irqdesc.c (ffffffff8110c847)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff8110ca5e)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff811111e5)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
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
In kernel/irq/irqdesc.c (ffffffff81117d57)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
```
```
In kernel/irq/handle.c (ffffffff81117f8e)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (ffffffff8111c9b5)
Location: kernel/irq/internals.h:256
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
```
</details>
</li>
</ul>

## Differences
