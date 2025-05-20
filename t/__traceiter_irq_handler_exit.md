# Function: <code>__traceiter_irq_handler_exit</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_irq_handler_exit(void *__data, int irq, struct irqaction *action, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810aa0a0)
Location: include/trace/events/irq.h:83
Inline: False
```
**Symbols:**

```
ffffffff810aa0a0-ffffffff810aa0f1: __traceiter_irq_handler_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_irq_handler_exit(void *__data, int irq, struct irqaction *action, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ab0d0)
Location: include/trace/events/irq.h:83
Inline: False
```
**Symbols:**

```
ffffffff810ab0d0-ffffffff810ab11f: __traceiter_irq_handler_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_irq_handler_exit(void *__data, int irq, struct irqaction *action, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810bcbf0)
Location: include/trace/events/irq.h:83
Inline: False
```
**Symbols:**

```
ffffffff810bcbf0-ffffffff810bcc3f: __traceiter_irq_handler_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_irq_handler_exit(void *__data, int irq, struct irqaction *action, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810d3a40)
Location: include/trace/events/irq.h:83
Inline: False
```
**Symbols:**

```
ffffffff810d3a40-ffffffff810d3a9b: __traceiter_irq_handler_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_irq_handler_exit(void *__data, int irq, struct irqaction *action, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810f2780)
Location: include/trace/events/irq.h:83
Inline: False
```
**Symbols:**

```
ffffffff810f2780-ffffffff810f27db: __traceiter_irq_handler_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_irq_handler_exit(void *__data, int irq, struct irqaction *action, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810fe720)
Location: include/trace/events/irq.h:83
Inline: False
```
**Symbols:**

```
ffffffff810fe720-ffffffff810fe77b: __traceiter_irq_handler_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_irq_handler_exit(void *__data, int irq, struct irqaction *action, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81107dd0)
Location: include/trace/events/irq.h:83
Inline: False
```
**Symbols:**

```
ffffffff81107dd0-ffffffff81107e2b: __traceiter_irq_handler_exit (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
