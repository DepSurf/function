# Function: <code>irq_domain_associate_locked</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_domain_associate_locked(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119f770)
Location: kernel/irq/irqdomain.c:591
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff8119f770-ffffffff8119f910: irq_domain_associate_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_domain_associate_locked(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1310)
Location: kernel/irq/irqdomain.c:577
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff811b1310-ffffffff811b146f: irq_domain_associate_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_domain_associate_locked(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c10c0)
Location: kernel/irq/irqdomain.c:577
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked
  - kernel/irq/irqdomain.c:irq_domain_associate_many
```
**Symbols:**

```
ffffffff811c10c0-ffffffff811c121f: irq_domain_associate_locked (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
