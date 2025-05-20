# Function: <code>irq_sim_domain_map</code>

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
int irq_sim_domain_map(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irq_sim.c (ffffffff8116c5a0)
Location: kernel/irq/irq_sim.c:117
Inline: False
```
**Symbols:**

```
ffffffff8116c5a0-ffffffff8116c62e: irq_sim_domain_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_sim_domain_map(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irq_sim.c (ffffffff811a1580)
Location: kernel/irq/irq_sim.c:117
Inline: False
```
**Symbols:**

```
ffffffff811a1580-ffffffff811a160e: irq_sim_domain_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_sim_domain_map(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irq_sim.c (ffffffff811b3390)
Location: kernel/irq/irq_sim.c:117
Inline: False
```
**Symbols:**

```
ffffffff811b3390-ffffffff811b341e: irq_sim_domain_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_sim_domain_map(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irq_sim.c (ffffffff811c31e0)
Location: kernel/irq/irq_sim.c:117
Inline: False
```
**Symbols:**

```
ffffffff811c31e0-ffffffff811c329c: irq_sim_domain_map (STB_LOCAL)
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
