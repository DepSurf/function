# Function: <code>irq_domain_remove_sim</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_remove_sim(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irq_sim.c (ffffffff8116c6af)
Location: kernel/irq/irq_sim.c:203
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
```
**Symbols:**

```
ffffffff8116c470-ffffffff8116c4b0: irq_domain_remove_sim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_remove_sim(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irq_sim.c (ffffffff811a16af)
Location: kernel/irq/irq_sim.c:203
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
```
**Symbols:**

```
ffffffff811a1420-ffffffff811a1460: irq_domain_remove_sim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_remove_sim(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irq_sim.c (ffffffff811b34c6)
Location: kernel/irq/irq_sim.c:203
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
```
**Symbols:**

```
ffffffff811b3230-ffffffff811b3270: irq_domain_remove_sim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void irq_domain_remove_sim(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irq_sim.c (ffffffff811c3346)
Location: kernel/irq/irq_sim.c:203
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:devm_irq_domain_create_sim
```
**Symbols:**

```
ffffffff811c3080-ffffffff811c30c0: irq_domain_remove_sim (STB_GLOBAL)
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
