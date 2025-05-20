# Function: <code>irq_sim_get_irqchip_state</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int irq_sim_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irq_sim.c (0)
Location: kernel/irq/irq_sim.c:52
Inline: False
```
**Symbols:**

```
ffffffff8116c4b0-ffffffff8116c512: irq_sim_get_irqchip_state (STB_LOCAL)
ffffffff81e5e21f-ffffffff81e5e23b: irq_sim_get_irqchip_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int irq_sim_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irq_sim.c (0)
Location: kernel/irq/irq_sim.c:52
Inline: False
```
**Symbols:**

```
ffffffff811a1470-ffffffff811a14d2: irq_sim_get_irqchip_state (STB_LOCAL)
ffffffff82059ae6-ffffffff82059b02: irq_sim_get_irqchip_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int irq_sim_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irq_sim.c (0)
Location: kernel/irq/irq_sim.c:52
Inline: False
```
**Symbols:**

```
ffffffff811b3280-ffffffff811b32e2: irq_sim_get_irqchip_state (STB_LOCAL)
ffffffff820d8204-ffffffff820d8220: irq_sim_get_irqchip_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int irq_sim_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irq_sim.c (0)
Location: kernel/irq/irq_sim.c:52
Inline: False
```
**Symbols:**

```
ffffffff811c30d0-ffffffff811c3132: irq_sim_get_irqchip_state (STB_LOCAL)
ffffffff821b3485-ffffffff821b34a1: irq_sim_get_irqchip_state.cold (STB_LOCAL)
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
