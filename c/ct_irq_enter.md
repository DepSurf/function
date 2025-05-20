# Function: <code>ct_irq_enter</code>

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
void ct_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/context_tracking.c (ffffffff820c0260)
Location: kernel/context_tracking.c:365
Inline: False
Direct callers:
  - kernel/softirq.c:irq_enter
  - kernel/entry/common.c:irqentry_enter
  - kernel/context_tracking.c:ct_irq_enter_irqson
```
**Symbols:**

```
ffffffff820c0260-ffffffff820c026f: ct_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ct_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/context_tracking.c (ffffffff821420e0)
Location: kernel/context_tracking.c:365
Inline: False
Direct callers:
  - kernel/softirq.c:irq_enter
  - kernel/entry/common.c:irqentry_enter
  - kernel/context_tracking.c:ct_irq_enter_irqson
```
**Symbols:**

```
ffffffff821420e0-ffffffff821420ef: ct_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ct_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/context_tracking.c (ffffffff822247d0)
Location: kernel/context_tracking.c:365
Inline: False
Direct callers:
  - kernel/softirq.c:irq_enter
  - kernel/entry/common.c:irqentry_enter
  - kernel/context_tracking.c:ct_irq_enter_irqson
```
**Symbols:**

```
ffffffff822247d0-ffffffff822247df: ct_irq_enter (STB_GLOBAL)
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
