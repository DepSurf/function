# Function: <code>irq_resolve_mapping</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113dd85)
Location: include/linux/irqdomain.h:409
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81161b47)
Location: include/linux/irqdomain.h:423
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81195307)
Location: include/linux/irqdomain.h:411
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:generic_handle_domain_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a6c97)
Location: include/linux/irqdomain.h:414
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:generic_handle_domain_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b67b7)
Location: include/linux/irqdomain.h:414
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:generic_handle_domain_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
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
