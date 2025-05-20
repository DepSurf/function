# Function: <code>handle_enforce_irqctx</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8112141d)
Location: kernel/irq/internals.h:428
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
```
```
In kernel/irq/resend.c (ffffffff811261a6)
Location: kernel/irq/internals.h:428
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
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
In kernel/irq/irqdesc.c (ffffffff8111d3fd)
Location: kernel/irq/internals.h:428
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
```
```
In kernel/irq/resend.c (ffffffff81121d96)
Location: kernel/irq/internals.h:428
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
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
In kernel/irq/irqdesc.c (ffffffff8111d77d)
Location: kernel/irq/internals.h:428
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_irq
```
```
In kernel/irq/resend.c (ffffffff81122116)
Location: kernel/irq/internals.h:428
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
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
In kernel/irq/irqdesc.c (ffffffff8113db08)
Location: kernel/irq/internals.h:428
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_irq_desc
```
```
In kernel/irq/resend.c (ffffffff811426c6)
Location: kernel/irq/internals.h:428
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
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
In kernel/irq/irqdesc.c (ffffffff81161a38)
Location: kernel/irq/internals.h:430
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_irq_desc
```
```
In kernel/irq/resend.c (ffffffff81166219)
Location: kernel/irq/internals.h:430
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
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
In kernel/irq/irqdesc.c (ffffffff81195138)
Location: kernel/irq/internals.h:432
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_irq_desc
```
```
In kernel/irq/resend.c (ffffffff8119a389)
Location: kernel/irq/internals.h:432
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
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
In kernel/irq/irqdesc.c (ffffffff811a6ac8)
Location: kernel/irq/internals.h:437
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_irq_desc
```
```
In kernel/irq/resend.c (ffffffff811ac077)
Location: kernel/irq/internals.h:437
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
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
In kernel/irq/irqdesc.c (ffffffff811b65e8)
Location: kernel/irq/internals.h:437
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_irq_desc
```
```
In kernel/irq/resend.c (ffffffff811bbc77)
Location: kernel/irq/internals.h:437
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
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
