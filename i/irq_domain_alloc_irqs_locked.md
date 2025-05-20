# Function: <code>irq_domain_alloc_irqs_locked</code>

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
int irq_domain_alloc_irqs_locked(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811a02f0)
Location: kernel/irq/irqdomain.c:1489
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
**Symbols:**

```
ffffffff811a02f0-ffffffff811a06bd: irq_domain_alloc_irqs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_locked(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b21b0)
Location: kernel/irq/irqdomain.c:1468
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
**Symbols:**

```
ffffffff811b21b0-ffffffff811b2529: irq_domain_alloc_irqs_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_locked(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c1f60)
Location: kernel/irq/irqdomain.c:1468
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
**Symbols:**

```
ffffffff811c1f60-ffffffff811c2314: irq_domain_alloc_irqs_locked (STB_LOCAL)
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
