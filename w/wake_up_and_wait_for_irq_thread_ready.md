# Function: <code>wake_up_and_wait_for_irq_thread_ready</code>

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
void wake_up_and_wait_for_irq_thread_ready(struct irq_desc *desc, struct irqaction *action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81162970)
Location: kernel/irq/manage.c:1280
Inline: True
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff81162970-ffffffff81162a4d: wake_up_and_wait_for_irq_thread_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wake_up_and_wait_for_irq_thread_ready(struct irq_desc *desc, struct irqaction *action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81196210)
Location: kernel/irq/manage.c:1272
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff81196210-ffffffff811962ed: wake_up_and_wait_for_irq_thread_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wake_up_and_wait_for_irq_thread_ready(struct irq_desc *desc, struct irqaction *action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a7bd0)
Location: kernel/irq/manage.c:1278
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff811a7bd0-ffffffff811a7cad: wake_up_and_wait_for_irq_thread_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wake_up_and_wait_for_irq_thread_ready(struct irq_desc *desc, struct irqaction *action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b7730)
Location: kernel/irq/manage.c:1280
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff811b7730-ffffffff811b780d: wake_up_and_wait_for_irq_thread_ready (STB_LOCAL)
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
