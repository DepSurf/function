# Function: <code>irq_domain_create_sim</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_sim(struct fwnode_handle *fwnode, unsigned int num_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irq_sim.c (ffffffff8116c3a0)
Location: kernel/irq/irq_sim.c:164
Inline: False
Direct callers:
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
```
**Symbols:**

```
ffffffff8116c3a0-ffffffff8116c46c: irq_domain_create_sim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_sim(struct fwnode_handle *fwnode, unsigned int num_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irq_sim.c (ffffffff811a1340)
Location: kernel/irq/irq_sim.c:164
Inline: False
Direct callers:
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
```
**Symbols:**

```
ffffffff811a1340-ffffffff811a140c: irq_domain_create_sim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_sim(struct fwnode_handle *fwnode, unsigned int num_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irq_sim.c (ffffffff811b3150)
Location: kernel/irq/irq_sim.c:164
Inline: False
Direct callers:
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
```
**Symbols:**

```
ffffffff811b3150-ffffffff811b321c: irq_domain_create_sim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_sim(struct fwnode_handle *fwnode, unsigned int num_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irq_sim.c (ffffffff811c2f70)
Location: kernel/irq/irq_sim.c:164
Inline: False
Direct callers:
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
```
**Symbols:**

```
ffffffff811c2f70-ffffffff811c306b: irq_domain_create_sim (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
